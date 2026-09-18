# Padrões Git do ASTRO

As descrições devem ser escritas em português. O mesmo identificador do Jira acompanha a branch, os commits e o título do Pull Request da tarefa. Os tipos mais usados são `feat` (funcionalidade), `fix` (correção) e `docs` (documentação).

## Branches

Crie a branch de trabalho a partir da `main`, salvo quando o repositório da aplicação documentar outro fluxo.

```text
<tipo>/<JIRA>-<descricao-em-kebab-case>
```

Exemplo de formato:

```text
feat/KNBN-0001-fluxo-esqueceu-senha
```

Use letras minúsculas, hífens e palavras sem acentos na descrição. Copie o identificador de um card real; o código acima é apenas ilustrativo.

## Commits

Use Conventional Commits com o card no lugar do escopo:

```text
<tipo>(<JIRA>): <descrição curta em português>
```

Exemplo de formato:

```text
feat(KNBN-0123): criar tela de importação
```

Prefira uma ação objetiva no infinitivo. Separe mudanças independentes em commits distintos e mantenha o mesmo Jira da branch. Outros tipos de Conventional Commits podem ser usados quando a alteração justificar, seguindo eventuais regras do repositório.

## Pull Requests

O título segue:

```text
[<JIRA>] <tipo>: <Descrição legível em português>
```

Exemplo de formato:

```text
[KNBN-0123] feat: Importação de funcionários
```

Preencha o [template de PR](../pull_request_template.md) com descrição, link do Jira, lista do que mudou e tipo da alteração. Acrescente instruções de validação e evidências quando forem necessárias para a revisão. Abra como rascunho se ainda houver trabalho em andamento.

## Revisão e integração

- Confira se o objetivo do PR corresponde ao card e se o código do Jira é o mesmo nos três registros.
- Execute as verificações disponíveis no repositório e informe o resultado ao revisor.
- Revise impacto em regras de negócio, dados, segurança, interface e documentação conforme a mudança.
- Responda aos comentários e integre o PR conforme as proteções e o fluxo do repositório.

Este guia não define branches de homologação, estratégia universal de merge, versão automática ou processo de release. Essas decisões dependem do repositório e devem estar registradas junto à aplicação.
