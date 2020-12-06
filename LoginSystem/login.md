# Login

## Para dar Login

- precisamos de 2 informações

>Nº do cartão da escola

>Password

## informação que precisamos para criar user

- **1. nº cartão**
- **2. nome**
- **3. apelido** 
- **4. idade** 
- **5. email** 
- **6. password** 
- **7. número** 
- **8. nivel**

## Base de dados

**1. Tabela: user**

- número do cartão (id) [INT 5]
- nome do aluno [TEXT 15]
- apelido do aluno [TEXT 25]
- idade [INT 2]
- email [TEXT 80]
- Password [TEXT 50]
- número Turma [INT 2]
- nivel [INT 1]

- comandos:
CREAT TABLE IF NOT EXISTS 'user'(
    'id' INT(5),
    'nome' TEXT(15),
    'apelido' TEXT(25),
    'idade' INT(2),
    'email' TEXT(50),
    'password' TEXT(50),
    'nivel' INT(1),
    'numero' INT(2),
PRIMARY KEY ('id'),
UNIQUE KEY 'email' ('email'),
KEY 'nivel' ('nivel')
)


**2. Tabela: Calendario**
    
**3. Tabela: Turma**


## Para fazer o sistema de login 

1.Temos de aceder a base de dados ()
