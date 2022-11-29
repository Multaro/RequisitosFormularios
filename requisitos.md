# LEVANTAMENTO DE REQUISITOS

O processo de levantamento de requisitos é uma etapa crítica no processo de engenharia de software e influencia as fases anteriores e posteriores, como garantia de qualidade e teste de software. O primeiro passo é identificar as partes interessadas (_stackholders_) e estabelecer canais de comunicação eficazes que devem ser mantidos durante todo o Ciclo de Vida de Desenvolvimento de Software.

As partes envolvidas neste levantamento são representadas pelo Comandante da Guarda Civil Municipal e principalmente pelos Ceconistas, sendo estes responsáveis pela operação do sistema.

## 1 Requisitos Funcionais

- O sistema deve gerar cadastros para cada tipo de documento existente, incluindo Delocamento de Viaturas, Auto de Infraçes e Ocorrências.

- O sistema deve assegurar que todas as informações incluídas em cada documento estejam presentes nos cadastros.

- O sistema deve possibilitar a exclusão dos formulários por parte do usuário.

- O sistema deve possibilitar a alteração dos formulários por parte do usuário.

- O sistema deve validar os dados cadastrados.

- O sistema deve garantir a padronização dos dados cadastrados.

- O sistema deve fornecer opção de backup dos dados cadastrados.

- O sistema deve adotar um sistema de banco de dados.


## 2 Requisitos Não-Funcionais

### 2.1 Disponibilidade

É necessário garantir a disponibilidade do sistema, uma vez que o usuário principal desta aplicação interage com o sistema de forma interrupta, já que a função do Ceconista é realizada continuamente.

É igualmente necessário assegurar que os dados não sejam perdidos devido à sua importância.


### 2.2 Segurança

Por lidar com dados importantes, é fundamental que o sistema esteja o menos exposto possível a usuários que não participam da segurança pública, além de vetar quaisquer tentativas de invasão. 

Como resultado, uma arquitetura sem distribuição da camada de interface foi aplicada ao sistema.


### Referências

MORAES, Janaína. Introdução à Abordagens de Identificação de Requisitos. **Engenharia de Software Magazine**: Rio de Janeiro, n. 2, p. 54-48, 200