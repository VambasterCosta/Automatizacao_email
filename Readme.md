# Automatização de email utilizando Python

- Aplicação desenvolvida para otimização de tempo de envio de emails maketing para lista de destinatários.

## Funcionalidades

- A aplicação envia em email padrão ('Content-Type', 'text/html') para uma lista de destinatários contidos em um arquivo externo (txt). Cada email após ser enviado respeita um tempo aleatório para que o servidor de email não bloquei o remetente como sendo spam por diversos disparos.

- O modelo de email em HTML pode ser modificado. Um bloco não foi implementado pois vai de acordo com as necessidades do usuário, neste caso seria as alterações de 'tags' dentro do arquivo, onde o aplicativo realizaria o 'replace', substiruindo as tags pelos dados informados.

- A aplicação gera um arquivo de logs para saber os procedimentos realizados pelo sistema.
