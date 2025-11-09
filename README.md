# Django Girls Blog

Este projeto foi desenvolvido durante um minicurso do grupo **Django Girls**, uma iniciativa que incentiva mulheres a darem seus primeiros passos na programação e no framework **Django**.

Durante o tutorial, aprendemos os conceitos básicos de desenvolvimento web com Django e construímos um pequeno blog, onde é possível criar, editar e visualizar postagens através de uma interface simples.

---

## Objetivo do Projeto

O propósito deste projeto é colocar em prática os fundamentos do Django, entendendo como funciona o fluxo entre:
- **Models** (camada de dados)
- **Views** (lógica de negócio)
- **Templates** (interface do usuário)

Embora o tutorial seja voltado para iniciantes, foi uma ótima oportunidade de reforçar minha base e consolidar conhecimentos já adquiridos em Python e desenvolvimento web.

---

## Tecnologias Utilizadas

- **Python 3**
- **Django**
- **HTML / CSS**
- **SQLite (banco de dados padrão do Django)**

---

## Funcionalidades

- Criação de postagens
- Edição de postagens existentes
- Exibição de lista de posts
- Visualização individual de cada post
- Interface simples e intuitiva

---

## Como Executar o Projeto Localmente

Clone o repositório:
```bash
git clone https://github.com/lidiacard/django-girls-blog.git
cd django-girls-blog
```

Crie e ative um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
venv\Scripts\activate   # No Windows
source venv/bin/activate  # No Linux/Mac
```

Instale as dependências:
```bash
pip install -r requirements.txt
```

```bash
Execute as migrações:
python manage.py migrate
```

```bash
Inicie o servidor:
python manage.py runserver
```

```bash
Acesse o projeto no navegador em:
http://127.0.0.1:8000/
```


## 🌸 Sobre o Django Girls

O Django Girls é um projeto global que oferece workshops gratuitos para ajudar mulheres a entrarem no mundo da tecnologia.
Durante o evento, cada participante cria seu próprio blog usando Python e Django, aprendendo conceitos essenciais de forma prática e colaborativa.

Mais informações: https://djangogirls.org/