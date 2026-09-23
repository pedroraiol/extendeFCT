# ExtendeFCT

> Vitrine para projetos de extensão da FCT.

Site para divulgação dos projetos de extensão coordenados por professores da Faculdade de Engenharia de Computação e Telecomunicações (FCT/UFPA). Professores podem publicar e manter os projetos que coordenam enquanto os alunos descobrem esses projetos num só lugar.

## Problema

A divulgação de projetos de extensão da FCT hoje é fragmentada: cada professor divulga do seu jeito: seja por SIGAA (conhecido por apresentar várias instabilidades), grupo de WhatsApp, "boca a boca". Um aluno interessado em participar não tem um lugar único para descobrir quais projetos estão ativos, quem coordena cada um e como entrar em contato. O resultado é que projetos bons ficam invisíveis para quem se interessaria por eles.

## Para quem

| Papel | Quem é | O que faz no sistema |
|---|---|---|
| Professor(a) coordenador(a) | Docente da FCT que coordena um projeto de extensão | Cadastra e mantém atualizado o projeto que coordena (descrição, área, vagas, contato) |
| Aluno(a) da FCT | Estudante de graduação interessado em participar de extensão | Navega, filtra e consulta os projetos ativos para decidir em qual entrar em contato |

## Por que a solução vale a pena

A solução vale a pena pois possibilita agrupar as informações de projetos de extensão na UFPA em um só lugar.

## Fluxo único (P0)

O menor caminho de ponta a ponta que já entrega valor:

1. **Professor(a) faz login** e acessa a área de gerenciamento.
2. **Professor(a) cadastra o projeto** que coordena (título, descrição, área, vagas, contato).
3. O projeto passa a aparecer automaticamente na **vitrine pública**, visível a qualquer visitante.
4. **Aluno(a) acessa a vitrine**, filtra por área/curso e abre a **página de detalhes** do projeto.
5. Aluno(a) entra em contato pelo email divulgado pelo(a) professor(a).

## Escopo desta entrega (P0)

**Obrigatório (Must)**:
- Cadastro e edição de projeto pelo(a) professor(a) autenticado.
- Vitrine pública listando os projetos ativos.
- Página de detalhes de um projeto.

**Desejável (Should)**:
- Filtro de projetos por área/curso.
- Busca por nome do professor(a).

## O que ficou de fora

- Sistema de candidatura/inscrição dentro da plataforma: o planejamento é só de divulgação. Se o(a) aluno(a) estiver interessado(a) em participar basta mandar um e-mail ao(à) professor(a).
- Login ou cadastro de alunos: a vitrine é pública e não precisa de autenticação.
- Avaliação ou feedback de projetos pelos alunos.
- Painel de administração institucional (múltiplos níveis de aprovação/coordenação).

## Stakeholders

- **Usa:** aluno(a) da FCT (consulta) e professor(a) coordenador(a) (publica e mantém).
- **É afetado sem usar diretamente:** a coordenação da FCT, que ganha visibilidade institucional das ações de extensão.
- **Pode vetar:** a coordenação de extensão da FCT, por se tratar de divulgação oficial vinculada a professores da faculdade.

## Equipe

| Nome | Papel |
|---|---|
| Pedro Antônio Raiol de Souza | Backend / API e banco de dados |
| Mariana Gonçalves Ribeiro | Frontend / Interface |
| Pedro Henrique Santos de Castro | Documentação e requisitos |
| Tainá Alves Bahia | QA e DevOps (testes e CI) |

## Contexto acadêmico

- Disciplina: EC01025 — Engenharia de Software · 2026.4
- Professor: Victor Ferreira
- UFPA — Faculdade de Engenharia de Computação e Telecomunicações (FCT)

## Status

P0 (escopo) e P1 (visão do produto e backlog) entregues. Ainda não há implementação.

## Cronograma

| Entrega | Data | Conteúdo |
|---|---|---|
| P0 | 11/09 ✅ | Equipe, repositório e canvas |
| P1 | 23/09 (hoje) ✅ | Visão do produto e backlog |
| P2 | 14/10 | Documento de requisitos |
| P3 | 16/11 | Modelo UML e arquitetura |
| P4 | 23/11 | Documentação técnica |
| P5 | 02/12 | Testes e integração contínua |
| P6 | 16/12 | Repositório e release |
