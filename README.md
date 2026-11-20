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

A solução vale a pena pois reúne em um só lugar as informações dos projetos de extensão da FCT.

## Fluxo único

O menor caminho de ponta a ponta que já entrega valor:

1. **Professor(a) faz login** com a conta institucional da UFPA e acessa a área de gerenciamento.
2. **Professor(a) cadastra o projeto** que coordena (título, descrição, áreas, curso, vagas, e-mail de contato).
3. Depois de **aprovado pela PROEX**, o projeto ativo passa a aparecer automaticamente na **vitrine pública**, visível a qualquer visitante.
4. **Aluno(a) acessa a vitrine**, filtra por área/curso e abre a **página de detalhes** do projeto.
5. Aluno(a) entra em contato pelo email divulgado pelo(a) professor(a).

## Escopo do MVP

**Obrigatório (Must)**:
- Cadastro e edição de projeto pelo(a) professor(a) autenticado.
- Vitrine pública listando os projetos ativos e aprovados pela PROEX.
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

- **Usa:** aluno(a) da FCT e visitante público (consultam) e professor(a) coordenador(a) (publica e mantém).
- **É afetado sem usar diretamente:** a coordenação da FCT, que ganha visibilidade institucional das ações de extensão, e a equipe de TI que hospeda a plataforma.
- **Pode vetar:** a PROEX (Pró-Reitoria de Extensão), que aprova cada projeto antes de ele aparecer na vitrine.

## Equipe

| Nome | Papel |
|---|---|
| Pedro Antônio Raiol de Souza | Backend / API e banco de dados |
| Mariana Gonçalves Ribeiro | Frontend / Interface |
| Pedro Henrique Santos de Castro | Documentação e requisitos |
| Tainá Alves Baia | QA e DevOps (testes e CI) |

## Contexto acadêmico

- Disciplina: EC01025 — Engenharia de Software · 2026.4
- Professor: Victor Ferreira
- UFPA — Faculdade de Engenharia de Computação e Telecomunicações (FCT)

## Status

P0, P1 e P2 entregues. P3 em andamento: a primeira versão do diagrama de classes do fluxo único já está em `docs/P3/`. Ainda não há implementação.

## Documentos

| Entrega | Arquivo |
|---|---|
| P1 | [Histórias de usuário](historias_usuario_extendeFCT.txt) |
| P2 | [Documento de requisitos v1.0](docs/P2/Modelo%20P2-V1.0-%20Documento%20de%20Requisitos.pdf) · [v0.2](docs/P2/Modelo%20P2_V0.2-%20Documento%20de%20Requisitos%20.pdf) · [v0.1](docs/P2/Modelo%20P2-V0.1-%20Documento%20de%20Requisitos.pdf) |
| P2 | [Inspeção cruzada (System Lab)](docs/P2/inspecao_systemlab_P2.pdf) |
| P3 | [Diagrama de classes](docs/P3/P3_Equipe03_diagrama_classes.png) ([fonte Graphviz](docs/P3/P3_Equipe03_diagrama_classes.dot)) |
| Estudo dirigido 18/11 | [Respostas](docs/estudo-dirigido-18-11/) |

## Cronograma

| Entrega | Data | Conteúdo |
|---|---|---|
| P0 | 11/09 OK | Equipe, repositório e canvas |
| P1 | 23/09 OK | Visão do produto e backlog |
| P2 | 14/10 OK | Documento de requisitos |
| P3 | 16/11 (em andamento) | Modelo UML e arquitetura |
| P4 | 23/11 | Documentação técnica |
| P5 | 02/12 | Testes e integração contínua |
| P6 | 16/12 | Repositório e release |
