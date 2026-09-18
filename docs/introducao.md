# Introdução

## O ASTRO

O ASTRO apoia empresas no acompanhamento de exigências ligadas às Normas Regulamentadoras e à Saúde e Segurança do Trabalho. O produto busca centralizar informações sobre treinamentos, certificados, pendências e atualizações das NRs. A equipe trabalha com interfaces web e mobile, serviços de back-end, dados e recursos de inteligência artificial, conforme a [apresentação do projeto](../profile/README.md).

Este guia documenta **como a equipe organiza e revisa alterações**. Regras de negócio, instruções de execução e decisões técnicas de cada serviço devem acompanhar o código correspondente.

## Objetivos

- Ligar cada alteração ao card do Jira que explica seu objetivo.
- Facilitar a leitura do histórico de branches, commits e Pull Requests.
- Dar ao revisor contexto, instruções de validação e visibilidade sobre o impacto da mudança.
- Atualizar a documentação quando o comportamento do produto ou o processo de trabalho mudar.

## Princípios de trabalho

1. **Contexto antes da implementação:** descreva o problema, o resultado esperado e os critérios de aceite no card.
2. **Entregas delimitadas:** mantenha cada branch e PR focados no mesmo objetivo. Divida mudanças independentes em cards e PRs próprios.
3. **Validação visível:** registre no PR o que foi testado e como outra pessoa pode conferir a mudança.
4. **Cuidado com dados de SST:** use exemplos sem dados pessoais, credenciais ou certificados reais ao escrever cards, documentação e evidências.
5. **Documentação junto da mudança:** atualize o guia, o README ou a documentação técnica afetada quando uma convenção ou comportamento mudar.

## Caminho de leitura

1. [Organização do projeto](organizacao-projeto.md) para planejar e acompanhar o trabalho.
2. [Padrões Git](padroes-git.md) para criar branch, commits e PR.
3. [Templates](templates.md) e [Exemplos](exemplos.md) para preencher os artefatos.
