# Templates e informações mínimas

Os modelos abaixo ajudam a registrar o contexto necessário para desenvolvimento e revisão. Adapte as seções ao tipo de tarefa e aos campos do Jira usados pela equipe.

## Card do Jira

```markdown
## Contexto
Qual problema ou necessidade esta tarefa atende?

## Resultado esperado
O que deve funcionar ou existir ao final?

## Critérios de aceite
- [ ] Cenário verificável 1
- [ ] Cenário verificável 2

## Dependências e referências
Links para decisões, design, documentação ou outros cards, quando houver.
```

Para um bug, acrescente passos para reprodução, resultado atual, resultado esperado e ambiente. Para documentação, indique quais páginas e leitores são afetados. Para mudanças em dados de funcionários ou SST, use evidências anonimizadas.

## Pull Request

O modelo aplicado automaticamente pelo GitHub está em [pull_request_template.md](../pull_request_template.md). Preserve as quatro seções existentes e substitua as instruções pelo conteúdo da entrega:

- **Descrição:** objetivo e efeito da mudança.
- **Jira:** link para o card correspondente ao identificador do título, branch e commits.
- **O que foi alterado:** componentes, regras ou documentos efetivamente modificados.
- **Tipo da alteração:** marque as opções pertinentes.

Na descrição, inclua também **como validar** quando o procedimento não for evidente. Informe os comandos executados e o resultado, ou os passos manuais e as evidências necessárias. Se houver limitação conhecida ou impacto de migração, descreva-a no PR.

## Revisão rápida antes de solicitar aprovação

- [ ] O título, a branch e os commits apontam para o mesmo card do Jira.
- [ ] A descrição explica o efeito da mudança para quem usa ou mantém o ASTRO.
- [ ] As verificações relevantes foram executadas e relatadas.
- [ ] A documentação afetada foi atualizada.
- [ ] Prints, logs e exemplos não expõem credenciais nem dados pessoais.
