# Django Blog Project - Reis567

Portuguese version at the end

This is a blog project developed using Django. It allows users to create and publish blog posts, manage categories and tags, and display pages with custom content. The project follows the MVT (Model-View-Template) architectural pattern and incorporates various Django features and functionalities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Reis567/django-blog/
```

2. Create a virtual environment and activate it:

```bash
python -m venv myenv
source myenv/bin/activate
```

3. Install the project dependencies:

```bash
pip install -r requirements.txt
```

4. Run database migrations:

```bash
python manage.py migrate
```

5. Create a superuser account:

```bash
python manage.py createsuperuser
```

6. Start the development server:

```bash
python manage.py runserver
```

The blog project should now be up and running locally at `http://localhost:8000/`.

## Usage

1. Access the admin interface:

   - Open your web browser and go to `http://localhost:8000/admin/`.
   - Log in using the superuser credentials created during installation.

2. Manage blog content:

   - Create, edit, and delete blog posts.
   - Manage categories and tags.
   - Create custom pages with desired content.

3. View the blog:

   - Open your web browser and go to `http://localhost:8000/`.
   - Browse the published blog posts, search by keywords, filter by categories and tags, and view individual posts and pages.

## Project Structure

The project follows a standard Django project structure:

- `blog/`: The main Django application directory.
  - `admin.py`: Configuration for the Django admin interface.
  - `apps.py`: Configuration for the blog application.
  - `models.py`: Definition of database models (e.g., Post, Tag, Category, Page).
  - `urls.py`: URL routing configuration for the blog application.
  - `views.py`: View functions and classes that handle requests and generate responses.
- `blog_project/`: The project's configuration directory.
  - `settings.py`: Django project settings and configuration.
  - `urls.py`: Main URL routing configuration for the project.
- `static/`: Directory for static files (CSS, JavaScript, images).
- `templates/`: Directory for HTML templates used by the blog application.
- `utils/`: Directory for utility files and functions.
- `manage.py`: The Django project management script.

## Features

The blog project includes the following features:

- User authentication: Users can create accounts, log in, and log out.
- Blog post management: Users can create, edit, and delete blog posts.
- Category and tag management: Users can assign categories and tags to blog posts.
- Custom page creation: Users can create pages with custom content.
- Search functionality: Users can search for blog posts by keywords.
- Filtering by category and tags: Users can browse blog posts by category or tags.
- Pagination: Blog posts are displayed in pages with a specified number of posts per page.
- Django admin interface: Provides an interface for managing blog content.
- Responsive design: The blog is designed to be responsive and accessible across different devices.

## Dependencies

The blog project has the following dependencies:

- Django (version 3.2 or above)
- Django Summernote (for rich text editing functionality)
- Pillow (for image processing and handling)
- django-axes (for IP-based login throttling)
- psycopg2 (for PostgreSQL database support)

For more details on the dependencies and their versions, refer to the `requirements.txt` file.

## Contributing

Contributions to the blog project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the project's coding style and guidelines.

To contribute to the project, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Implement your changes.
4. Commit and push your changes to your forked repository.
5. Submit a pull request to the main repository.

Please provide a clear description of your changes in the pull request, along with any relevant information or context.

# Português


# Projeto Blog Django - Reis567

Este é um projeto de blog desenvolvido usando Django. Ele permite que os usuários criem e publiquem postagens de blog, gerenciem categorias e tags e exibam páginas com conteúdo personalizado. O projeto segue o padrão arquitetural MVT (Model-View-Template) e incorpora vários recursos e funcionalidades do Django.

## Índice

- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Recursos](#recursos)
- [Dependências](#dependências)
- [Contribuição](#contribuição)

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/Reis567/django-blog/
```

2. Crie um ambiente virtual e o ative:

```bash
python -m venv myenv
source myenv/bin/activate
```

3. Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

4. Execute as migrações do banco de dados:

```bash
python manage.py migrate
```

5. Crie uma conta de superusuário:

```bash
python manage.py createsuperuser
```

6. Inicie o servidor de desenvolvimento:

```bash
python manage.py runserver
```

O projeto de blog estará disponível localmente em `http://localhost:8000/`.

## Uso

1. Acesse a interface de administração:

   - Abra seu navegador da web e acesse `http://localhost:8000/admin/`.
   - Faça login usando as credenciais de superusuário criadas durante a instalação.

2. Gerencie o conteúdo do blog:

   - Crie, edite e exclua postagens de blog.
   - Gerencie categorias e tags.
   - Crie páginas personalizadas com conteúdo desejado.

3. Visualize o blog:

   - Abra seu navegador da web e acesse `http://localhost:8000/`.
   - Navegue pelas postagens de blog publicadas, pesquise por palavras-chave, filtre por categorias e tags e visualize postagens e páginas individuais.

## Estrutura do Projeto

O projeto segue a estrutura padrão de um projeto Django:

- `blog/`: O diretório principal do aplicativo Django.
  - `admin.py`: Configuração para a interface de administração do Django.
  - `apps.py`: Configuração para o aplicativo de blog.
  - `models.py`: Definição dos modelos de banco de dados (por exemplo, Post, Tag, Category, Page).
  - `urls.py`: Configuração de roteamento de URL para o aplicativo de blog.
  - `views.py`: Funções e classes de visualização que lidam com as solicitações e geram respostas.
- `blog_project/`: O diretório de configuração do projeto.
  - `settings.py`: Configurações e configuração do projeto Django.
  - `urls.py`: Configuração de roteamento de URL principal para o projeto.
- `static/`: Diretório para arquivos estáticos (CSS, JavaScript, imagens).
- `templates/`: Diretório para os templates HTML usados pelo aplicativo de blog.
- `utils/`: Diretório para arquivos e funções utilitárias.
- `manage.py`: Script de gerenciamento do projeto Django.

## Recursos

O projeto de blog inclui os seguintes recursos:

- Autenticação de usuários: Os usuários podem criar contas, fazer login e fazer logout.
- Gerenciamento de postagens de blog: Os usuários podem criar, editar e excluir postagens de blog.
- Gerenciamento de categorias e tags: Os usuários podem atribuir categorias e tags às postagens de blog.
- Criação de páginas personalizadas: Os usuários podem criar páginas com conteúdo personalizado.
- Funcionalidade de pesquisa: Os usuários podem pesquisar postagens de blog por palavras-chave.
- Filtragem por categoria e tags: Os usuários podem navegar pelas postagens de blog por categoria ou tags.
- Paginação: As postagens de blog são exibidas em páginas com um número especificado de postagens por página.
- Interface de administração do Django: Fornece uma interface para gerenciar o conteúdo do blog.
- Design responsivo: O blog é projetado para ser responsivo e acessível em diferentes dispositivos.

## Dependências

O projeto de blog possui as seguintes dependências:

- Django (versão 3.2 ou superior)
- Django Summernote (para funcionalidade de edição de texto rico)
- Pillow (para processamento e manipulação de imagens)
- django-axes (para limitação de login baseada em IP)
- psycopg2 (para suporte ao banco de dados PostgreSQL)

Para obter mais detalhes sobre as dependências e suas versões, consulte o arquivo `requirements.txt`.

## Contribuição

Contribuições para o projeto de blog são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, abra uma issue ou envie uma pull

 request. Certifique-se de seguir o estilo de codificação e as diretrizes do projeto.

Para contribuir com o projeto, siga estas etapas:

1. Fork o repositório no GitHub.
2. Crie um novo branch para sua funcionalidade ou correção de bug.
3. Implemente suas alterações.
4. Faça commit e envie suas alterações para o repositório forked.
5. Envie uma pull request para o repositório principal.

Forneça uma descrição clara de suas alterações na pull request, juntamente com qualquer informação ou contexto relevante.

Espero que este template ajude você a criar um README.md completo para o seu projeto de blog! Se precisar de mais assistência, não hesite em entrar em contato.
