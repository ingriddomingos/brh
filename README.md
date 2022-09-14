# Sistema BRH 
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)


Projeto em desenvolvimento para o treinamento Level Up Alura: BRH

# Sobre o projeto
O sistema BRH é um sistema de gestão de recursos humanos, seu objetivo é permitir a gestão dos colaboradores e departamentos da empresa.
Para exemplificação do projeto, os conceitos de entidade, procedures e funções são inicialmente da empresa ficticia denominada Comex.

A empresa é divida em departamentos, cada um chefiado por um colaborador. Os departamentos são identificados pela sigla que é atribuída em sua criação.

Os colaboradores, quando contratados, são sujeitos ao cadastro contendo nome, cpf, telefones, dependentes (caso possua), endereço, email e salário. Eles são alocados num departamento e são identificados pela matrícula que recebe ao ser contratado.

A empresa é uma organização projetizada, ou seja, os colaboradores fazem parte de projetos com data para iniciar e terminar, podendo os mais capacitados fazerem parte de mais de um projeto ao mesmo tempo.

Para favorecer as boas práticas de Gestão 3.0, o chefe do departamento delega a responsabilidade de liderar de cada projeto ao colaborador mais indicado.

Cada colaborador tem um papel definido em um determinado projeto (desenvolvedor, engenheiro de infraestrutura, administrador de banco de dados, etc) e cada colaborador pode exercer papéis diferentes em cada projeto e o mesmo papel, desde que em projeto diferentes.

# Sobre o treinamento
O projeto vem caminhando por etapas, desde a criação do modelo conceitual à criação do banco de dados.

O primeiro passo para a criação do projeto foi realizar o modelo conceitual. Posterirmente foi criado o modelo relacional, já normalizado, ambos na plataforma BrModelo.
Realizado o modelo relacional com as entidades/tabelas  com todas as chaves primárias, campos e etc já estabelecidas, foi iniciado um teste de criação de schema na plataforma MySqlWorkbench.

O SGBD disponibilizado pelo curso para dar andamento com o projeto, foi o oracle sql developer. Nele criamos o schema já ajustado e damos andamento nesse SGBD até então. 

Para a criação do banco para a empresa Comex, foi necessário a criação do schema com as seguintes tabelas: brh.papel, brh.departamento, brh.endereco, brh.colaborador, brh.telefone_colaborador, brh.dependente, brh.projeto e brh.atribuicao


Para a criar o mesmo schema rode o arquivo em algum sgbd:


```
schema.sql
```

# Autora

[<img src="![image](https://user-images.githubusercontent.com/113357688/190251992-ad7f6bbf-2998-4d22-9440-7faf7e1f0f91.jpg))" width=115><br><sub>Ingrid Domingos Antuness</sub>](https://github.com/ingriddomingos) 

