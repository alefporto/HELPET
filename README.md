# :checkered_flag: HELPET

Helpet é uma Aplicação Web destinada a facilitar a adoção de animais de rua e arrecadação de fundos através de doações e venda de produtos de uma maneira simples 
e rápida.

## :technologist: Membros da equipe

548323 |   Wendel Rodrigues Viana  | Engenharia de Software
548322 | João Álef Porto Bevilaqua | Engenharia de Software

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Usuário não registrado.
Usuário registrado.
Administrador

## :spiral_calendar: Entidades ou tabelas do sistema

Animais
Usuário
Comentário

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

Usuários não registrados poderão, somente, ver os animais e os comentários feitos por usuários registrados.
Usuários registrados, além do que os não registrados já fazem, poderão postar novos animais e comentários nas postagens de outros.
Administradores poderão deletar e editar publicações.

## :desktop_computer: Tecnologias e frameworks utilizados

Frontend: VueJS v3.0, Vue-Router e Pinia.
Axios

Backend: Strapi

## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Animais | X | X | X | X |
| Usuários | X |  |  |  |
| Comentários | X | X |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
