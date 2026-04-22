# academia
Este projeto implementa um sistema de gerenciamento de academia em Python, utilizando conceitos de Programação Orientada a Objetos (POO). O sistema permite o cadastro de planos, alunos e funcionários, além do registro de entrada e saída de alunos na academia. Ele gerencia o status de acesso dos alunos (ativo/inativo, plano vencido) e oferece um menu interativo para diversas operações.
Classes Principais:
•	Pessoa: Classe base para entidades com nome, ID e idade.
•	Usuario: Herda de ‘Pessoa’, adicionando credenciais de login e email.
•	Aluno: Herda de ‘Usuario’, gerenciando planos, status de atividade e vencimento do plano.
•	CLT: Classe para informações de salário de funcionários.
•	Funcionario: Herda de ‘Pessoa’ e ‘CLT’, adicionando cargo.
•	Plano: Representa um plano de academia com nome, valor e duração.
•	Acesso: Registra os eventos de entrada e saída dos alunos.
Funcionalidades:
•	Cadastrar e listar planos de academia.
•	Cadastrar e listar alunos, associando-os a um plano.
•	Cadastrar e listar funcionários.
•	Registrar entrada e saída de alunos, com verificação de acesso (plano ativo, não vencido).
•	Listar todos os acessos registrados.
•	Listar alunos ativos.
Como Executar o Sistema
1.	Pré-requisitos: Certifique-se de ter o Python 3.x instalado em sua máquina.
2.	Clonar o Repositório (se aplicável):
Git clone https://github.com/fabriciodansi-maker/Python.git
3.	Executar o Script: Execute o arquivo principal do projeto.
 ```bash
python main.py
```
(Nota: No ambiente Colab, basta executar a célula de código que contém a função “menu()”)
4.	Interagir com o Menu: Siga as instruções do menu interativo no console para realizar as operações desejadas (cadastrar planos, alunos, etc.).
O que achamos mais desafiador na transição para o Python
O mais desafiador na transição para o Python foi se adaptar à forma como a linguagem organiza o código, principalmente a indentação, já que diferente de outras linguagens, ela faz parte da estrutura do programa.
Outro ponto foi entender melhor o uso do self nas classes, que no início causa certa confusão para quem vem de linguagens como C ou Java. Além disso, o fato de Python não exigir tipagem obrigatória exige mais atenção para evitar erros durante a execução.
Por outro lado, percebemos que o Python é uma linguagem mais simples e direta, o que facilitou bastante o desenvolvimento. Recursos como dataclasses, listas e tratamento de exceções ajudaram a manter o código organizado e fácil de entender.
