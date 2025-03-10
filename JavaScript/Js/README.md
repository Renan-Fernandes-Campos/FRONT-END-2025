# Javascript
- Estado do JS ( https://2020.stateofjs.com/en-US/technologies/ )
- Onde é executado = (é excutado pelo navegador)
- onipresente na web = (utilizada na maioria das aplicações web)
- App híbrido
- Aplicação de ponta-a-ponta: banco de dados ex: mongodb, back-end + nodejs / front-end
- Interagir com DOM (api-web)
- Requisições dinâmicas = (controlar ações dentro da pagina html)
- IoT (Internet das Coisas): o JS está presente em tudo
- ECMAScript = (Defini o padrão pra a linguagem)

# Fundamentos JS
- Fundamentos do JavaScript são essenciais para avançar no desenvolvimento de aplicações modernas, é a base de diversos frameworks
- Neste curso evoluímos da base para o topo
- É que melhor começar na frente e precisar retornar a base

# Metodologia
- Método progressivo e integrado
- Todo arranha céu só é erguido depois de ter uma fundação robusta e segura
- Neste curso apresentamos conceitos de modo progressivo, seguindo uma linha de evolução
- Começa fácil e vai aumentando a complexidade
- Além da especialização, aprender a integrar com diversas possibilidades

# Lógica de Programação
- Computador: -- Máquina que extrai dados -- Processador: realiza operações nos dados de entrada
- Dado: é o que pode ser processado
- Informação: resultado do processamento
- Processamento de dados: Entrada (dados) >[ Processamento ]> Saída (informação)

### E lógica?
Lógica é aquilo que faz sentido

### Como escrever um programa?
- Aplique a lógica para descrever os passos para resolver um problema em ordem de execução

### Lógica de programação
- É a técnica de sequenciar pensamentos, passos, fluxo de dados para atingir um objetivo: a informação
- A sequencia de passos, instruções que o computador deve seguir é conhecida como ALGORITMO

### Algoritmo
- Sequência lógica e finita de intruções que resolvem um problema
- Exemplo: receita de bolo, manual de instrução
- Nem todo algoritmo é um programa de computador, mas todo programa de computador é algoritmo
- Quem viabiliza o funcionamento dos algoritmos nos computadores: linguagens de programação

## Algoritmo para calcular a média de 3 números
1. Início;
2. Recebendo o primeiro número: entrada 1;
3. Receber o segundo número: entrada 2;
4. Recebendo o terceiro número: entrada 3;
5. PROCESSAMENTO: Somar os 3 números recebidos e dividir por três: (entrada 1 + entrada 2 + entrada 3) / 3;
6. Exibir o resultado: print, echo, console.log ;
7. fim;

## Torre de Hanói
Mover todos os discos para a direita, com o menor número de movimentos possíveis, sem colocar um disco em cima de um disco menor: https://www.somatematica.com.br/jogos/hanoi/
Jogos: https://www.somatematica.com.br/jogos.php

# Funcionalidades gerais do JS
- Criar algoritmos e programas para executar no navegador: lado do cliente
- Manipular o DOM: elementos HTML, eventos (clique, enviar), estilos CSS
- Node.js: framework JS para back-end / runtime em JS = (Do lado do servidor)
- Mongo.db / GraphQL: banco de dados em JS
- frameworks JS para desenvolvimento web / mobile: React / Vue.js / Angular: 
- framework JS para desenvolvimento: mobile React Native 
- rebece e manipular dados
- tomar decisões baseadas em lógica computacional
- loop e interações
- condições de saída

## Executar o JS
- Navegadores de console
- Editores: Sublime, Visual Studio Code
- JS Fiddle https://jsfiddle.net/

## Instalação do Node.js
- Para a gente conseguir executar scripts JS no terminal de comando, precisamos utilizar o Node.js
- Instalação: https://nodejs.org/pt-br/download/package-manager/
- Windows: Primeiro instale o Chocolatey
- Precisa executar o PowerShell como administrador
- se tudo der certo na instalação do Chocolatey, rodar: choco install nvs
- nvs add lts
- $ nvs use lts PATH -= %LOCALAPPDATA%\nvs\default PATH += %LOCALAPPDATA%\nvs\node\14.17.0\x64
- MacOs: Primeiro instale o Homebrew
- se tudo der certo na instalação do Homebrew, rodar: brew install node

### Após concluir a instalação
Rodar em um novo terminal: node -v (exibei a versão do nodejs)

## Variáveis
São usados ​​para referenciar o espaço na memória

- var
- const (fica com valor imutável)
- let (se utiliza também para uma const)
- string (tipo de variável para conjunto de caracteres ex: palavras,)
- tipagem: número ou string
- array: conjunto de valores ex: ["cep","rua",31,"numero",50] 
- [varialvel].length para vir o tamanho do arrayendereco

## operadores
- soma +
- Subtração -
- Multiplicar *
- Dividir /
- Módulo (restante de divisão) %
- Math: random(), round(), sqrt().

## Atribuição
a = b
a += b
a -= b 
a *= 
b a /= 
b a %= 
b Adiciona 1 ++ 
  Subtrai 1 --

## Operadores de Comparação / Lógicos
- == igual entre as sentenças (valor)
- === valor igual entre a sentença e o tipo (valor e e tipo) - [typeof]>para saber a tipagerm da variável
- !== difirente entre as sentenças (valor e tipo)
- Diferente !=
- Maior que >
- Maior ou igual >=
- Menor que <
- Menor que <=
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Expressions_and_operators

## Operadores de lógica e junção lógica
- ! nega a condição
- && para ser = treu as duas condições tem que ser verdadeiras
- || para ser = a true apenas uma condição precisa ser verdadeira

# Código Junto
Lista de Exercícios
Descrever um Algoritmo para resolver o problema Calcular a média de alunos.

JS: Exibir média de 3 números com entradas pelo formulário HTML Enviar link(s) do git ou do fiddle
https://jsfiddle.net/kov1nxz9/1/


# Condicionais e laços de repetição
- If ([condicao]){[execucao]}
- else 
- while ([condicao]){[execucao]}
- do while {[execucao]} while{[condicao]}
- for ([expressão_inicial];[condicao];[incremento]){[execucao]}