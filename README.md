# Biblioteca
Sistema em Django de uma biblioteca. Onde o CRUD esta quase completo com CBV, E esta faltando implementar uma criação de API de consulta dos livros utilizando DRF e hospedar o sistema na plataforma Heroku.

Para colocar este projeto em execução localmente em seu computador:
Configure o ambiente de desenvolvimento Python para o Windows 10(Pesquise como configura o ambiente, sites como Alura, MDN Web Docs, e entre outros ajuda a configurar).

Execute os seguintes comandos:

<br>|para atualizar o banco de dados de forma adequada.|</br>
<br>`python3 manage.py makemigrations`</br>
<br>`python3 manage.py migrate`</br>
<br>`python3 manage.py createsuperuser`</br>
<br>|Cria um superUsuario(adicionando um username, email, e senha para entrar na parte de admin)|</br>
<br>`python3 manage.py runserver`</br>


<br>Abra um navegador http://127.0.0.1:8000/admin/ para abrir o site de administração </br>
<br>Crie alguns objetos de teste de cada tipo(se não tiver nenhum dados no banco).</br>
<br>Abra a aba para http://127.0.0.1:8000 ver o site principal.</br>

<br>Caso queira ver as Views do CRUD na Web de Autor ou Livro, acesse esses links abaixo, pois ainda não implementei no layout com botões para redirecionar até a página</br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/author/create/ para abrir o site de criação do autor</br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/author/10/update/ para abrir o site de atualização do autor(o ‘/10/’ é o id do autor que quer atualizar) </br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/author/10/delete/ para abrir o site de deletação do autor(o ‘/10/’ é o id do autor que quer deletar</br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/book/create/ para abrir o site de criação do livro</br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/book/1/update/ para abrir o site de atualização do livro(o ‘/1/’ é o id do livro que quer atualizar) </br>
<br>Abra um navegador http://127.0.0.1:8000/catalog/book/1/delete/ para abrir o site de deletação do livro(o ‘/1/’ é o id do livro que quer deletar</br>
