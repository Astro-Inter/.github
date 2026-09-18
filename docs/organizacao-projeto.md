# Organização do projeto

## Unidade de trabalho

O **card do Jira** fornece o contexto da alteração. Antes de implementar, registre o objetivo, o resultado esperado e o que permitirá considerar a tarefa concluída. Quando uma entrega envolver várias partes, divida-a em cards menores e mantenha o vínculo com a iniciativa maior no Jira.

| Informação | O que registrar |
| --- | --- |
| Objetivo | Problema ou necessidade do ASTRO |
| Escopo | O que será entregue nesta tarefa |
| Critérios de aceite | Comportamentos que precisam ser verificados |
| Dependências | Outros cards, decisões, APIs ou dados necessários |
| Referências | Design, regra de negócio, documentação ou evidência útil |

Os campos exatos, responsáveis, prioridades e estados são definidos no Jira da equipe. Atualize o card durante o trabalho para que ele reflita bloqueios, decisões e conclusão.

## Do card ao código

1. Leia o card e esclareça as regras de negócio afetadas. Para funcionalidades de conformidade, identifique o impacto em treinamentos, validade de certificados, pendências ou exigências de NR, quando aplicável.
2. Crie uma branch com o código do card seguindo [Padrões Git](padroes-git.md).
3. Implemente e valide a mudança de acordo com as instruções do repositório da aplicação.
4. Abra um PR ligado ao mesmo card e explique o que mudou e como conferir o resultado.
5. Trate a revisão e atualize o card conforme o estado real da entrega.

## Onde documentar

| Informação | Local recomendado |
| --- | --- |
| Objetivo e critérios da tarefa | Card do Jira |
| Mudanças e validação de uma entrega | Pull Request |
| Convenções comuns da equipe | Este repositório `.github` |
| Instalação, arquitetura e operação de um serviço | Repositório do serviço |
| Decisão que afeta vários serviços | Documento compartilhado com links a partir dos repositórios afetados |

Não use este guia para reproduzir o quadro de estados ou os campos atuais do Jira: esses dados mudam com o processo. Registre aqui uma convenção quando ela for realmente adotada pela equipe.
