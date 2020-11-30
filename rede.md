# Camada de Rede

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

### Exemplo de requisição GET

    GET /hello.htm HTTP/1.1
    User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
    Host: www.tutorialspoint.com
    Accept-Language: en-us
    Accept-Encoding: gzip, deflate
    Connection: Keep-Alive

### Exemplo de requisição POST

    POST / HTTP/1.1
    Host: foo.com
    Content-Type: application/x-www-form-urlencoded
    Content-Length: 13

    say=Hi&to=Mom

![DNS](http_to_https-1.jpg)

[[!] Sujestão de leitura](https://www.alura.com.br/artigos/qual-e-diferenca-entre-http-e-https)

[Ler mais](https://canaltech.com.br/internet/o-que-e-dns/)
ou
[Assistir um video](https://youtu.be/oukRwnVAamo?list=PLucm8g_ezqNpGh95n-OdEk06ity7YYfvU)

- Correio eletrônico

Um correio eletrônico ou correio eletrónico ou, ainda, e-mail, é um método que permite compor, enviar e receber mensagens através de sistemas eletrônicos de comunicação. O Correio Eletrônico é tipicamente um modo assíncrono de comunicação.O termo "e-mail" é aplicado tanto aos sistemas que utilizam a Internet e que são baseados nos protocolos [POP3](https://pt.wikipedia.org/wiki/Post_Office_Protocol), [IMAP](https://pt.wikipedia.org/wiki/Internet_Message_Access_Protocol) e [SMTP](https://pt.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol), como àqueles sistemas conhecidos como intranets, que permitem a troca de mensagens dentro de uma empresa ou organização e que são, normalmente, baseados em protocolos proprietários.
