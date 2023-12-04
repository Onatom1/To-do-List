# Django Todo List

## Configuração do Ambiente Virtual



1. Navegue até o diretório desejado utilizando o comando cd caminho/do/diretorio.

2. Crie o ambiente virtual com o seguinte comando: python -m venv venv
   ou, se preferir, pode especificar um nome para o ambiente: python -m venv nome_do_ambiente

3. Ative o ambiente virtual:
   No Windows: venv\Scripts\activate

4. Instale as dependências necessárias utilizando o comando: pip install -r requirements.txt

5. Gere o banco de dados SQLite vazio e as tabelas com os seguintes comandos: python manage.py makemigrations e python manage.py migrate
  
6. Execute o aplicativo utilizando o comando: python manage.py runserver



Agora, seu ambiente virtual estará configurado, as dependências instaladas, o banco de dados SQLite criado e as tabelas geradas. O aplicativo estará em execução, pronto para ser acessado no navegador.
Lembre-se de adaptar os comandos conforme necessário, dependendo do sistema operacional que você está usando.
