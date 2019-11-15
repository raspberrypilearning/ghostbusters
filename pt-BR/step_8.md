## Adicionar um cronômetro

Agora você vai adicionar um cronômetro de forma que o jogador tenha apenas dez segundos para pegar o maior número possível de fantasmas.

--- task ---

Crie uma nova variável chamada 'tempo'.

--- /task ---

--- task ---

Será que você consegue adicionar um cronômetro no seu Palco para dar ao seu jogador somente 10 segundos para capturar fantasmas?

Seu cronômetro deve:

+ Começar mostrando 10 segundos
+ Contagem regressiva a cada segundo

O jogo deve parar quando o cronômetro chegar a 0.

--- hints ---
--- hint ---
`quando a bandeira verde for clicada`{:class="block3events"}, sua variável de `tempo`{:class="block3variables"} deve `mudar para 10`{:class="block3variables"}. Deverá então `mudar em -1`{:class="block3variables"} a cada segundo `até que chegue em 0`{:class="block3control"}.
--- /hint ---
--- hint --- Aqui estão os blocos que você vai precisar: ![ghost-sprite](images/ghost-backdrop.png)

```blocks3
pare [todos]

< [ ] = [ ] >

mude [tempo v] para [10]

adicione (-1) a [tempo v]

tempo :: variables

espere (1) seg

repita até que < >
fim

quando ⚑ for clicado

```

--- /hint --- --- hint --- Aqui está o código que você vai precisar para criar o cronômetro: ![backdrop icon](images/ghost-backdrop.png)

```blocks3
quando ⚑ for clicado
mude [tempo v] para [10]
repita até que < (tempo :: variables) = [0] >
espere (1) seg
adicione (-1) a [tempo v]
fim
pare [todos]
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

Peça a um amigo para testar seu jogo. Quantos pontos eles conseguem no placar?

--- /task ---

Se o seu jogo estiver muito fácil, você pode:

+ Dar ao jogador menos tempo
+ Fazer os fantasmas aparecerem com menos frequência
+ Diminuir o tamanho dos fantasmas

--- task ---

Mude e teste seu jogo algumas vezes até que você esteja satisfeito com o nível de dificuldade.

--- /task ---