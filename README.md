# resumoApiREST

# Api REST e RESTFul

Apis são conjuntos de definições e protocolos para que uma aplicação fique mais simples estruturalmente, deixando um código menor e com maior agilidade para executá-lo. Também utilizada para aumentar a segurança entre conteúdos compartilhados entre os usuários e os recursos solicitados. 

## Diferenças entre REST e RESTFul

* REST: Conjunto de restrições de arquitetura. Funcionam com requerimentos HTTP para executar ações como o CRUD (Criar, ler, atualizar e deletar). Utiliza-se dos seguintes métodos: Get (Retorna um dado salvo anteriormente), Post (Cria um dado), Put (Altera um dado criado anteriormente) e Delete (Apaga um dado criado anteriormente). Geralmente os dados são salvos em arquivos JSON (Javascript Object Notation) ou XML (Extensible Markable language), na qual o JSON é utilizado como pares de valor chave, enquanto o XML é utilizado como padrão de árvore.

* RESTFul: É basicamente a evolução da Api REST, mas utilizada para serviços em nuvem, como: Google, Amazon, LinkedIn e Twitter.

## HTTP verbs

Os verbos HTTPS, mas também conhecidos como requisições indicam a ação de um determinado método, sendo os mais conhecidos:

* Get: Como já citado anteriormente, retorna dados salvos.
  
* Head: Solicita uma resposta semelhante ao Get, mas pode retornar qualquer tipo de recurso.

* Post: Como já citado anteriormente, cria um dado no banco.
  
* Put: Como já citado anteriormente, modifica um dado.
  
* Delete: Como já citado anteriormente, apaga um dado completamente.
  
* Connect: Cria uma conexão entre dois servidores.
  
* Options: Utilizada para mostrar as possíveis requisições que um cliente pode fazer.
  
* Trace: Realiza um teste de conexão entre os servidores.
  
* Patch: Modifica parcialmente um dado.

## HTTP Status Code

HTTP Status Code, são códigos que determinam como está o funcionamento do seu projeto e são divididos em três digitos sendo o primeiro deles uma classificação do problema:

1. 1xx (Informacional): Significa que a requisição foi recebida e o processo continua

2. 2xx (Sucesso): Requisição recebida, entendida e aceita.

3. 3xx (Redirecionamento): Significa que outra ação deve ser executada antes do processo atual.

4. 4xx: Erro de sintaxe.

5. 5xx: Erro no servidor.


    ---

Autor do resumo: Gabriel Barbosa - 01566611
