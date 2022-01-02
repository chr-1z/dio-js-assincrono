# Javascript Assíncrono

Objetivo do Curso
- Explicar o conceito de assincronicidade
- Apresebtar Promises
- Ensinar como fazer requisições de APIs

Aula 1 - Assincronicidade <br /> 
Aula 2 - Consumindo APIs <br /> 
Aula 3 - Atividade Prática <br /> 

## Assincronicidade - Algo que não ocorre/não é efetivado ao mesmo tempo.
Ex: 
- Ir á aula presencialmente com a turma, síncrono.
- Estudar online, vê as aulas a hora que puder, assíncrono. <br />
### Promises - Objeto de processamento assíncrono
- Inicialmente seu valor é desconhecido. Pode então, ser resolvida ou rejeitada.

Promise
Ex: <br />
Um show pode acontecer ou não - then() ou catch()

Uma promise pode ter 3 estados
1) Pending - Pendente
2) Fulfilled - Completado
3) Rejected - Erro

### Async/Await
- Await faz parar o código até resolver, ai continua o código.
- Funções assíncronas tambem retornam Promises.
- Tem que declarar o await antes da função, sem isso, uma promise vai retornar outra promise.
- Pode ser utilizado o try...catch também.
