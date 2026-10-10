name: 🛠️ Tarefa de Descrição Simples
description: Crie uma tarefa acionável para a equipe.
title: "<Substitua pelo título>"
labels: ["task"]
body:
  - type: markdown
    attributes:
      value: |
        Preencha os detalhes da tarefa para que qualquer membro da equipe possa assumi-la e desenvolvê-la sem dúvidas.
  - type: textarea
    id: context
    attributes:
      label: 🟢 Contexto / História do Usuário
      description: Explique brevemente a necessidade. Se for uma User Story, use o formato "Como [ator], eu quero [ação] para que [motivo/valor]".
      placeholder: "Como analista da SECOR, eu quero visualizar um dashboard orçamentário para acompanhar os gastos em tempo real."
    validations:
      required: true
