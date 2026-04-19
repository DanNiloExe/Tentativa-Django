Passos Seguidos

Criação do ambiente virtual:
  python -m venv .venv
    .venv\Scripts\activate
      .venv\Scripts\activate

Django e projeto
  pip install django
    django-admin startproject flashpoint
      cd flashpoint
        python manage.py runserver
  Resultado: "April 18, 2026 - 21:43:09
Django version 6.0.4, using settings 'flashpoint.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK."


Vincular VsCode ao GitHub para upar o código (não consegui de outro jeito)

*Instalar o Git
Criar o .gitignore para garantir o não envio dos arquivos confidenciais

Iniciar o e adicionar arquivos ao repositorio local
  git init
    git add .

Criar o primeiro commit:
    git commit -m "Initial commit - Django Server"
      git branch -M main

Linkar o repoisotio no github
  git remote add origin https://](https://github.com/DanNiloExe/Tentativa-Django
    git push -u origin main
