IP => seu endereço
TCP => portas de comunicação


IP ORIGEM           -----------DADOS----------->     IP DESTINO
porta de origem                                      porta de destino


DNS => tradução de " apelidos" ( google.com ) para o endereço ( ex: 8.8.8.8 )

Endereços públicos: 
     - ex: google.com

Endereços privados: 
     - ex: dispositivos pessoais

* um celular que possui um endereço privado acessa um site que possui endereço público (google.com)

- Para estabelecer uma conexão de um dispositivo privado com um serviço público, o dispositivo envia um SYN para o servidor do serviço requerido, o servidor devolve um SYN/ACK para o dispositivo autorizando a conexão, o dispositivo envia o ACK para o servidor e a conexão é estabelecida.


* WIRESHARK é uma ferramenta desenvolvida para monitar os pacotes que estão saindo e entrando no seu dispositivo.

porta 80 - HTTP
porta 22 - SSH
porta 443 - HTTPS
