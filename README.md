# Guia de desenvolvimento do ASTRO

Este repositório reúne as convenções de trabalho do **ASTRO**, plataforma de apoio à gestão de conformidade com Normas Regulamentadoras (NRs), treinamentos e certificados de Saúde e Segurança do Trabalho (SST).

O guia ajuda a equipe a manter o trabalho ligado ao Jira, organizar o histórico Git e dar contexto suficiente para revisão. O [perfil da organização](profile/README.md) apresenta o produto, a equipe e as tecnologias. As instruções técnicas de instalação e execução pertencem aos repositórios de cada aplicação.

## Comece por aqui

| Documento | Assunto |
| --- | --- |
| [Introdução](docs/introducao.md) | Contexto do ASTRO, escopo e princípios de trabalho |
| [Padrões Git](docs/padroes-git.md) | Branches, commits, Pull Requests e revisão |
| [Organização do projeto](docs/organizacao-projeto.md) | Jira, divisão das atividades e acompanhamento |
| [Templates](docs/templates.md) | Informações para cards e uso do template de PR |
| [Exemplos](docs/exemplos.md) | Aplicação prática das convenções |

## Fluxo de uma alteração

```mermaid
flowchart LR
    A[Card no Jira] --> B[Branch da main]
    B --> C[Implementação e validação]
    C --> D[Commits]
    D --> E[Pull Request]
    E --> F[Revisão e integração]
```

Use o mesmo código do card no nome da branch, nos commits e no título do PR. A descrição do PR deve conter o link do card e um resumo das mudanças. Consulte [Padrões Git](docs/padroes-git.md) para os formatos completos.

## Alcance deste guia

Estas convenções servem de referência para os repositórios do ASTRO. Instruções específicas de arquitetura, testes, ambientes e entrega devem ser documentadas no próprio repositório que as utiliza. Quando houver uma regra local diferente, registre a exceção ali e mantenha os exemplos deste guia coerentes com a prática da equipe.
