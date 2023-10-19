# terraform-learn
Repositório para estudos relacionados ao terraform usando o EC2 da Amazon

### O que é o Terraform? 
Terraform é uma ferramenta para provisionamento de infraestrutura como código, com o terraform podemos padronizar essa criação e pular algumas etapas, tambem fizemos o uso do ansible que permite uma flexibilidade maior na hora de criar a infraestrutura.

### O que é o Ansible 
O Ansible é uma poderosa ferramenta de automação de TI e gerenciamento de configuração que permite automatizar tarefas repetitivas e complexas de implantação, gerenciamento e manutenção de sistemas e infraestrutura, os arquivos do ansyble são do tipo yml,
o hosts.yml está fazendo a função de "conectar" na maquina usando o ipv4 publico, e no playbook.yml a gente coloca as tarefas que queremos que o ansible execute, para executar precisamos escrever um código no terminal.

**ansible-playbook playbook.yml -u ubuntu --private-key IaC-alura.pem -i hosts.yml**



