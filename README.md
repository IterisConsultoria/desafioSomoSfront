# SomoS - Desafio Frontend

Obrigado por participar do nosso desafio e pelo seu interesse em trabalhar conosco. Nós preparamos um desafio muito legal para você: Criar um catálogo de Pokemons!

<IMG  src="https://ih1.redbubble.net/image.733115337.2227/flat,1000x1000,075,f.jpg"  alt="PokeDex"/>

## Orientações

- Faça o desafio sozinho;
- Você poderá desenvolver seu frontend utilizando qualquer linguagem/framework;
- Faça sua aplicação utilizando o padrão REST. Escolha bem os métodos, endpoints e status codes de retorno;
- Crie um repositório **público** no GitHub;
- Inicie seu projeto, crie suas branches e faça seus commits regularmente;
- Você pode consultar qualquer site para auxiliá-lo no seu desenvolvimento;
- Na raiz do seu projeto, adicione um arquivo README detalhando como que buildamos e executamos o seu projeto. Você pode usar [este template](https://github.com/IterisConsultoria/desafioSomoSfront/blob/main/README-exemplo.md) para criar o seu;
- Qualquer dúvida sobre o desafio crie uma issue neste projeto e iremos te responder o mais rápido possível;
- Escolha sua playlist favorita e bora codar! Estamos torcendo por você 🤞🤞🏻🤞🏼🤞🏽🤞🏾🤞🏿

Boa sorte!

## O desafio

---

Criar um frontend com o catálogo de todos os Pokemons e suas respectivas informações. Para isto, iremos utilizar a [PokeApi](https://pokeapi.co/docs/v2) para recuperar os dados dos Pokemons e exibi-los em tela (inclusive as imagens). As operações que você precisará consumir são estas:

| #                                             | Objetivo                                                                           | Orientações                                             |
|-----------------------------------------------|------------------------------------------------------------------------------------|---------------------------------------------------|
| `GET https://pokeapi.co/api/v2/pokemon`      | Listar pokemons                                                                    | Este serviço possui opção de usar [paginação](https://pokeapi.co/docs/v2#resource-listspagination-section) com offset e limit |
| `GET https://pokeapi.co/api/v2/pokemon/{id}` | Recupera um pokemon específico com todos os detalhes dele, baseado no id informado | O retorno deste serviço possui muitas informações, para o desafio você só irá precisar destes campos: `id`, `name`, `sprites.other.official-artwork.front_default`, `types[].type.name`, `stats[].base_stat` e `stats[].stat.name`                                                  |

O frontend deverá conter uma lista paginada dos pokemons, com uma ação para exibir os detalhes de um determinado pokemon do lado direito da lista caso o usuário clique em um dos nomes dos pokemons.

### O que queremos que você construa

---

#### Obrigatório

- Uma listagem paginada de pokemons
- Um componente de detalhe de pokemons
- Um Easter Egg do Pikachu 💛

#### Opcional

- Deixar a aplicação visualmente agradável
- Adicionar responsividade
- Configurar a sua aplicação para rodar dentro de um container

### O que iremos avaliar

---

- O README
- Se a aplicação funciona
- A integração com a PokeApi
- A organização do seu código
- A disposição dos elementos em tela
- Seus commits, branches e etc

### O que não iremos avaliar

---

- Testes unitários

### Interface

---

Gostaríamos que a interface seja parecida com o protótipo abaixo. Use suas habilidades para deixá-la com o visual incrível, adicione cores, ícones e o que mais achar necessário.

![image.png](https://i.imgur.com/5r5cejh.png)

### O Easter Egg

---

Sim, queremos que você adicione um Easter Egg na sua aplicação. Se o usuário clicar três vezes na imagem do Pikachu, faça com que o background da aplicação vire esta imagem: https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/25.svg

## A Entrevista

---

Para a entrevista, certifique-se de que a sua aplicação estará funcionando na sua máquina para que você a apresente para nós.

## Links úteis

---

- [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)
- [PokeApi Pagination](https://pokeapi.co/docs/v2#resource-listspagination-section)
