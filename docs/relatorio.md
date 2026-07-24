# Relatório Final — Página Colaborativa de Receitas

## Integrantes do Grupo

- **Nome do projeto:** Página Colaborativa de Receitas
- **Integrantes:** Diogo Esteves, Gabriel Simão, Kauan Fortunato e Daniel Fiel
- **Repositório:** [GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel)
- **Data da atividade analisada:** 24 de julho de 2026

## Objetivo do Projeto

O projeto teve como objetivo criar uma página colaborativa de receitas e praticar um fluxo de trabalho com Git e GitHub. Cada integrante trabalhou em branches próprias, criou commits com alterações pequenas e identificáveis e integrou o trabalho na branch `main` através de Pull Requests.

O resultado final inclui:

- uma página inicial em `src/index.html`;
- quatro receitas individuais;
- uma receita colaborativa construída em quatro etapas;
- identificação dos autores e integrantes na página inicial;
- documentação das regras de contribuição e do padrão de nomes dos ficheiros;
- utilização de Issues, branches, commits e Pull Requests.

## Funcionalidades e Conteúdo Implementados

### Página inicial

A página `src/index.html` foi criada e atualizada para apresentar:

- o título e a descrição do projeto;
- links funcionais para todas as receitas;
- o autor de cada receita;
- a lista dos quatro integrantes;
- a receita colaborativa do grupo.

### Receitas individuais

Cada receita contém autor, categoria, dificuldade, tempo, rendimento, ingredientes, modo de preparação e uma dica:

| Receita | Responsável | Ficheiro |
|---|---|---|
| Bolo de Cenoura com Cobertura de Chocolate | Gabriel Simão | `src/receitas/receita-bolo-de-cenoura.md` |
| Pastéis de Nata | Kauan Fortunato | `src/receitas/receita-pasteis-de-nata.md` |
| Pão de Queijo | Diogo Esteves | `src/receitas/receita-pao-de-queijo.md` |
| Panquecas Veganas de Banana | Daniel Fiel | `src/receitas/receita-panquecas-veganas.md` |

Foi ainda corrigido um erro de digitação na receita de pão de queijo.

### Receita colaborativa

O ficheiro `src/receitas/receita-colaborativa.md` contém o **Smoothie Tropical do Grupo**. A receita foi construída por quatro Pull Requests consecutivos, com um passo acrescentado por cada integrante:

1. Diogo Esteves criou a estrutura e adicionou o primeiro passo;
2. Gabriel Simão adicionou o segundo passo;
3. Kauan Fortunato adicionou o terceiro passo;
4. Daniel Fiel adicionou o quarto passo.

### Documentação

Também foram realizadas as seguintes melhorias:

- atualização do `README.md` com os integrantes, as receitas e informações do projeto;
- atualização de `CONTRIBUTING.md` com regras para branches, commits, Pull Requests e Issues;
- definição do padrão `receita-nome.md` para os ficheiros de receitas.

## Branches Criadas

Foram usadas 14 branches de trabalho, além da branch principal `main`:

| Branch | Objetivo |
|---|---|
| `feature/bolo-de-cenoura` | Criar a receita de bolo de cenoura |
| `feat/pasteis-de-nata` | Criar a receita de pastéis de nata |
| `feature/pao-de-queijo` | Criar a receita de pão de queijo |
| `feature/panquecas-veganas` | Criar a receita de panquecas veganas |
| `feature/pagina-inicial` | Criar a estrutura da página inicial |
| `feature/link-bolo` | Adicionar/corrigir o link do bolo de cenoura |
| `feat/link-nata` | Adicionar o link dos pastéis de nata |
| `docs/atualizar-readme` | Atualizar o README e os integrantes |
| `docs/padrao-nomes` | Documentar o padrão de nomes dos ficheiros |
| `docs/lista-receitas` | Atualizar a lista de receitas e os autores |
| `feature/colaborativa-base` | Criar a base e o primeiro passo da receita colaborativa |
| `feature/colaborativa-passo2` | Adicionar o segundo passo da receita colaborativa |
| `feature/colaborativa-passo3` | Adicionar o terceiro passo da receita colaborativa |
| `feature/colaborativapasso4` | Adicionar o quarto passo da receita colaborativa |

Todas estas branches foram integradas em `main` através de Pull Requests. A branch `feature/link-bolo` foi utilizada nos PRs #6 e #12.

## Histórico de Commits e Contribuições

O histórico final contém **36 commits**, incluindo os commits de merge dos Pull Requests. A página de contribuições pode ser consultada em [Insights — Contributors](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/graphs/contributors).

### Número de commits por integrante

Os valores apresentados pelo GitHub, incluindo commits de conteúdo e de merge, são:

| Integrante | Utilizador no GitHub | N.º de commits |
|---|---|---:|
| Gabriel Simão | `GabrielSimao67` | 15 |
| Diogo Esteves | `Diogo1306` | 8 |
| Kauan Fortunato | `KauanFortunato` | 8 |
| Daniel Fiel | `danielfiel` | 5 |
| **Total** | — | **36** |

Alguns commits aparecem localmente com variações do nome do autor, como `DiogoEsteves`/`Diogo Esteves` e `Kauan`/`Kauan Fortunato`. O GitHub associa-os às respetivas contas através do autor e do endereço de correio eletrónico.

### Exemplos de boas mensagens de commit

- `feat: adicionar receita de bolo de cenoura com cobertura de chocolate`
- `feat: Receita de pasteis de nata`
- `feat: adicionar receita de pão de queijo`
- `feat: adicionar receita vegana de panquecas de banana`
- `chore: criar estrutura da página inicial de receitas`
- `fix: corrigir erro de digitação na receita de pão de queijo`
- `docs: README.md atualizado com os integrantes e informações`
- `docs: padronizar nomes dos ficheiros de receita`
- `feat: passo 4 da receita colaborativa`

As mensagens utilizam prefixos como `feat`, `fix`, `docs` e `chore`, permitindo perceber rapidamente o tipo e o objetivo de cada alteração.

## Issues Criadas

Foram criadas e concluídas quatro Issues:

| Issue | Descrição | Responsável | Estado |
|---|---|---|---|
| [#2](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/issues/2) | Receita de pastéis de nata | Kauan Fortunato | Fechada |
| [#4](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/issues/4) | Criar receita de pão de queijo | Diogo Esteves | Fechada |
| [#5](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/issues/5) | Criar receita vegana de panquecas de banana | Daniel Fiel | Fechada |
| [#9](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/issues/9) | Rever o README e adicionar os integrantes | Kauan Fortunato | Fechada |

As Issues #2, #4 e #5 utilizaram a label `enhancement`; a Issue #9 utilizou a label `documentation`.

## Pull Requests

Foram integrados **15 Pull Requests**:

| PR | Autor | Alteração |
|---|---|---|
| [#1](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/1) | Gabriel Simão | Receita de bolo de cenoura |
| [#3](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/3) | Kauan Fortunato | Receita de pastéis de nata |
| [#6](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/6) | Gabriel Simão | Primeiro link do bolo na página inicial |
| [#7](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/7) | Daniel Fiel | Receita de panquecas veganas |
| [#8](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/8) | Diogo Esteves | Receita de pão de queijo |
| [#11](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/11) | Diogo Esteves | Estrutura da página inicial |
| [#12](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/12) | Gabriel Simão | Correção do link do bolo |
| [#13](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/13) | Kauan Fortunato | Link dos pastéis de nata |
| [#14](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/14) | Kauan Fortunato | Atualização do README |
| [#15](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/15) | Daniel Fiel | Padrão de nomes dos ficheiros |
| [#16](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/16) | Diogo Esteves | Lista de receitas e integrantes |
| [#17](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/17) | Diogo Esteves | Base e passo 1 da receita colaborativa |
| [#18](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/18) | Gabriel Simão | Passo 2 da receita colaborativa |
| [#19](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/19) | Kauan Fortunato | Passo 3 da receita colaborativa |
| [#20](https://github.com/GabrielSimao67/projeto-receitas-GabrielSimao-DiogoEsteves-KauanFortunato-DanielFiel/pull/20) | Daniel Fiel | Passo 4 da receita colaborativa |

Vários PRs tiveram um colega solicitado como revisor, demonstrando a intenção de revisão cruzada. Contudo, o histórico do GitHub não apresenta reviews formais, aprovações ou comentários submetidos. Os PRs foram integrados por merge commits, preservando no histórico a identificação de cada Pull Request.

## Conflitos e Resoluções

O histórico não permite confirmar a existência de conflitos resolvidos manualmente, pois não existem commits ou comentários que descrevam uma resolução de conflito específica.

Existem, no entanto, merges de sincronização que mostram a atualização de branches antes da integração:

- a branch `feature/pagina-inicial` recebeu um merge de `main`;
- a branch `feat/link-nata` recebeu um merge de `main`;
- também foram efetuadas sincronizações da branch `main` com o repositório remoto.

Esta prática permitiu incorporar alterações feitas por outros membros antes do merge final e reduziu o risco de conflitos. Como melhoria futura, qualquer conflito manual deve ser descrito no respetivo Pull Request.

## Dificuldades Enfrentadas

Com base no histórico do projeto, as principais dificuldades e ajustes foram:

- coordenar várias alterações feitas no mesmo ficheiro `src/index.html`;
- manter as branches atualizadas com `main`;
- corrigir os links das receitas depois da criação da estrutura inicial;
- uniformizar os nomes dos ficheiros;
- corrigir um erro de digitação na receita de pão de queijo;
- coordenar quatro Pull Requests dependentes para construir a receita colaborativa;
- manter consistentes os nomes dos autores nos commits.

## Principais Comandos Git Utilizados

O GitHub não guarda um registo exato de todos os comandos executados localmente. Contudo, o histórico de branches, commits, pushes e merges corresponde ao seguinte fluxo:

| Comando | Finalidade |
|---|---|
| `git clone <url-do-repositorio>` | Obter uma cópia local do projeto |
| `git status` | Verificar a branch atual e os ficheiros alterados |
| `git switch -c <nome-da-branch>` | Criar e mudar para uma branch de trabalho |
| `git add <ficheiro>` | Preparar alterações para o commit |
| `git commit -m "mensagem"` | Registar uma alteração com uma mensagem descritiva |
| `git push -u origin <nome-da-branch>` | Publicar a branch no GitHub |
| `git fetch origin` | Obter referências e alterações do repositório remoto |
| `git pull origin main` | Atualizar a branch com as alterações de `main` |
| `git merge main` | Integrar `main` numa branch de trabalho |
| `git log --graph --oneline --all` | Consultar o histórico e os merges |

Após o `push`, os Pull Requests foram criados no GitHub e integrados na branch `main`.

## Conclusão

A atividade permitiu aplicar, num projeto pequeno mas completo, os conceitos essenciais de colaboração com Git e GitHub. O grupo distribuiu tarefas através de Issues e branches, criou receitas individuais, construiu uma receita em quatro contribuições sucessivas e integrou 15 Pull Requests.

Os principais aprendizados foram a importância de trabalhar em branches separadas, escrever mensagens de commit claras, manter a branch atualizada, associar tarefas a responsáveis e integrar alterações através de Pull Requests. Como evolução do processo, o grupo pode registar reviews e aprovações formais, relacionar cada PR com a respetiva Issue e documentar explicitamente eventuais conflitos e decisões tomadas durante a revisão.
