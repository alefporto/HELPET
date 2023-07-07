# :checkered_flag: HELPET

Helpet é uma Aplicação Web destinada a facilitar a adoção de animais de rua e arrecadação de fundos através de doações de uma forma fácil e rápida.

## :technologist: Membros da equipe

<ul>
    <li>João Álef Porto Bevilaqua | 548322 | Engenharia de Software
    <li>Wendel Rodrigues Viana    | 548323 | Engenharia de Software
</ul>

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

<ul>
    <li>Admin (Administrador)
    <li>Logado (Usuário que fez login)
    <li>Public (Usuário que não fez login)
</ul>

## :spiral_calendar: Entidades ou tabelas do sistema

<ul>
    <li>User
    <li>Pet
    <li>Anuncio
    <li>Pedido
    <li>Feedback
</ul>

## :triangular_flag_on_post: Principais funcionalidades da aplicação

<ul>
    <li>Admins poderão, criar, editar e deletar anúncios próprios e deletar anúncios de outros usuários.
    <li>Usuários logado poderá publicar anúncios, adotar pets, comentar em anúncios já existentes e realizar doações.
    <li>Usuários não logados, poderão, somente, ver os anúncios existentes e seus comentários.
</ul>

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:** 
VueJS. CSS3. HTML5.

**Backend:**
NodeJS. Strapi. JavaScript.

## :shipit: Operações implementadas para cada entidade da aplicação

| Entidade | Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| User | X | X | X |  |
| Pet | X | X | X | X |
| Anuncio | X | X | X | X |
| Pedido | X | X | X | X |
| Feedback | X | X | X | X |

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
