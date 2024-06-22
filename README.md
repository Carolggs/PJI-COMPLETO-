"TrabalhoPJI_Carolina_LucasL.zip" possui todos os arquivos de código do projeto e "MeetTalk.sql" é o arquivo do banco de dados 

Documento de especificação de requisitos:

O objetivo do software é colocar as pessoas em contato de forma prática e rápida,  para isso ele irá disponibilizar ferramentas que ajudem nesse processo. As principais ferramentas são o “Match Perfeito” (Match pode significar par, partida, correspondência etc) que aparecerá diariamente e mostrará alguém compatível com o usuário,  e o sistema de busca de outras pessoas com base nas características que o usuário escolher além do chat, onde os usuários poderão conversar. 

Escopo

MeetTalk (Meet é conhecer em inglês e Talk é falar em inglês).
O software vai possibilitar que o usuário encontre pessoas com os mesmos interesses, a ele de forma automática ou que ele possa escolher pessoas com quem quer conversar, com base nas  características que ele procura. Isso fará com que as pessoas consigam se encontrar de um modo mais rápido e fácil. 
Os usuários do sistema poderão realizar cadastro, pesquisar outros usuários que gostariam de conversar, iniciar conversas e apagá-las, seguir uns aos outros e deixar de seguir. Além disso, poderão escrever mensagens diárias, podendo alterá-las caso necessário.





Requisitos Funcionais

RF001 - Cadastrar usuários 
Descrição: Cadastrar usuário com os campos “email” e “senha”. Além disso, o usuário deverá preencher o perfil com seus dados, são eles: gênero, esporte favorito, estilo musical favorito, país, maior qualidade, maior defeito, gênero literário favorito, gênero favorito de filme, religião, status de relacionamento e sexualidade, além de idade (para maiores de 14 anos). Futuramente esses dados poderão ser atualizados.
Classificação: Obrigatório


RF002 - Realizar Login 
Descrição: O usuário deverá preencher o campo email e senha para realizar o login.
Classificação: Obrigatório

RF003 - Conferir idade do usuário 
Descrição: Se o usuário for menor de 14 anos, não poderá finalizar o cadastro e o sistema emitirá um alerta avisando. 
Classificação: Desejável

RF005 - Preencher perfil de usuário com uma foto de perfil
Descrição: O usuário deverá adicionar uma foto de perfil que poderá ser alterada.
Classificação: Obrigatório

RF006 - Preencher perfil de usuário com um nome de usuário
Descrição: O usuário deverá colocar um nome de usuário que poderá ser alterado.
Classificação: Obrigatório

RF007 - Mensagens Diárias
Descrição: O usuário poderá escrever uma mensagem que ficará exposta no seu perfil durante 24 horas. Essa mensagem poderá ser alterada.
Classificação: Opcional

RF008 - Acesso às mensagens diárias
Descrição: O usuário só  poderá visualizar as mensagens diárias de outro usuário se clicar no perfil.
Classificação: Opcional

RF009 - Mostrar o Match do dia
Descrição: Todo dia o site vai mostrar para o usuário um novo usuário que bate com as características dele (Match Perfeito).
Classificação: Obrigatório

RF010 - Aceitar sugestão ou Negar sugestão do Match do dia
Descrição: Após receber o “Match Perfeito”, o usuário poderá aceitar a sugestão e iniciar a conversa ou negar a sugestão e não iniciar a conversa.
Classificação: Obrigatório

RF011- Enviar mensagem de aviso caso não tenha um match diário
Descrição: Caso o sistema não encontre um “Match perfeito”, ele enviará uma mensagem dizendo que não houve o match do dia.
Classificação: Obrigatório

RF012 - Pesquisa de usuários
Descrição: O usuário poderá pesquisar outros usuários com base nas características que ele escolher (idade, gênero, esporte favorito, estilo musical favorito, país, estado, maior qualidade, maior defeito, gênero literário favorito, gênero favorito de filme, religião, status de relacionamento, hobby e sexualidade).
Classificação: Obrigatório

RF013 - Sistema de Chat
Descrição: O usuário poderá se comunicar com outros usuários do site através de um chat.
Classificação: Obrigatório

RF014 - Adicionar usuário como “amigo”
Descrição: Os usuários poderão fazer amizades com outros usuários através de um sistema de seguidores, onde eles poderão seguir-se e acompanhar-se.
Classificação: Obrigatório


RF015 - Desfazer “amizade” com usuário
Descrição: Os usuários poderão desfazer amizades com outros usuários e deixá-los de seguir.
Classificação: Obrigatório



RF017 - Realizar Logout  
Descrição: O usuário poderá realizar o logout ao apertar um botão na interface.
Classificação: Obrigatório

Requisitos de Interface
RI001 - Página de login
Descrição: A página de login será a primeira tela do site e terá dois campos para login (email e senha).
Classificação: Obrigatório

RI002 - Página de cadastro
Descrição: Supondo que o usuário não tenha uma conta no site, ele poderá realizar o cadastro  que terá dois campos para login (email e senha) e também deverá preencher os outros dados ( idade (maiores de 16 anos), gênero, esporte favorito, estilo musical favorito, país, estado, maior qualidade, maior defeito, gênero literário favorito, gênero favorito de filme, religião, status de relacionamento e sexualidade).
Classificação: Obrigatório

RI003 - Página Inicial
Descrição: A página inicial conterá o match diário do usuário, além de uma barra de pesquisas onde será possível que os usuários pesquisem por características de outros usuários.
Classificação: Obrigatório

RI004 - Página de Perfil próprio 
Descrição: A página de perfil próprio conterá o perfil do usuário que está logado no site, bem como suas características, foto de perfil, bio e a frase do dia.
Classificação: Obrigatório

RI005 - Perfil de outros usuários 
Descrição: Após a pessoa utilizar a barra de pesquisa para encontrar pessoas, ao selecionar a pessoa que ela está interessada, aparecerá o perfil delas
Classificação: Obrigatório.

RI006 - Sistemas de Chats
Descrição: A página deverá conter o sistema de Chat quando um usuário quiser se comunicar com outro, no match diário ou com outros usuários
Classificação: Obrigatório.

Requisitos Não Funcionais (Qualidade)

RN001 - Plataforma
Descrição: O sistema software será em plataforma web.
Classificação: Obrigatório.

RN002 - Linguagem de programação
Descrição: PHP
Classificação: Obrigatório.

RN003 -Facilidade de uso
Descrição: O sistema deverá ser fácil de usar.
Classificação:Desejável
RN004 - Interface amigável
Descrição: A interface deve ser visualmente amigável aos seus usuários.
Classificação: Obrigatório.

Restrições
RT001 - Idade mínima
Descrição: Para realizar o cadastro e usar o site os usuários devem ser maiores de 14 anos
Classificação: Obrigatório.
Referências:



