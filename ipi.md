# CyberSecurity

## Roadmap
![mind map](mind.png)

# [OSI](osi.md)

## Redes

é um conjunto de dois ou mais dispositivos eletrônicos de computação interligados por um sistema de comunicação digital, guiados por um conjunto de regras (protocolo de rede) para compartilhar entre si informação, serviços e, recursos físicos e lógicos.

- [Camada de Rede](rede.md)

- [Camada de Aplicação](aplicacao.md)

## Servidor

Em informática, um servidor é um software ou computador, com sistema de computação centralizada que fornece serviços a uma rede de computadores, chamada de cliente.

- [Hardware](hardware.md)

- [Software](software.md)










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

### Como se informar sobre vulnerabilidades já descobertas por pesquisadores ?

### O que é CVE ?

O CVE, sigla inglesa para Vulnerabilidades e Exposições Comuns, é uma lista pública de falhas de segurança. Quando alguém menciona um CVE, geralmente está se referindo ao número de identificação (ID) atribuído a uma falha de segurança.

[Leia mais](https://www.redhat.com/pt-br/topics/security/what-is-cve)

### O que é exploit ?

Um exploit é um pedaço de software, um pedaço de dados ou uma sequência de comandos que tomam vantagem de um defeito, falha ou vulnerabilidade a fim de causar um comportamento acidental ou imprevisto a ocorrer no software ou hardware de um computador ou em algum eletrônico.

[Exploit Database](https://www.exploit-db.com/)

# Algumas falhas comuns

### Information disclosure

A divulgação de informações, também conhecida como vazamento de informações, ocorre quando um site da Web revela, sem querer, informações confidenciais a seus usuários. Dependendo do contexto, os sites podem vazar todos os tipos de informações para um invasor potencial, incluindo:

- Dados sobre outros usuários, como nomes de usuário ou informações financeiras
- Dados comerciais ou empresariais confidenciais
- Detalhes técnicos sobre o site e sua infraestrutura

![infodis](information-disclosure-.jpg)

[Leia mais](https://portswigger.net/web-security/information-disclosure)

[[!] Acesse o laboratório](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-excessive-trust-in-client-side-controls)

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

### SQL injection

A injeção de SQL é uma vulnerabilidade de segurança da web que permite que um invasor interfira nas consultas que um aplicativo faz ao seu banco de dados. Geralmente, permite que um invasor visualize dados que normalmente não é capaz de recuperar. Isso pode incluir dados pertencentes a outros usuários ou quaisquer outros dados que o próprio aplicativo é capaz de acessar. Em muitos casos, um invasor pode modificar ou excluir esses dados, causando alterações persistentes no conteúdo ou comportamento do aplicativo.

![xss](sql-injection.svg)

[Leia mais](https://portswigger.net/web-security/sql-injection)

[[!] Acesse o laboratório](https://portswigger.net/web-security/sql-injection/lab-retrieve-hidden-data)

Solução
[![Watch the video](https://img.youtube.com/vi/GxYsM3X5u0I/0.jpg)](https://youtu.be/GxYsM3X5u0I)
