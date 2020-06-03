## Faça o Download das .ISO

[Ubuntu Server 18.04](https://google.com)

[Ubuntu Desktop 18.04](https://google.com)

[Windows 7 Professional](https://google.com)

## Edição da Documentação

Para editar o arquivo, você deve executar no **Ubuntu Desktop**:

> sudo nano /home/arquivos/server_ad/docs/(aula2, aula3, etc...)

Para acompanhar suas edições, você deve rodar o seguinte comando ***como root***:

> mkdocs serve

o link gerado será este `http://127.0.0.1:8000`. Lá você irá acompanhar suas edições. Tudo o que você fizer dentro de aula2.md e aula3.md será refletido por lá.

# Senhas

* Ubuntu server:
     * server login: guilherme
     * password: ********
    
* Ubuntu Desktop:
     * root: guilherme
     * password: ********

* Windows:
     * root: guilherme
     * password: ********

### Outros usuarios:

Estes usuários são os que devem ser utilizados para se autenticar o file Sharing pelo Windows, pois invalidamos o root, por segurança.

* No Ubuntu Desktop, usuário que NÃO é root: gilberto
* Password: ********

* No Ubuntu Server, usuário que NÃO é root: raul
* password: ********

# Como enviar para Produção?

Depois de terminar suas alterações, você deve rodar o comando:

> mkdocs gh-deploy

username: MrGui1100
password: ****************

Este comando irá gerar o HTML estático das paginas e fará automaticamente o commit para o gitHub Pages, que funciona como nosso servidor.





