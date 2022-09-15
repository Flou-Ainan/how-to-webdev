# Manual How-to-webdev por Flou Ainan

  

Estou montando aqui um caminho de produção webdev que será alterado ao longo do tempo de acordo com meu conhecimento.

  

Este documento é apenas um repositório de conhecimento pessoal sobre webdev que desejo altrerar ao longo do tempo com o sistema de versionamento do Git

  

---------------

  

# Como eu estudo webdev

  

Na minha humilde sabedoria atual que ainda se encontra defasada e um tanto quanto confusa com a quantidade de tecnologias que existem no meio WebDev.

  

Tendo construir nhecimento acerca dessa área com a seguinte técnica baseada em 3 passos e alguns conceitos.

  

Passo 1:

Analisar bem o processo inteiro e tentar colher os tópicos chave

Geralmente assisto/ouço alguem que ja trabalha com o processo completo e tento colher as informações que vão me ajudar a entender o processo todo. Aquelas navegadas pela internet com 72 abas abertas também ocorrem nesta etapa hahaha.

  

Passo 2:

Estudar e praticar tópicos importantes do processo via cursos, exercícios, desafios, leituras, etc.

  

Passo 3:

Tentar executar uma fatia do processo completo, neste contexto o objetivo é se por a prova e se desafiar fazer todo o processo de forma simplficada para entender o mecanismo conjunto e enfrentar os desafios que veem com a prática completa. (diferenciada da prática de tópicos)

  

Passo "4":

Repito a sequencia de passos novamente. sempre me aprofundando ou abrangendo mais onde é necessario.

  

Os conceitos por tras desse sistema têm o objetivo de otimizar o aprendizado das coisas mais importantes da forma mais rápida possível, e pelo menos assim tem funcionado pra mim.

  
  

# Como eu entendo o sistema de forma resumida

A **World Wide Web** pode ser definida como um sistema de documentos em hipermídia que são interligados e executados via Internet.

Num cenário padrão, reconhecemos dois polos nesta rede. O lado cliente e o lado servidor.

  

Para acessar essa informação interligada e distribuída como um cliente é necessário utilizar um dispositivo que implemente algum Navegador Web como o Google Chrome, Safari, Edge, Firefox, Opera, entre outros.

  

Este Programa (O Navegador) então roda no lado cliente e é responsável por diversas tarefas. Dentre elas:

  

- Processar e Representar os variados tipos de dados recebidos de um servidor

- Gerenciar os protocolos e conexões com os Servidores

- Oferecer facilidade e usabilidade aos usuários da Web

- Oferecer um sub-sitema operacional capaz de rodar as aplicações web e interagir com o sistema operacional da máquina

  

Para um usuário ou **cliente** acessar algum conteúdo existente na Web ele vai precisar primeiro de um dispositivo com um navegador instalado. Em seguida ele precisará usar este navegador para acessar um endereço na Web...

Toda esta etapa de ligar o endereço digitado ao lado servidor é feito através de uma cadeia sistemica bem complexa envolvendo as companhias distribuidoras de internet e convenções definidas por grandes grupos que regulamentam a web.

  

Resumindo o padrão:

A forma usual de se conectar com um website é acessa-lo atraves do protocolo [HTTP](https://pt.wikipedia.org/wiki/Hypertext_Transfer_Protocol) e utilizar o padrão de nomes [DNS](https://pt.wikipedia.org/wiki/Sistema_de_Nomes_de_Dom%C3%ADnio)...

Quando esse [handshake](https://www.cloudflare.com/pt-br/learning/ssl/what-happens-in-a-tls-handshake/) é executado, formaliza-se uma conexão do **cliente** com o **servidor**.

O lado **Servidor** é responsável por lidar com os acessos dos clientes, distribuir conteúdo aos clientes, atualizar informações em bancos de dados, manter o website no ar, executar códigos e devolver um resultado ao usuário, dentre outras responsabilidades.

Antes de falar sobre as responsabilidades do lado cliente á necessário se entender um poco de como esse sitema é dividido.

O lado cliente não é só o terminal onde as informações do servidor são cospidas ao usuário (como eram nos anos 90), o lado cliente é essencialmente tudo que acontece dentro do navegador que recebe uma variedade de tipos de dados dos servidores e até mesmo aplicações completas que vão rodar neste sub-sistema operacional que existe dentro do seu navegador.

O lado **Cliente** é responsável por transformar todo o conteúdo obtido da internet em uma experiencia de usuário. Isso implica em transformar todos códigos HTML, CSS e JavasCript em formas, estilos e aplicações.