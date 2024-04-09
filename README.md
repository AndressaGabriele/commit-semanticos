# Guia de Commits Semânticos Simplificado 👻

Este guia descreve as convenções para mensagens de commit semântico, utilizando uma abordagem padronizada para manter um histórico de alterações claro e organizado.

## Mensagens de Commit

Os commits devem seguir o seguinte padrão:

- `<tipo>(<escopo opcional>): <descrição>`


### Tipos de Commit

| Tipo       | Descrição                                                              |
|------------|------------------------------------------------------------------------|
| feat       | Uma nova funcionalidade ou adição de uma nova característica.          |
| fix        | Correção de bugs ou problemas identificados.                            |
| docs       | Alterações relacionadas à documentação.                                 |
| style      | Alterações que não afetam o código (espaços em branco, formatação, etc.)|
| refactor   | Refatoração de código, sem adição de novas funcionalidades ou correção de bugs. |
| test       | Adição ou modificação de testes.                                        |
| chore      | Tarefas de manutenção, como atualização de dependências ou configurações. |
| perf       | Alterações relacionadas à otimização de desempenho.                     |
| revert     | Reverte uma alteração anterior.                                         |
| build      | Alterações relacionadas ao sistema de build, configurações ou scripts.   |
| ci         | Alterações relacionadas à integração contínua (CI), pipelines de implantação, etc. |
| deps       | Alterações relacionadas às dependências do projeto.                     |
| merge      | Commits de merge resultantes da mesclagem de branches.                   |
| release    | Commits que marcam uma versão específica do projeto.                    |

### Escopo (opcional)

O escopo pode ser usado para especificar a parte do código que foi alterada.

### Descrição

A descrição deve ser clara e concisa, descrevendo o que foi feito no commit.

## Exemplos

- `feat(authentication): Adiciona autenticação por token JWT`
- `fix(validation): Corrige validação de entrada de dados`
- `docs(readme): Atualiza o README com instruções de uso`
- `style(css): Ajusta a formatação do código CSS`
- `refactor(api): Refatora método de busca para melhorar desempenho`
- `test(api): Adiciona teste para endpoint de registro`
- `chore(dependencies): Atualiza versões das dependências`
- `perf(api): Otimiza consulta de banco de dados`
- `revert(featureX): Reverte adição da funcionalidade X`
- `build(docker): Atualiza configurações do Dockerfile`
- `ci(pipeline): Adiciona estágio de teste de integração ao pipeline`
- `deps(package.json): Atualiza pacote 'axios' para a versão 2.0.0`
- `merge(featureY): Merge branch 'featureY' into 'main'`
- `release(v1.2.3): Marca a versão 1.2.3 como release`


## Convenções Adicionais

- Mantenha cada commit o mais granular possível, abordando apenas uma alteração por commit.
- Utilize o imperativo presente ("Adiciona", "Corrige", "Atualiza") na descrição do commit.
- Limite a linha de descrição do commit a 72 caracteres.
- Use o corpo do commit para fornecer detalhes adicionais, quando necessário.

## Autor ✍️

**Andressa Gabriele**

