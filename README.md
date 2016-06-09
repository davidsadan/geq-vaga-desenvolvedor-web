# Grupo Edson Queiroz

## Teste para candidatos à vaga de desenvolvedor web

# Projeto

Desenvolver uma aplicação de **Blog** utilizando o framework **Laravel**.

## Requisitos

### Back-end

#### CRUD de Usuários

Criar um gerenciamento aonde seja possível Criar, Listar, Editar e Visualizar um Usuário. 

Atributos de um Usuário são:

- nome
- email
- senha
- data de nascimento
- foto

#### CRUD de Posts

Criar um gerenciamento aonde seja possível Criar, Listar, Editar e Visualizar um Post.

Atributos de um Post são:

- titulo
- conteúdo
- imagem
- autor ( Deve ser um usuário )
- data de publicação

#### Autenticação

- Restringir o acesso ao back-end através de sistema de autenticação.

#### Front-end

#### Home

- A listagem dos post deve ser realizado na página inicial, com páginação, trazendo os posts mais recentes primeiro.
- A exibição do post na lista deve conter apenas o titulo, imagem, e resumo com no máximo 200 caracteres e o link para a página do single do post.

#### Detalhes do Post

- Na página de detalhes do post, deve conter a imagem do post, conteúdo completo e nome do autor.


# Instruções:

- Deve ser utilizado o **Laravel** como framework.
- As tabelas do banco de dados devem ser criadas através de migrations.
- Deve ser criado um seeder para alimentar a aplicação com dados de teste.
- Deve ser utilizado o **Composer** para gerenciar as dependências da aplicação.
- Deve ser utilizado o **Bower** para gerenciar as dependência de front-end.
- Não é permitido utilizar *Yeoman* para gerar o scaffolding da aplicação.
- Criar um README com orientações para a instalação.

# Esperamos que você:

- Minifique seu css e deixe-o na pasta "css"
- Minifique seu javascript e deixe-o na pasta "js";
- Faça commit também dos arquivos não minificados;

# Fique livre para:

- Escolher o tema para o blog e interface adminitrativa.

# Ganhe pontos extras por:

- Utilizar o estilo de código definido na PSR-2;
- Desenvolver HTML semântico para o Front-end;
- Utilizar boas práticas de SEO;

# O que será avaliado

- Se o código é limpo, organizado e comentado;
- Se o código segue os conceitos do S.O.L.I.D;
- Uso de Design Patterns;
- O funcionamento da aplicação;

## Publicação

- O projeto final deve ser publicado em sua conta do Github. E o link deve ser enviado para **anderson.andrade@geq.com.br**