# Plano de Gerenciamento e configuração de software

## 1. Introdução

O presente documento tem como finalidade orientar a todos que buscam contribuir com o repositório, apresentando padrões, políticas, ferramentas, instruindo sobre o ambiente de desenvolvimento.

## 2 - Política de Commits

Os commits realizados no repositório do projeto deverão seguir o padrão definido abaixo:
- Os commits devem ser atômicos e significativos, descrevendo o que foi implementado.
- Mensagem do commit em português, com verbo no gerúndio indicando o propósito do commit, iniciado por letra maiúscula e sem ponto final.

Exemplo de mensagem de commit:
```Atualizando readme.md```


## 3 - Política de Branches
Para garantir um fluxo de trabalho contínuo e de forma padronizada possibilitando o rastreamento das funcionalidades desenvolvidas e facilitando a implementação de _pipelines_ de integração(CI) e entrega(CD) contínua, será utilizada a metodologia do Git Flow nos repositórios [RADAR-backend](https://github.com/mecassauro/RADAR-backend) e [RADAR-frontend](https://github.com/mecassauro/RADAR-frontend).

![](https://i.imgur.com/NRbk35f.png)


No repositório [docs](https://github.com/mecassauro/docs) o Git Flow não será utilizado, desta forma, o pull request deverá ser feito diretamente na master.

## 4 - Política de aprovação do Código

Para que o "Pull Request" das funcionalidades seja devidamente aceito, esta deve estar seguindo os padrões de commit e estilo de código. Além disso, a <i>build</i> da Integração Contínua deverá estar "passando" para tal funcionalidade.

## 5 - Uso das Issues

As issues deverão conter <i>labels</i>, para que se possa identificar a sua natureza e elas deverão ser criadas a partir do template de [issue](https://github.com/mecassauro/RADAR-frontend/blob/master/.github/ISSUE_TEMPLATE/issue.md), [feature](https://github.com/mecassauro/RADAR-frontend/blob/master/.github/ISSUE_TEMPLATE/feature.md) ou [bug](https://github.com/mecassauro/RADAR-frontend/blob/master/.github/ISSUE_TEMPLATE/bug.md).

## 6 - Ferramentas 

| Ferramenta | Descrição |
|:----:|:---------:|
| Git | Ferramenta de versionamento |
| GitHub | Ferramenta de hospedagem de repositórios e controle de versão|
| React JS | Framework para a criação do frontend |
| Node | Tecnologia para criação do backend |
| Docker | Ferramenta de virtualização e configuração de ambiente por meio de containers|
| Docker Compose | Ferramenta de gerenciamento de containers Docker |
| Travis CI | Ferramenta de integração contínua|
| EsLint | Ferramenta de análise de código |
  