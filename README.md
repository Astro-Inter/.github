<p align="center">
  <img src="profile/banner.svg" width="100%" alt="ASTRO — Conformidade em órbita. Gestão de NRs, treinamentos e certificados.">
</p>

<h1 align="center">Guia de desenvolvimento do ASTRO</h1>

<p align="center">
  Convenções compartilhadas para transformar cada card em uma entrega clara, rastreável e fácil de revisar.
</p>

Este repositório reúne as convenções de trabalho do **ASTRO**, plataforma SaaS em desenvolvimento para gestão de conformidade com Normas Regulamentadoras (NRs) e processos de Segurança e Saúde no Trabalho (SST).

O produto busca reduzir o trabalho manual de RH, profissionais de SST e Gestores, centralizando a estrutura da empresa, os Colaboradores, as obrigações por Cargo, as Conformidades, os Eventos e as evidências. A experiência combina gestão pela Web e acompanhamento e operação pelo Mobile, incluindo Formulários e inspeções.

O guia ajuda a equipe a manter o trabalho ligado ao Jira, organizar o histórico Git e dar contexto suficiente para revisão. O [perfil da organização](profile/README.md) apresenta o produto, a equipe e as tecnologias. As instruções técnicas de instalação e execução pertencem aos repositórios de cada aplicação.

## Comece por aqui

| Para... | Consulte |
| --- | --- |
| Consultar o escopo, as regras e os fluxos do produto | [Base funcional no astro-knowledge](https://github.com/Astro-Inter/astro-knowledge/blob/main/docs/astro/README.md) |
| Entender o produto e os princípios da equipe | [Introdução](docs/introducao.md) |
| Nomear branches, commits e Pull Requests | [Padrões Git](docs/padroes-git.md) |
| Organizar cards, escopo e acompanhamento | [Organização do projeto](docs/organizacao-projeto.md) |
| Preencher cards e descrições de PR | [Templates](docs/templates.md) |
| Ver as convenções aplicadas na prática | [Exemplos](docs/exemplos.md) |

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

## Regra de ouro

```text
card claro → branch focada → commits rastreáveis → PR verificável
```

Cada entrega deve responder, sem ambiguidade: **por que a mudança existe, o que foi alterado e como outra pessoa pode validá-la**.

<table>
  <tr>
    <td width="76%">
      <h3>Astrinho acompanha a tripulação</h3>
      <p>Nosso mascote representa uma tecnologia próxima e clara. Ele também lembra que documentação, validação e colaboração fazem parte da mesma missão.</p>
      <p><a href="profile/README.md"><strong>Conheça o ASTRO e a equipe →</strong></a></p>
    </td>
    <td width="24%" align="center">
      <img src="profile/assets/mascote-astro.png" width="180" alt="Astrinho, mascote robô do ASTRO.">
    </td>
  </tr>
</table>

## Alcance deste guia

Estas convenções servem de referência para os repositórios do ASTRO. Instruções específicas de arquitetura, testes, ambientes e entrega devem ser documentadas no próprio repositório que as utiliza. Quando houver uma regra local diferente, registre a exceção ali e mantenha os exemplos deste guia coerentes com a prática da equipe.
