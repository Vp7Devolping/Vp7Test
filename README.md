# PROJETO TIC

## O que temos a fazer
- [ ] Sistema de login / Users 
- [ ] Horário/adicionar eventos (testes, falta de professores, etc...)
- [ ] Trabalhos a fazer
- [ ] Alertas
- [ ] Contactos
- [ ] Lista da turma
- [ ] Tornar a aplicação dinamica (html, etc...)

## Sistema de login
- 3 tipos de usuários: Delegados, DT, Alunos.

| Permissões          | Delegados | DT | Alunos |
|---------------------|-----------|----|--------|
| Adicionar alertas   |     X     |  X |        |
| Adicionar eventos   |     X     |  X |        |
| Adicionar trabalhos |     X     |  X |        |
| Visualizar contactos|     X     |  X |    X   |
| Visualizar turma    |     X     |  X |    X   |
| Receber alertas     |     X     |  X |    X   |
| Visualizar trabalhos|     X     |  X |    X   |
| Visualizar horário  |     X     |  X |    X   |

## Horário
- O horário vai ser visivel na página principal, onde todos os usuários podem ver.
- No horário vão haver bolinhas com varias cores, cada cor tem um significado (insira o curso em cima da bolinha).
>Vermelho: Vai faltar algum professor

>Azul: Indicar dia de algum teste/Entrega de projeto

>Amarelo: Feriado/Interrupeção

>roxo: Férias
- Estes eventos podem ser adicionados pelos Delegados, e pela DT.

## Alertas
- Os alertas vão ser utilizados para alertar todos os users, quando for adicionado: trabalhos e eventos.
- Os alertas vão ser enviados por: Email, Discord da Turma:
> EMAIL: Os emails vão ser enviados por um email criado so para a turma;

> DISCORD: Os avisos no Discord vão ser feitos através de um BOT;

## Contactos
- Os contactos que vão estar expostos para todos os users, vão ser os dos Delegados e o da DT.
- Existe um botão que ao clicar envia uma mensagem para o WhatsApp :
> API: https://api.whatsapp.com/send?phone=seunumerodetelefone&text=sua%20mensagem

## Lista da Turma
- A lista da turma, é uma lista com todos os membros, e nessa lista, vai estar indicado o membro, com número, número de cartão, aniversário (idade), email.

## Tornar a plataforma dinamica
- Nos queremos aceder a plataforma por todos os meios possiveis: Computador, telemovel, tablet, etc... Então vamos a visualização da plataforma e a sua utilização vai se adaptar dependendo do dispositivo.
