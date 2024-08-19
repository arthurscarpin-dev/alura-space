# ALURA SPACE
A photo gallery of the space developed in Django.

### Tech Stack:
<p align="left">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=python,django,sqlite"/>
    </a>
</p>

### Graphical interface:
![alura-space](https://github.com/user-attachments/assets/d28093a0-648e-4370-92ca-5ba98ea7beb6)

### How to run?
1. Clone the remote repository.
```
git clone 
```

### Como executar?
<div>
  <p>Para executar esse projeto é necessário apenas realizar o clone do repositório através do comando "git clone" ou realizar o download dos arquivos .zip através do GitHub, com o respositório baixado localmente o usuário deve seguir os seguintes passos:</p>
  <ol>
    <li>Criar e ativar o ambiente virtual usando o prompt de comando</li>
    <ul>
      <li>Executar o comando "python -m venv venv" para criar o ambiente virtual do Python.</li>
      <li>Executar o comando ".\venv\Scripts\Activate" se estiver usando o Windows ou "source venv/bin/activate" se tiver usando Linux ou Mac para ativar o ambiente virtual do Python.</li>
    </ul>
    <li>Instalar as bibliotecas que estão no arquivo "requirements.txt"</li>
    <ul>
      <li>Executar o comando "pip install -r requirements.txt" para instalar todas as dependências que são utilizadas nesse projeto.</li>
    </ul>
    <li>Realizar a migration do banco de dados SQLite</li>
      <ul>
        <li>Executar o comando "python manage.py migrate" para realizar a migration do banco de dados.</li>
      </ul>
    <li>Criar super usuário do admin do Django</li>
      <ul>
        <li>Executar o comando "python manage.py createsuperuser" para criar super usuário.</li>
        <li>Será solicitado o nome do usuário, e-mail, senha e confirmação da senha.</li>
      </ul>
    <li>E por fim, executar a aplicação Django</li>
      <ul>
        <li>Executar o comando "python manage.py runserver" para rodar a aplicação localmente.</li>
      </ul>
  </ol>
</div>
