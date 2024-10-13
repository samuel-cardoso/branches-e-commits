# branches-e-commits

## Padrão para branches
Escreve-los sempre em inglês.

A branche deve ser constituída com as seguintes partes:

feat-satisfaction-form-NP-73

- Prefixo: feat
- Conteúdo: satisfaction-form
- Sufixo: NP-73

O commit deve ser constituído com as seguintes partes:

feat: create field name

- Prefixo: feat
- Conteúdo: create field name

### Prefixo

As branches e commits são prefixados com um tipo, que consiste em um substantivo. 

Os mais usados são:

1. feat (Feature)
Significado: É utilizado para indicar que a branch está relacionada ao desenvolvimento de uma nova funcionalidade ou recurso dentro do sistema.
Exemplo: feat-cadastro-veiculos — Implementação da funcionalidade de cadastro de veículos.

3. fix (Bugfix)
Significado: Usado para correções de bugs ou problemas no sistema que já existem em produção ou no desenvolvimento.
Exemplo: fix-erro-login — Correção de um problema no processo de login.

5. chore (Tarefa de manutenção e setup do projeto)
Significado: Utilizado para tarefas de manutenção que não impactam diretamente o código de produção ou as funcionalidades do sistema. Pode incluir configurações, atualizações de dependências, ou ajustes que não afetam o comportamento do software.
Exemplo: chore-atualizacao-libraries — Atualização de bibliotecas ou dependências.

7. refactor (Refatoração)
Significado: Indica que a branch é usada para refatorar o código, ou seja, melhorar a estrutura e qualidade sem alterar o comportamento externo do sistema. Geralmente, esse tipo de branch melhora a legibilidade, simplifica a lógica ou otimiza a performance.
Exemplo: refactor-codigo-auth — Refatoração da lógica de autenticação.

9. test (Testes)
Significado: Usado para branches que lidam com a criação ou modificação de testes (testes unitários, integração, etc.).
Exemplo: test-validacoes-login — Adição de testes para validar o processo de login.

11. docs (Documentação)
Significado: Utilizado para mudanças relacionadas à documentação do projeto. Isso pode incluir documentação do código, README, ou manuais de usuário.
Exemplo: docs-adicionar-readme — Atualização ou criação de documentação.

13. style (Estilo de código)
Significado: Usado para mudanças que afetam apenas a formatação do código, como indentação, espaçamento, correção de erros de lint, etc., sem alterar a lógica ou o comportamento do código.
Exemplo: style-ajustes-espacamento — Ajustes na formatação do código.

15. perf (Performance)
Significado: Indica uma branch destinada a melhorar a performance do sistema, como otimização de tempo de execução, redução de consumo de memória, etc.
Exemplo: perf/melhoria-renderizacao — Melhoria na performance de renderização de componentes.

17. ci (Integração Contínua)
Significado: Usado para modificações relacionadas à configuração ou ajuste de integração contínua (CI), como pipelines de build, testes automáticos, etc.
Exemplo: ci/ajustar-pipeline — Ajustes na configuração do pipeline de integração contínua.

19. build (Sistema de build)
Significado: Refere-se a mudanças no sistema de build ou nas ferramentas de compilação, como configurações de Webpack, Gulp, ou dependências de build.
Exemplo: build-atualizar-webpack-config — Atualização na configuração do Webpack.

21. revert (Reversão)
Significado: Utilizado quando é necessário reverter uma alteração anterior, voltando o código para um estado anterior.
Exemplo: revert-feat-cadastro-veiculos — Reversão da feature de cadastro de veículos que foi implementada anteriormente.

23. hotfix (Correção urgente)
Significado: Usado para correções de bugs críticos que precisam ser feitos com urgência, especialmente em produção. É similar ao fix, mas com um caráter de urgência.
Exemplo: hotfix-ajuste-login-producao — Correção imediata de um problema em produção relacionado ao login.

### Conteúdo

O conteúdo(no Conventional Commits está como "body", mas adaptei de uma forma diferente para meu uso) é a parte responsável do commit semântico por descrever de maneira simples e objetiva o que foi realizado na branch ou commit em questão.

### Sufixo

O sufixo é a parte da branche que corresponde ao nome do projeto(sigla) e ao número da tarefa da ferramenta de gerenciamento de projetos. (trello, slack...)
  
## Importante.

Erros mais comuns com Git e como corrigí-los: https://www.campuscode.com.br/conteudos/erros-mais-comuns-com-git-e-como-corrigi-los

## Fontes

Conventional Commits: https://www.conventionalcommits.org/en/v1.0.0/
Artigo sobre padrões e nomeclaturas: https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106
GeekHunter: https://blog.geekhunter.com.br/o-que-e-commit-e-como-usar-commits-semanticos/
