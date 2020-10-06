#
# RedFox
# teste de desenvolvimento web
#

#
# como funciona o projeto?
#

Antes de tudo, queria dizer que o projeto ficou bem simples, eu dei meu máximo pra entregar o que a RedFox pediu, mas não saiu do jeito que eu queria, até porque não tive muito tempo pra fazer, eu precisava de mais tempo.

No layout, utilizei o framework Bootstrap.
No front-end, sei que pediram pra não usar jQuery, mas foi minha única opção. Eu sei um pouquinho sobre React, mas não consegui fazer a mesma coisa que fiz com o jQuery.
No back-end, não utilizei Node.js, não tenho conhecimento do mesmo.

Como eu disse no início, o projeto ficou bem simples. O usuário pesquisa o nome do pokémon, e o site retorna o resultado da pesquisa; fiz isso com JavaScript utilizando uma função com 8 variáveis. Caso o usuário pesquise uma informação que não existe, o site não irá retornar nenhum resultado.

Para pegar os dados dos pokémons, utilizei o arquivo do Excel e salvei com o formato .csv, usei um site pra converter os dados (csvtojson.com) de um arquivo .csv para JSON, copiei o arquivo JSON e joguei dentro de uma tag script lendo o documento e armazenando os dados em uma variável com o nome de "data".

Personalizei as tabelas utilizando as tables do Bootstrap. E usei uma input do Bootstrap para personalizar a caixa de pesquisa também.

Utilizei uma forma de pesquisa automática, cada letra que o usuário digitar, a função searchFunction() será chamada para fazer a pesquisa do pokémon para o usuário.

A função searchFunction() realiza as pesquisas de acordo com o nome dos pokémons. Exemplo: caso você digite 3 letras de um nome de um pokémon, se houver outro pokémon que tenha as mesmas 3 letras, o site irá retornar os 2 pokémons e assim em diante.
