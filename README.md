Módulo 15
=================

Após iniciar os estudos sobre DevOps, CI-CD, Docker e conhecer ferramentas que possibilitam a implementação da integração contínua no dia a dia do desenvolvimento de software, como atividade da formação em Engenheiro de Qualidade de Software da [EBAC (Escola Britânica de Artes Criativas e Tecnologia)](https://ebac.art.br/), fui capaz de criar esteiras de testes em pipelines do Jenkins para rodar os testes desenvolvidos nos módulos 11, 12 e 14.

Como estratégia para criar e executar a esteira:
------------------------------------------------

- Instalei uma imagem oficial do Jenkins via Docker
- Instalei as dependências relacionadas ao Nodejs, Cypress e NPM
- Configurei o pipeline para uso com "script from scm"
- Criei o Jenkinsfile nos respectivos repositórios e executei as esteiras

Para visualizar o trabalho desenvolvido acesse:
------------------------------------------------

- [Repositório módulo 11](https://github.com/leicam1995/teste-ebac-ui.git)
- [Repositório módulo 12](https://github.com/leicam1995/teste-e2e-ebac.git)
- [Repositório módulo 14](https://github.com/leicam1995/teste-api-ebac.git)
