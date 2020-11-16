# CyberSecurity

## OSI
O modelo OSI fornece um padrão para que diferentes sistemas de computadores possam se comunicar e pode ser visto como uma linguagem universal para redes de computadores. É baseado no conceito de dividir um sistema de comunicação em sete camadas abstratas, empilhadas umas sobre as outras. 

![OSI model image](osi.jpg)

[Ler mais](https://www.cloudflare.com/pt-br/learning/ddos/glossary/open-systems-interconnection-model-osi)
ou
[Assistir um video](https://www.youtube.com/watch?v=WO1uGJRqrwI)


## Camada de Rede
- TCP

Protocolo de Controle de Transmissão é um dos protocolos de comunicação, da camada de transporte da rede de computadores do Modelo OSI, que dão suporte a rede global Internet, verificando se os dados são enviados na sequência correta e sem erros via rede. É complementado pelo protocolo da Internet, normalmente chamado de, TCP/IP.

![OSI model image](TCP_IP.webp)

[Ler mais](https://pt.wikipedia.org/wiki/Transmission_Control_Protocol)
ou
[Assistir um video](https://youtu.be/bH29oltn8Cw)

- UDP

 Através da utilização desse protocolo, pode-se enviar datagramas de uma máquina à outra, mas sem garantia de que os dados enviados chegarão intactos e na ordem correta. Além do mais, o UDP é um protocolo que não é voltado à conexão.

 ![TCP vs UDP](TCP-vs-UDP.jpg)

[[!] Sujestão de leitura](https://www.alura.com.br/artigos/quais-as-diferencas-entre-o-tcp-e-o-udp)

- IPV4

O IPv4 é um protocolo sem conexão, para utilização de comutação de pacotes redes. Ele opera em um modelo de entrega por menor esforço, em que não garante a entrega, nem garante a sequência correta ou evita a duplicação de entrega. Estes aspectos, incluindo a integridade dos dados, são abordados por uma camada superior de protocolo de transporte, tais como o Protocolo de Controle de Transmissão (TCP).

O IPv4 utiliza endereços de 32 bits, o que limita o espaço de endereço para 4294967296 (232) endereços.Datagrama:

![IPV4](ipv4.png)

[Ler mais](http://jkolb.com.br/protocolo-ip-ipv4-e-ipv6/)
ou
[Assistir um video](https://www.youtube.com/watch?v=XPWd08tLAuo)

- IPV6

IPv6 é a versão mais atual do Protocolo de Internet. Originalmente oficializada em 6 de junho de 2012, é fruto do esforço do IETF para criar a "nova geração do IP".

[Ler mais](http://jkolb.com.br/protocolo-ip-ipv4-e-ipv6/)
ou
[Assistir um video](https://www.youtube.com/watch?v=XPWd08tLAuo)

## Camada de Aplicação

- DNS

Os servidores DNS (Domain Name System, ou sistema de nomes de domínios) são os responsáveis por localizar e traduzir para números IP os endereços dos sites que digitamos nos navegadores.

Imagine ter que acessar seus sites preferidos através de números de IP (Internet Protocol), memorizando sequências de números para cada um deles. Conseguiríamos acessar meia dúzia deles no máximo, mais ou menos a mesma quantidade de números de telefone que conseguimos memorizar, não é?

![DNS](dns.png)

[Ler mais](https://canaltech.com.br/internet/o-que-e-dns/)
ou
[Assistir um video](https://youtu.be/oukRwnVAamo?list=PLucm8g_ezqNpGh95n-OdEk06ity7YYfvU)

- WWW

World Wide Web, o famoso WWW, é um sistema de documentos dispostos na Internet que permitem o acesso às informações apresentadas no formato de hipertexto. Para ter acesso a tais informações pode-se usar um programa de computador chamado navegador.

[Ler mais](https://www.tecmundo.com.br/web/759-o-que-e-world-wide-web-.htm)

- HTTP / HTTPS

HTTP é um protocolo de transferência que possibilita que as pessoas que inserem a URL do seu site na Web possam ver os conteúdos e dados que nele existem. A sigla vem do inglês Hypertext Transfer Protocol.

![DNS](http_to_https-1.jpg)

[[!] Sujestão de leitura](https://www.alura.com.br/artigos/qual-e-diferenca-entre-http-e-https)

[Ler mais](https://canaltech.com.br/internet/o-que-e-dns/)
ou
[Assistir um video](https://youtu.be/oukRwnVAamo?list=PLucm8g_ezqNpGh95n-OdEk06ity7YYfvU)

- Correio eletrônico

Um correio eletrônico ou correio eletrónico ou, ainda, e-mail, é um método que permite compor, enviar e receber mensagens através de sistemas eletrônicos de comunicação. O Correio Eletrônico é tipicamente um modo assíncrono de comunicação.O termo "e-mail" é aplicado tanto aos sistemas que utilizam a Internet e que são baseados nos protocolos [POP3](https://pt.wikipedia.org/wiki/Post_Office_Protocol), [IMAP](https://pt.wikipedia.org/wiki/Internet_Message_Access_Protocol) e [SMTP](https://pt.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol), como àqueles sistemas conhecidos como intranets, que permitem a troca de mensagens dentro de uma empresa ou organização e que são, normalmente, baseados em protocolos proprietários.

## Servidor

Em informática, um servidor é um software ou computador, com sistema de computação centralizada que fornece serviços a uma rede de computadores, chamada de cliente.

### Hardware

Um servidor é um computador equipado com um ou mais processadores, bancos de memória, portas de comunicação e, ocasionalmente, algum sistema para armazenamento de dados como hard disks internos ou memórias SSD. É mais forte do que um desktop comum.

![Placa Mãe](placa_mae.jpeg)

### Software

Servidor web é um software responsável por aceitar pedidos em HTTP de clientes, geralmente os navegadores, e servi-los com respostas em HTTP, incluindo opcionalmente dados, que geralmente são páginas web, tais como documentos em HTML com objetos embutidos (imagens, etc) ou um computador que executa um programa que provê a funcionalidade descrita anteriormente.O mais popular, e mais utilizado no mundo, é o servidor Apache (software livre). A Microsoft possui a sua própria solução denominada IIS (Internet Information Services).

![Apache](apache.png)


## Aprendendo novas tecnologias

### Cursos gratuitos

HTML => https://www.youtube.com/watch?v=epDCjksKMok&list=PLHz_AreHm4dlAnJ_jJtV29RFxnPHDuk9o

PHP => https://www.youtube.com/watch?v=R_yRrYUHai0&list=PLesCEcYj003TrV2MvUOnmVtMdgIp0C4Pd

Javascript => https://www.youtube.com/playlist?list=PLntvgXM11X6pi7mW0O4ZmfUI1xDSIbmTm

Python => https://www.youtube.com/watch?v=j94IGZmwtYI&list=PLesCEcYj003QxPQ4vTXkt22-E11aQvoVj

## Vulnerabilidades

### Information disclosure

A divulgação de informações, também conhecida como vazamento de informações, ocorre quando um site da Web revela, sem querer, informações confidenciais a seus usuários. Dependendo do contexto, os sites podem vazar todos os tipos de informações para um invasor potencial, incluindo:

- Dados sobre outros usuários, como nomes de usuário ou informações financeiras
- Dados comerciais ou empresariais confidenciais
- Detalhes técnicos sobre o site e sua infraestrutura

![infodis](information-disclosure-.jpg)

[Leia mais](https://portswigger.net/web-security/information-disclosure)

[[!] Acesse o laboratório](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls)

[![Watch the video](https://img.youtube.com/vi/Vlyx_GpL3Sg/0.jpg)](https://youtu.be/Vlyx_GpL3Sg)

### Business logic vulnerabilities

Vulnerabilidades de lógica de negócios são falhas no design e na implementação de um aplicativo que permitem que um invasor elicie um comportamento indesejado. Isso potencialmente permite que os invasores manipulem funcionalidades legítimas para atingir um objetivo malicioso. Essas falhas são geralmente o resultado da falha em antecipar os estados incomuns do aplicativo que podem ocorrer e, conseqüentemente, da falha em lidar com eles com segurança.

![Apache](logic.jpg)

[Leia mais](https://portswigger.net/web-security/logic-flaws)

[[!] Acesse o laboratório](https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-in-error-messages)

Solução

[![Watch the video](https://img.youtube.com/vi/Nmlo5qj-G3g/0.jpg)](https://youtu.be/Nmlo5qj-G3g)


### Cross-site scripting

Cross-site scripting (também conhecido como XSS) é uma vulnerabilidade de segurança da Web que permite que um invasor comprometa as interações que os usuários têm com um aplicativo vulnerável. Ele permite que um invasor contorne a política de mesma origem, que é projetada para separar sites diferentes uns dos outros. As vulnerabilidades de script entre sites normalmente permitem que um invasor se disfarce de usuário vítima, execute quaisquer ações que o usuário seja capaz de realizar e acesse quaisquer dados do usuário. Se o usuário vítima tiver acesso privilegiado dentro do aplicativo, o invasor poderá obter controle total sobre todas as funcionalidades e dados do aplicativo.

![xss](xss.svg)

[Leia mais](https://portswigger.net/web-security/cross-site-scripting)

[[!] Acesse o laboratório](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded)

Solução

[![Watch the video](https://img.youtube.com/vi/iOm_gsdVHpU/0.jpg)](https://youtu.be/iOm_gsdVHpU)
