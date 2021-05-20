# Desafio Flutter - Pokédex

Este é um desafio que consiste no desenvolvimento de um app que mostre dados simples de determinados pokémons de acordo com a Pokédex global disponível em uma API gratuita.

#### LEIA AS INSTRUÇÕES POR COMPLETO ANTES DE COMEÇAR

### Requisitos

O app deve consumir a [Pokédex Api](https://pokeapi.co/ "Pokédex Api"),  essa API apresenta dados dos mais simples aos mais complexos. O intuito desse desafio é mostrar os dados da maneira mais simplificada possível.

- Utilize o **Flutter** para criar o seu app da forma que rode no mínimo em dispositivos Android
- OPCIONAL: Rodar na Web

### Tarefas

- O aplicativo deve ter duas telas principais:
 - A primeira tela deve conter:
 	- Uma lista contendo pokémons até a terceira geração contendo: 
		- Número na pokédex
		- Nome
		- Imagem
 - A segunda tela deve ter
 	- Informações básicas do pokémon selecionado da lista anterior: 
		- Tipo (Um pokémon pode conter apenas um ou até dois)
		- Habilidade (apenas uma)

### Observações

- Não utilize mais do que 3 bibliotecas externas (packages)
- Para pegar uma imagem de um determinado pokémon, utilize o seguinte índice do JSON:
`generation-iii": { "emerald": { "front_default" } }` (precisa ser generation-iii pra pegar todas as imgs das gerações de I a III)
- O objetivo deste desafio é avaliar o seu conhecimento técnico, estilo de código, conhecimento de arquiteturas, padrões de programação e boas práticas. Faça disso uma oportunidade pra mostrar todo o seu conhecimento.


### Opcionais (não necessário, porém contam pontos):

- Utilizar gerenciador de estado (MobX, GetX, Bloc ou Provider)
- Separar pastas entre backend e frontend (backend para chamadas da API e frontend para construção da interface)
- Fazer uma busca na lista dos pokémons pelo nome

### Processo de submissão

Para submeter o seu desafio, faça um fork deste projeto para sua conta no github, realize o clone e desenvolva localmente, no final, abra um pull request com o formato "[Flutter] - Nome" para a master até a data limite estabelecida. Um exemplo seria "[Flutter] - Felipe Magalhães".

