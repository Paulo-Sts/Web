<div style="display:inline_block">
    <img align="left" height="100" width="100" alt="Web" src="https://www.pngall.com/wp-content/uploads/4/World-Wide-Web-PNG-Image-File.png">
</div>

# Web
Conceitos e Tecnologias da web e como desenvolver aplicações.

## Introdução

> #### DEFINIÇÃO
* A Web ou a Internet é um grande conjunto de redes de computadores interconectados por todo o mundo. Através da web é possível transmitir dados e estabelecer comunicação em seus mais diversos pontos.

> #### PROTOCOLO TCP/IP
* O TCP é o protocolo de comunicação adotado pela internet. Se baseia em estabelecer uma comunicação através das camadas de rede de forma confiável, para realizar a transferência de dados. O Protocolo IP é o responsável por realizar a comunicação entre redes definindo um endereço para cada máquina dentro da rede.

> #### PORTA
* É o responsável por mapear um processo. Para acessar a um processo deve-se acessar ao número da porta na qual aquele processo esta associado.

> #### PROTOCOLO HTTP
* Usando como base o protocolo TCP/IP, o protocolo HTTP, é utilizado na obtenção de recursos através de requisições para realizar a troca de dados entre cliente e servidor.
* A comunicação é feita através de solicitações de serviços (requisições) da parte do cliente (através de uma url e um conjunto de parâmetros) para o servidor que fornece um serviço (Geralmente documentos html, css, js e outras mídias) quando solicitado (resposta). A comunicação é feita de forma individual.
* Entre suas características estão a simplicidade de uso e sua extensabilidade (o fato de não possuir estado), ou seja, não existe relação entre requisições de uma mesma conexão.
* O HTTP utiliza um conjunto de métodos que definem diferentes tipos de operações, essas operações são realizadas através dos verbos HTTP. Os verbos HTTP são: Get, Post, Put, Delete, Trace, Options, Connect e Head.
* O HTTP também possui grupos de status, que trazem informações sobre a requisição solicitada.
    - 1xx = informação;
    - 2xx = Sucesso;
    - 3xx = Redirecionamento;
    - 4xx = Erro no Cliente;
    - 5xx = Erro no Servidor.

> #### SERVER SIDE E CLIENT SIDE
* As aplicações server side são aplicações em que tanto os dados como o conteúdo, são gerados e gerenciados por um servidor.
* As aplicações client side ou aplicações front-end são aquelas em que a parte de conteúdo visual é gerado dinâmicamente através de SPAs (single page aplications) utilizando o javascript e o servidor atua apenas fornecendo serviços web (que retornam dados), geralmente em formato JSON.

> #### SERVIDOR DNS
* Os servidores DNS, são servidores que fazem a tradução, mapeamento e apontamento de nomes de domínio na web para o endereços IP de um serviço. O endereçamento pode ser de um DNS para IP, DNS para outros DNS, DNS para servidores de email, entre outros.
* O DNS funciona através do protocolo UDP, usando a porta 53.

> #### HTTPS
* É o protocolo de comunicação com uma camada de criptografia que fornece segurança as requisições. O objetivo de uso do HTTPS é manter a integridade dos dados durante toda a transferência de informações através das redes. O mecanismo de segurança adicionado com o HTTPS se trata de um processo de criptografia dos dados através de um certificado.
* Os protocolos utilizados para a criptografia dos dados são o TLS ou SSL.
* Os certificados de uso do HTTPS são emitidos e validados por uma autoridade certificadora. Trata-se de um arquivo presente no servidor e no browser que habilita a criptografia e descriptografia dos dados das requisições.

> #### WEB SERVICE
* Trata-se de um ou mais serviços que uma aplicação disponibiliza, através das tecnologias da web. Uma característica da web é a transferência de informações por meio de formatos textuais como JSON ou XML, o que possibilita uma interoperabilidade entre diferentes sistemas que se utilizam das mais variadas linguagens de programação e outras tecnologias.
* Os principais modelos para a construção de web services são o SOAP e o REST (O modelo SOAP utiliza o formato WSDL e XML já o REST utiliza o HTTP e o JSON).

> #### CLOUD
* É um serviço utilitário de recursos computacionais em que o custo depende do consumo (se paga pelo que se usa) e estes são escaláveis de acordo com a necessidade de capacidade. 
* Os serviços de nuvem são possíveis através do processo de virtualização de máquinas e são subdivididos em alguns grupos de acordo com sua estrutura de funcionamento. 
*  A infraestrutura como serviço (IaaS) fornece o serviço de toda a infraestrutura de hardware e software em que é possível gerenciar diretamente diversos computadores, assim como gerenciar serviços de computação, armazenamento, banco de dados, funções e etc.
*  A plataforma como serviço (PaaS), atua com o fornecimento de uma infraestrutura pronta que suporta a implementação do código para execução de serviços na web.
*  O software como serviço (SaaS) fornece uma plataforma personalizável já pronta para uso em que é possível definir as características necessárias de acordo com a necessidade.
