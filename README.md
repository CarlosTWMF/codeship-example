# Integração Contínua com CodeShip - Projeto Integrador

[ ![Codeship Status for CarlosTWMF/codeship-example](https://codeship.com/projects/980399d0-e2d3-0132-6180-0e8782f5ebb8/status?branch=master)](https://codeship.com/projects/81568)

Da instalação à construção
===========

GitHub
---------

01 - O primeiro passo é instalar e configurar o Git:
* $ sudo aptitude install git-core
* $ git config -- global user.name "Seu Nome"
* $ git config -- global user.email "seu@email.com"




02 - Gerando uma nova chave SSH:
* $ ssh-keygen -t rsa -b 4096 -C "seu@email.com"




03 - Utilize a configuração padrão quando for questionado um arquivo para salvar a chave, simplesmente pressionando Enter para continuar:
* Enter file in which to save the key (/Users/you/.ssh/id_rsa): [Pressione Enter]




04 - Defina uma frase de segurança para as operações no repositório.




05 - Adicione a chave ao seu agente SSH:
* $ ssh-add ~/.ssh/id_rsa




[06 - Associe a sua chave SSH à sua conta no GitHub](https://help.github.com/articles/generating-ssh-keys/#step-4-add-your-ssh-key-to-your-account)




07 - Teste a conexão:
* $ ssh -T git@github.com
* Digite "yes"




CodeShip
---------
01 - Autentique-se no CodeShip utilizando a sua conta do GitHub




02 - Conecte-se ao GitHub




03 - Crie o seu primeiro projeto




04 - Informe a plataforma da sua aplicação




04 - Informe as configurações de comandos, deploy, testes, ambiente. Para mais detalhes [acesse a documentação do CodeShip](https://codeship.com/documentation)




[04 - Exiba o status de Build do CodeShip no seu projeto do GitHub](https://codeship.com/documentation/faq/codeship-badge/)




05 - Seu projeto já está pronto para ser acompanhado. Siga as instruções a seguir para enviar os arquivos para o GitHub. Assim que você mandar os arquivos para o seu repositório já poderá visualizar o CodeShip trabalhando =)




Enviando o projeto para o GitHub e acompanhando o Build
---------
01 - Veja quais o status do seu repositório:
* $ git status




02 - Adicione os arquivos ao projeto:
* $ git add .




03 - Informe quais as alterações você está realizando:
* $ git commit -m "Mensagem de Informação do commit"




04 - Envie as alterações do seu projeto para o seu repositório no GitHub:
* $ git push origin master




05 - Observe o CodeShip funcionar =)



Fontes
---------
[GitHub](https://help.github.com/articles/generating-ssh-keys/#step-4-add-your-ssh-key-to-your-account)
[CodeShip](https://codeship.com)
[Exemplo](http://code.tutsplus.com/tutorials/codeship-continuous-integration-and-delivery-made-simple--cms-23517)
[Exemplo](https://github.com/tidoust/codeship)

