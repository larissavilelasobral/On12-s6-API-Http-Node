# On11-TodasEmTech-s6-Introducao-Node
Turma Online 11 - Todas em Tech | Back-end | 2021 | Introdução à API:
HTTP e NodeJS

## Para o lar
Abra o PullRequest Respondendo as seguintes questões:

1) Qual a relação entre os métodos HTTP e o CRUD?
Os metodos HTTP são:
- GET
- HEAD
- POST
- PUT
- DELETE
- CONNECT
- OPTIONS 
- TRACE 
- PATCH

CRUD(Create, Read, Update and Delete)
- Create	- INSERT
- Read (Retrieve)	- SELECT
- Update	- UPDATE
- Delete (Destroy)	- DELETE

_Relação entre os métodos HTTP e CRUD:_

Create no HTTP é PUT/POST
Read no HTTP é GET    
Update no HTTP é PUT/POST/PATCH
Delete no HTTP é DELETE
__________________________________________________________

2) Comente, com exemplos, a diferença entre o PUT e o PATCH.
O método PUT ele subistitui tudo, já o metodo PATCH já é mais especifico e aplica modificações parciais.

3) Assim como na aula, apresente os dados dos JSONs no console 
    - No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
    - No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
    - No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

4) Defina o conceito de idempotência e como uma API pode ser idempotente
_idempotência: Um metodo HTTP é idempotente se uma requisição idêntica pode ser feita uma ou mais vezes em sequência com o mesmo efeito enquanto deixa o servidor no mesmo estado._
_API idempotente: uma API pode ser idempotente quando ela pode ser executada varias vezes sem efeitos colaterais.
5) Cite alguns diferentes padrões de projetos de software
_são soluções típicas para problemas comuns em projeto de software._
- Padrões criacionais 
- Padrões estruturais 
- Padrões comportamentais