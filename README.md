# Biblioteca
Sistema em Django de uma biblioteca. Onde o CRUD esta quase completo com CBV, E esta faltando implementar uma criação de API de consulta dos livros utilizando DRF e hospedar o sistema na plataforma Heroku.

Para colocar este projeto em execução localmente em seu computador:
Configure o ambiente de desenvolvimento Python para o Windows 10.


Para verificar se o Python 3 foi instalado, digite o seguinte texto no prompt de comando:
`py -3 -V`
  `Python 3.8.6`
Assim, vera se foi instalado


Execute os seguintes comandos(se você estiver no Windows, pode usar py ou em py -3 vez de python para iniciar o Python):


`python3 manage.py makemigrations`
`python3 manage.py migrate`
`python3 manage.py createsuperuser`
| Cria um superUsuario(adicionando um username, email, e senha para entrar na parte de admin) |
`python3 manage.py runserver`


Abra um navegador http://127.0.0.1:8000/admin/ para abrir o site de administração
Crie alguns objetos de teste de cada tipo(se não tiver nenhum dados no banco).
Abra a aba para http://127.0.0.1:8000 ver o site principal.
