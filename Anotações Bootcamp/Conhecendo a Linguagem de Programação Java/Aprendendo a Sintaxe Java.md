# Introdução
- O que é "Anatomia da Classe"?
  - É consolidar todo aspecto estrutural, onde é aplicado o código, por que foi inicializado em tal lugar e precisou encerrar em outro, por que existe um encandeamento de caracteres, chaves, colchetes, por que algumas palavras são escritas de forma espaçada ou identada. 
>#### Assuntos
>
>- **Estrutura inicial** - Conhecer o que é uma classe.  
>- **Padrão de nomenclatura** - Necessidade de adotar alguns padrões para tornar o código mais legível.  
>- **Declarando variáveis e métodos**
>- **Identação**
>- **Organizado arquivos** - Organização através de um conceito chamado "pacotes" (subdiretórios bem distribuídos nos projetos). Separar classes por pacotes.
>- **Java Beans** - O que é essa convenção para trazer mais clareza e objetividade nas implementações?

# Anatomia das Classes  
## Anatomia das Classes 1  
- **Escrita de código de um programa** - Composição de palavras pré-definifas pela linguagem com expressões utilizadas para determinar nome de arquivos, classes, atributos e métodos.  
- Existem projetos que recomendam que toda a implementação de seu programa seja escrita em inglês.  
- A classe precisa estar compatível com o nome do arquivo. Dentro da classe pode haver várias estruturas de composição (códigos, métodos, variáveis, expressões).  
- Grande parte das classes (99%) inciará com a expressão "public class". O nome da classe deve ser intuitivo.  
- P/ classe, a primeira letra deve ficar maiúscula, ex: MinhaClasse. P/ variáveis, minúscula: minhaVariável.  
- Se a classe for executável, ela precisa ter o método main. public static void main (String [] args){}.  
- Corpo da Classe MinhaClasse {} e corpo do método main {}.  
- A linguagem é constituída de arquivos java (classes) e essas classes estão ao nosso dispor. É preciso conhecê-las para dominar a linguagem.  
- System.out.print(){}.  
- Todas as classes precisam estar no diretório src.
## Anatomia das Classes 2  
> #### Padrão de Nomenclatura
> - **Arquivo.java:** Começa sempre com letra maiúscula. Palavra composta - segunda palavra começa com letra maiúscula também. Ex: ```Calculadora.java```, ```CalculadoraCientifica.java```.  
> - **Nome da classe no arquivo:** A classe deve possuir o mesmo nome do arquivo.java, exemplo:
> ```
> // arquivo CalculadoraCientifica
>
> public class CalculadoraCientifica {
>
>}
> ```
- Se o nome da classe for diferente do nome do arquivo, a IDE acusa um erro de escrita.
> **- Nome de variável:** Primeira letra SEMPRE minúscula. Se for nome composto, primeira da 1ª palavra minúscula e primeira da 2ª palavra (as próximas palavras também) maiúscula, ex: ``` ano ``` e ``` anoFabricacao ```. O nome dessa prática é "camelCase".
> - No entanto, existe uma regra adicional para variáveis imutáveis, como mostra no código abaixo (Conveção: totalmente letra maiúscula, separado por underline):
> ```
> final String BR = "Brasil"
> String BR = "Brasil"
> final double PI = 3.14
> double PI = 3.14
> int ESTADOS_BRASILEIRO = 27
> int ANO_2000 = 2000
> ```
> - Se a variável começa com letra maiúscula, já se pressupõe que ela recebeu o "final", ou seja, é uma variável imutável.
> #### Regras para declaração de variáveis:
> - Deve conter apenas letras, _ (underline), $ ou os números de 0 a 9.
> - Deve se iniciar com uma letra (preferencialmente), underline ou $, jamais com número.
> - Deve iniciar com letra minúscula (boa prática)
> - Não pode conter espaços
> - Não pode usar palavras-chave da linguagem
> - O nome deve ser único dentro de um escopo
## Anatomia das Classes 3
#### Declarando variáveis e métodos
Como identificar declaração de variáveis e métodos no programa? 
- Declarar uma variável em Java segue sempre a seguinte estrutura:
```
// Estrutura

Tipo nomeBemDefinido = Atribuição (opcional em alguns casos)

// Exemplo

int idade = 23;
double altura = 1.62;
Dog spike; //observe que aqui a variável spike não tem valor
```
- Declarando métodos em Java segue uma estrutura bem simples:
```
// Estrutura

TipoRetorno NomeObjetivoNoInfinitivo Parametro(s)

// Exemplo

int somar (int numeroUm, int numero2)

String formatarCep (long cep)
```
## Anatomia das Classes 4

####Identação  
- Termo utilizado para escrever o código do programa de forma hierárquica, facilitando assim a visualização e entendimento do programa.
- Em Python é utilizado a nível de estrutura, mas não é a realidade do Java.
## Anatomia das Classes 5
- **Organizando arquivos** - À medida que o sistema vai evoluindo, surgem novos arquivos (código fonte) na estrutura de arquivos do projeto. Isso exige que seja realizada uma organização desses arquivos através de pacotes (packages).
- **Convenção dos subdiretórios** - Prefixos aplicados nos projetos: Comercial = com; Organizacional = org; opensource = org ou opensource.
  - com(prefixo).hypertech(nome da empresa).notification.app/modelo/utilidade(pacote).
## Anatomia das Classes 6
# Tipos e Variáveis
## Tipos e Variáveis 1
