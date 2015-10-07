# Exportações

## Updates (hook_update_N)
- Funcionamento
- Cuidados
  - Podem quebrar a montagem do ambiente
  - Inserir o drupal_set_installed_schema_version para iniciar o updb
    - Mindset que todos os updates irão ser executados

## Configuration Management
- Funcionamento
- Cuidados
 - Avisar o time sobre o envio de atualizações
 - Alterando ou removendo fields
 - Desabilitando modulos
 - Uso do drush clsyn
 - Não trackear o tracked.inc
 - Não trackear variáveis
 - Variants (Page Manager Handler)
 - Permissões
 
## Features
- Funcionamento
- Cuidados
 - Exportando
 - Revertendo as features
 - Boa escrita nos nomes
 - Usar elas como modulos ou submodulos
 
## Manifests
- Funcionamento
- Cuidados
  - Erro de duplicação de informação
  - Excesso de codigo pode demorar a execução
  - Preocupar com dependências
  - Updb ocorre antes do manifest (drush kw-u)
