# Notes_Java
Anotações sobre o Java: Básico/Intermediário/Avançado

<div>
 <h1 align="center"> :book: Livros para estudo </h1>
 
  :book: Algoritmos: Lógica para desenvolvimento de programação de computadores
  
  :book: Orientação a objetos: aprenda seus conceitos e suas aplicabilidades de forma efetiva
  
  :book: MYSQL: Comece com o principal banco de dados open source do mercado
  
  :book: Java: Como programar (Capítulos 1, 11, 20, 28, 29)
  
  :book: HTML e CSS
  
  :book: Estrututras de dados e algoritmos em Java Script
</div>

<h1>●❯────────────────────────────❮●</h1>

<!-- Conceitos Básicos -->
<div>
<h1 align="left"> :brain: Conceitos básicos </h1>
<ul align="left">

  <li>Informática: Aprender como funciona aplicativos e programas prontos</li>
  <li>Computação: Braço da matemática que resolve problemas na teoria</li>
  <li>Programação: Computação na prática, resolução de problemas na prática</li>
  <li>Hardware: Peças e placas do computador, literalmente a parte de fora</li>
  <li>Software: Programas que o computador executa</li>
  <li>Sistema operacional: (Windows, Linux, MacOs...) é a classe mais complexa de programas, ele é o mediador entre o Hardware e o Software</li>
  <li>Compilador: Transforma as linguagens de programação na linguagem que o computador entende (binário: 0 e 1). O compilador Java é o JavaC, transforma a                 linguagem de alto nível para bytecode (uma linguagem intermediária)</li>
  <li>Linguagem de alto nível: Mais próxima do entendimento humano (linguagens de programação conhecidas)</li>
  <li>Linguagem de baixo nível: Mais próximo do entendimento do computador (apenas 0 e 1)</li>

#

<h6 align="left"> Verificando erros </h6>

  <li>Qualquer Computador com uma JVM (máquina virtual que lê o bytecode) irá rodar o programa sem problemas</li>
  <li>Análise léxica: Verifica se os códigos estão certos e existem</li>
  <li>Análise Sintática: Verifica se a ordem está certa</li>
  <li>Análise Semântica: Verifica o sentido</li>
  <code>O compilador mostra onde está o erro, mas não o arruma.</code>
  <li>Algoritmo: Conjunto de passos finitos e organizados que, quando executados, resolvem determinado problema.</li>
  <li>Procedimento: Execução de passos infinita.</li>
  <li>JRE: Apenas pra quem quer usar o Java</li>
  <li>JDK: Para quem quer programar em Java</li>
  <li>A JDK tem: JavaC (compilador), Bibliotecas (códigos prontos), JavaTools(ferramentas), IDE - eclipse (facilitador)</li> 
  <li>Variáveis: São endereços de memória que guardam um valor</li>
</ul>
</div>

*Java é uma linguagem fortemente tipada, ou seja, tem muitos tipos de variável.*

<h1>●❯────────────────────────────❮●</h1>

<!-- Tipos de Dados Primitivos -->
<div> 
 <h1 align="left"> :computer: Tipos Primitivos :alien: </h1>
 <ul align="left">
 <h2 align="center">Em computação existem apenas 4 tipos de dados primitivos, algumas linguagens subdividem esses tipos de dados em outros de acordo com                     a capacidade de memória necessária para a variável. Mas de modo geral, os tipos de dados primitivos são:</h2>
  
  <li>INTEIRO: Representa valores numéricos negativo ou positivo sem casa decimal, ou seja, valores inteiros</li>
  <li>REAL: Representa valores numéricos negativo ou positivo com casa decimal, ou seja, valores reais. Também são chamados de ponto flutuante</li>
  <li>LÓGICO: Representa valores booleanos, assumindo apenas dois estados, VERDADEIRO ou FALSO. Pode ser representado apenas um bit (que aceita apenas 1               ou 0)</li>
  <li>TEXTO: Representa uma sequencia de um ou mais de caracteres, colocamos os valores do tipo TEXTO entre " " (aspas duplas)</li>
  <li>Boolean: Lógica de Verdadeiro ou Falso (True or False)</li>
  <li>Char (Armazena um caractere)</li>
  <li>Byte(8 Byts) – Capaz de armazenar valores entre -128 até 127</li>
  <li>Short(16 Byts) – Capaz de armazenar valores entre – 32768 até 32767</li>
  <li>Int(32 Byts) – Capaz de armazenar valores entre –2147483648 até 2147483647</li>
  <li>Long(64 Byts) - Capaz de armazenar valores entre –9223372036854775808 até 9223372036854775807</li>
  <li>Float(32 Byts)</li>
  <li>Double(64 Byts)</li>
 </ul>
</div>

<h1>●❯────────────────────────────❮●</h1>

<!-- Aritmética -->
<div>
 <h1 align="left"> :computer: Operações Aritméticas :fire: </h1>
 <ul align="left">
 <h2 align="center">Os operadores aritméticos são operadores binários, ou seja, funcionam com dois operandos. Por exemplo, a expressão “a + 1” contém o                       operador binário “+” (mais) e os dois operandos “a” e “1”.</h2>
  
  <li>Soma(+) - Soma um valor</li>
  <li>Subtração(-) - Subtrai um valor</li>
  <li>Multiplicação(*) - Multiplica um valor</li>
  <li>Divisão(/) - Divide um valor</li>
  <li>Resto(%) - Divide um valor</li>
 </ul>
</div>
 
 <h1>●❯────────────────────────────❮●</h1>
 
 <!-- Operadores Relacionais -->
<div>
 <h1 align="left"> :computer: Operadores Relacionais :smile_cat: </h1>
 <ul align="left">
 <h2 align="center">Operadores relacionais são utilizados para comparar valores, o resultado de uma expressão relacional é um valor booleano (VERDADEIRO                     ou FALSO). Os operadores relacionais são: igual, diferente, maior, menor, maior ou igual, menor ou igual</h2>
  <li>Maior que(>) - Compara se um valor é maior que outro valor</li>
  <li>Menor que(<) - Compara se um valor é menor que outro valor</li>
  <li>Maior ou igual que(>=) - Compara se um valor é maior ou igual que outro valor</li>
  <li>Menor ou igual que(<=) - Compara se um valor é menor ou igual que outro valor</li>
  <li>Diferente de(!=) - Compara se um valor é diferente ao outro valor</li>
  
  #
  
  <h6 align="left"> Operadores Lógicos </h6>
   <li>E(&&) – Só resulta verdade quando os dois são verdadeiros. Se determinada coisa é verdadeira E outra também é verdadeira, então ele executa. No                  Java é representado por &&</li>
   <li>OU(||) – Só resulta falso quando os dois valores forem falsos. Executa se uma condição for verdadeira. É representado por || no Java</li>
   <li>NÃO(!) – Inverte o valor, se for verdadeiro fica falso e se for falso fica verdadeiro. É representado por ! no Java</li>
  
  #
  
  <h6 align="left"> Estruturas de Controle </h6>
  
   - IF(Se) ➜ Se a condição for verdadeira ele executa.
```ruby
 If (condição) { }
```

   - ELSE(Se não) ➜ Se a condição do If não for verdadeira, o código executa o Else.
```ruby
 If (condição) { } else { }
```
 </ul>
</div>

 
*Se você fizer uma conta de real para inteiro o número após a vírgula se perde!
❯ Casting: Forçar a compilação com determinado tipo de variável. Colocar um (tipo da variável) antes da compilação.
❯ Overflow: quando a soma estoura o máximo do tipo ele dá a “volta”.            Exemplo byte: 127+1 = -128
❯ Underflow: quando a subtração estoura o máximo do tipo e dá a “volta”.                            Exemplo byte: -128 – 1 = 127
=> Tipo composto: String – Armazena um texto.

# 

Scanner
O java não tem uma função para ler do teclado diretamente na sua linguagem, por isso precisamos “criar” ele. Para isso nós primeiramente importamos o pacote Scanner com o código: import java.util.Scanner; lá no começo do programa.
O nome que eu uso para o Scanner é o que o professor ensinou, “leitor”. Para criar o nosso Scanner, usamos o código: Scanner leitor = new Scanner (System.in);
Um atalho é escrever apenas o código de baixo e apertar cntrl + espaço quando escrever o Scanner e em seguida apertar ENTER, com isso ele vai importar o Scanner automaticamente.
O código para ler um valor e guardá-lo em uma variável é: leitor.nextTipodavariavel(); ou seja, se o tipo da variável for int você criará um leitor assim: leitor.nextInt(); e assim é para todos os tipos de variável. 

=> SWITCH CASE serve apenas para comparações (==) se o valor na variável for igual ao valor no case, executa.
Switch (variável){
Case valor:
Break;
Case valor:
Break;
Default:
Break;
O break é um comando que faz pular para outro bloco de código, ele interrompe o switch assim que o valor é encontrado.
O default é como se fosse um else. Se o valor for igual a 1 executa determinada coisa, se for igual a 2 executa outra coisa e se não for ele executa o conteúdo no default.



Estruturas de Repetição
=> Contador: Conta quantas vezes será executado. Precisa saber previamente quantas vezes será executado.
- For (tipoVariavel i = começoVariavel; i - operaçãoRelacional - condição; i – acrescentar ou incrementar) {
Precisa criar uma variável para o contador e essa variável só existira dentro dele, essa variável é comumente chamada de i. 
Depois de criar a variável que irá contar, nós determinamos onde ela começa podendo ser um valor fixo ou uma variável. 
Depois determinamos até onde o for repetirá. Depois definimos qual valor ele irá acrescentar ao i. Normalmente acrescentamos 1 usando o i++, mas outros valores também são possíveis. Também é possível subtrair o valor inicial, contando em ordem decrescente.
 For (int i = 1; i <=10; i++) {
Esse é um for para executar 10 vezes o seu conteúdo.

=> Condição: O código é executado ENQUANTO a condição for verdadeira. Não se sabe previamente quantas vezes será executado.
- while (condição) {
Se a condição for verdadeira, executa e testa novamente. Enquanto for verdadeira repete o laço.
- Do while: Mesma coisa que o while, porém ele primeiro executa e depois testa. Ele sempre executará pelo menos uma vez, testará e, se for verdadeiro repete o laço.
Do {
} while (condição);
Depurar projeto (Debugar)
É um método para achar bugs e problemas no seu programa.
Primeiro você clica duas vezes numa linha de código onde você quer começar o teste e irá aparecer uma bolinha.
 
Após isso clique com o botão direito no arquivo do seu programa e vá em DEBUG AS, depois clique em Java application.
Ele irá executar o programa passo a passo, mostrando os valores que são atribuidos as variáveis. Para avançar um passo clique numa seta amarela em cima do programa.
 
Para voltar a execução normal clique novamente com o botão direito e cliquem em RUN AS e java application
Vetor
É uma variável que armazena vários valores (quantos precisar) no mesmo endereço de memória. É preciso saber e definir previamente o tamanho do vetor, ou seja, a quantidade de valores que serão guardados. Elas também têm tipos (int, float, String...) e são imutáveis.
Para usá-la precisamos cria-la igual o Scanner (porém não precisa importar).
Int nome [] = new tipoVariavel [tamanho];
Para atribuir valores ou buscar valores já atribuídos usamos: 
Nome [endereçoDeMemória ]
O endereço de memória dos vetores sempre começa em 0 e o último sempre será o tamanho – 1. Se o tamanho for 5 então teremos: 0, 1, 2, 3, 4.
For each
Serve para ler todas as informações de um vetor. É um açúcar sintático.
For ( int i: vetor) {
}
Matriz

SUBROTINA
Trechos de código que pode ser reutilizado. Algoritmo que faz uma função específica. Ele é isolado do código principal e é chamado por um comando específico para ser usado novamente. Não podem estar dentro do método main. Dividida em dois tipos: Funções e Procedimentos.
- Função: Executa e te retorna um valor. Tem que ter um "return". O código da função tem que estar acima do return.
- Procedimento: Executa e acaba. Não retorna um valor.
--> o método main (public static void (String[]args)) também é uma sub-rotina (procedimento). É o ponto de partida do programa. 
- public static ignora agora. 
- void: tipo de retorno (função ou procedimento). Void significa "vazio", por isso o método main é um procedimento, pois ele não retorna nada. 
- main: nome da sub-rotina. 
- (): parâmetros da sub-rotina, informações que ela precisa pra funcionar (nem sempre são necessários). Sempre terá que ser variáveis, dizendo o tipo e nome.
---> Prática da Função: public static int soma (int numero1, int numero2) { 
return numero1 + numero2; 
-Precisa-se criar variáveis para os parâmetros. 
-O return serve para retornar o valor da função. 
- int: tipo de retorno (vai retornar um valor int). -Soma: nome da sub-rotina. 
-(int numero1, int numero2): parâmetros, informações pra ele somar. 
--> para usar: soma (2,2); (2,2) 
- As informações que eu passei para a função executar, chamadas de argumento.           * argumentos e parâmetros têm que ter o mesmo tipo e a mesma quantidade pra funcionar. 
-> para guardar esse valor basta criar uma variável e atribuir a função a ela. (Tem que ter o mesmo tipo do tipo de retorno) 
 O print e o Scanner também são uma sub-rotina -> as outras sub-rotinas não têm entrada e saída de dados, apenas no main.
----> "continue": código que ignora aquele if e continua a repetição

Programação Orientada a Objetos

-Antigamente só havia o paradigma estruturado, em 73 Alan Kay criou a primeira linguagem orientada a objetos.
-POO é uma forma de resolver problemas inspirada na vida real, dois conceitos importantes: Classe e Objeto.
Classe
Descreve uma entidade do problema, é uma ideia, uma forma. É constituída de membros, que se divide em dois:
-Atributos: Descrevem as qualidades de uma classe, as informações que ela precisa.
Exemplo: Tamanho, cor, nome...
Essas informações serão variáveis criadas para esta classe. Se eu criar uma classe "Aluno", alguns atributos dele seriam: nome, idade, cpf, etc. Essas são as informações gerais que todos os alunos devem conter.
-Métodos: Ações que uma classe pode realizar. Serão sempre Sub-rotinas.
Exemplo: O que um aluno pode fazer? Responder chamada, ver sua nota, resolver uma atividade, etc.
Ordem de estrutura: Atributos, métodos de construção, métodos de acesso e os métodos normais.
Objeto
É criado a partir de uma classe e é uma especificação dela. É a ideia da classe depois de ser criada definitivamente.
Por exemplo: Eu criei a classe aluno que descreve as predefinições de um aluno. Criando um objeto "Aluno1" eu descrevo as características específicas de um aluno, atribuindo as informações desse aluno em específico. (As informações do objeto sempre serão relacionadas aos atributos da classe)	.
-O responsável por atribuir coisas para suas variáveis e modificá-las tem que ser o próprio objeto, por isso as atribuições têm que ser feitas na própria classe. Ele não pode ser modificado ou acessado de fora da classe pois não teria controle se as informações estão corretas ou não.
-Para isso, usamos os *modificadores de acesso* para controlar quem tem acesso ou não as informações.
--------Prática:
-Para criar um objeto é como criar um vetor, porém o tipo da variável vai ser nossa classe criada anteriormente.
Ex:	Aluno aluno1 = new Aluno ();
Cria um objeto com atributos vazios por padrão, para criá-los com algo use o método construtor.
-Para chamar o método para que o objeto o exerça, precisa-se usar o nome do objeto + o método desejável.
Ex: 	Aluno1.responderChamada();

Métodos
Os métodos seguirão o mesmo conceito que a subrotina vista anteriormente. Os métodos são ações que uma classe pode realizar. É equivalente a uma função, subrotina ou procedimento. Não existem métodos globais, eles sempre devem estar dentro de uma classe, mas uma classe não precisa ter obrigatoriamente um método. A sintaxe de um método é:
[modificador] tipo_retorno identificador ([argumentos]) {
//Corpo do método
}
O modificador será visto a seguir, o tipo de retorno é baseado no tipo de algum atributo, por exemplo: String, int, Aluno (pode retornar uma classe!). O identificador será o nome do método, algumas regras:
O nome de um método deve começar com uma letra (a-z/A-Z), um underscore (_), ou um sinal de dólar ($). Os caracteres subsequentes podem incluir os dígitos de 0 a 9.
Convenção: Use verbos para nome de métodos. Faça a primeira letra do nome
minúscula com cada letra inicial interna maiúscula. Por exemplo: getUserName(),
getMaxPrice().
Os argumentos é o mesmo que um parâmetro, usados nas subrotinas. Um método pode ter zero ou mais parâmetros. Cada argumento deve ser declarado como define-se uma variável, especificando o seu tipo e nome. Caso seja mais de um argumento, cada declaração deve estar separada por vírgula.
public void setIdade(int novaIdade)
{
Idade = novaIdade;
}
É possível retornar um valor a partir de um método. Para isso, é preciso definir, na frente do nome do método, o tipo do valor a ser retornado. O tipo pode ser um primitivo ou então uma classe ou interface. Caso o método não retorne valor algum, é obrigatória a utilização do tipo void na assinatura do método. Exemplo:
public int getIdade () {
return Idade;
}
O comando return é utilizado para passar o valor requerido de volta para quem chamou o método e é obrigatório quando o tipo de retorno não é void. Ele deve receber um único valor ou uma expressão que deve ser compatível com o tipo de retorno especificado para o método. Quando o comando é encontrado, o método termina sua execução imediatamente, ignorando todas as instruções seguintes.
Modificadores de Acesso 
Servem para mudar quem tem acesso ao atributo ou método.	
-Public (públicos): São os programas em que suas informações podem ser acessadas em qualquer parte do projeto. Tem + como símbolo.
-Private (privados): Programas acessíveis e existentes apenas na própria classe, dentro do seu próprio local. Não permitindo ações fora dele. Tem - como símbolo. Quando usamos o private precisamos usar o método de encapsulamento com os getters e setters.
-Protect (protegido):  Só existe e é visível na própria classe e nas subclasses. Tem # como símbolo.
Atribuições dos objetos não devem ser acessadas fora dele, por isso nós as tornamos privadas. Para acessar os atributos fora da classe criamos Sub-rotinas na própria classe para acessá-los. Essas Sub-rotinas são chamadas de *Métodos de Acesso*

Métodos de Acesso (Encapsulamento)
Os métodos de acesso servem para impedir que as coisas fora de uma classe específica tenham acesso aos atributos dessa classe diretamente. Eles são uma forma de controle dos atributos da classe, podendo criar tratamentos de exceção no mesmo.
-Get: Serve para retornar o valor do atributo. Exemplo de uso: Para printar o valor da variável.
public tipoDoAtributo getNomeDoAtributo () {
return nomeDoAtributo;
}
Usamos o get para pegar o valor que já está preenchido no determinado atributo. Exemplo:
System.out.print(“Olá “ + aluno.getNome() + “!”);
-Set: Serve para atribuir um valor ao atributo. Também serve para validar o valor.
public void setNomeDoAtributo (tipoDoAtributo nomeDoAtributo){
this.nomeDoAtributo = nomeDoAtributo;
}
Usamos o set para adicionar um valor para um atributo, por exemplo, quando queremos adicionar um nome de um aluno usamos:
aluno.setNome(“Rodrigo”);
O set serve principalmente para receber esse nome do aluno, verificar ele (com um tratamento de exceção) e colocar no atributo da classe. 
*this(esse) serve para indicar que uma das variáveis é um atributo e não um parâmetro
Quando queremos modificar ou usar o objeto fora da classe, temos que chamar essas sub-rotinas criadas ao invés de chamar o local da informação. Exemplo:
GET - System.out.print(getNomeDoAtributo ())
SET – setNomeDoAtributo(valor);
 

Métodos de Construção
É o método responsável por construir um objeto, eles têm o mesmo nome que a classe e são vazios por padrão. Ou seja, quando você cria um objeto ele não tem nenhum valor atribuído por padrão.
Servem para construir um objeto com as atribuições desejadas anteriormente. Se eu criar um método de construção para criar o objeto já com as informações de nome, matrícula e idade, o objeto já será criado com essas informações atribuídas a ele.
Posso ter quantos construtores eu quiser, porém eles precisam ter quantidades diferentes.
--Prática: 
-Para criar o método de construção:
Public Alunos () {
setNomeDoAtributo(valor);
}
-Para criar o objeto com as variáveis desejadas:
Aluno nomeObjeto = new Aluno (atributo, atributo, atributo...);
Como se fossem argumentos.

HERANÇA
Uma hierarquia, é um relacionamento entre classes. Várias classes que apesar de representarem coisas diferentes tem algo em comum, uma relação. Essas classes têm as mesmas informações e os mesmos atributos.
•	Classe Base: A classe que concede as características a uma outra classe. Uma classe mais genérica, quanto mais sobe na hierarquia mais genérica e abstrata é.
•	Classe Derivada: A classe que herda as características da classe base. Classes mais específicas, quanto mais desce na hierarquia mais específica e concreta é.
Para ser uma herança precisa responder à pergunta: É um?
Exemplo: Um peixe é um animal? Se sim, pode ser herança.

Elas herdam atributos e métodos.
A classe que está no topo da relação é superclasse e a que está em baixo é subclasse.

Para estabelecer a herança usamos extends
Exemplo: 
public class Quadrado extends Quadrilátero {

As subclasses têm que ter um construtor que “chame” o construtor da classe superclasse. Para isso usamos o “super” que é referente a superclasse. Ex:
public class Retângulo extends Quadrilatero {
 
public Retângulo (float ladoA, float ladoB, float ladoC, float ladoD) {
super (ladoA, ladoB, ladoC, ladoD);
}
}
A superclasse nunca vai ter um objeto criado a partir dela diretamente. Esse tipo de classe se chama de abstrata. Classes acima da hierarquia geralmente as classes são abstratas.
Classes abstratas: Não se pode criar objetos a partir dela.
Classes concretas: São classes que se criam objetos a partir dela.
Mudando a classe para abstrata não se pode criar objetos a partir dela, para isso usamos “abstract”.

Assinatura vs Corpo do método (Dois métodos são iguais quando eles têm a mesma Assinatura)
-Assinatura é composta por modificador de acesso, tipo de retorno, nome, tipos e quantidade dos parâmetros.
-Corpo é o que está dentro do abre e fecha chaves {}.

Os métodos da superclasse que não são gerais para suas subclasses não têm corpo, apenas assinatura. São chamados de métodos abstratos. Para isso também adicionamos o “abstract”.

Servem para as subclasses herdarem esse método e adicionarem um corpo a ele. Cada subclasse vai reescrever dando o seu próprio corpo. Isso se chama sobrescrever (overwriter) um método. *Ele tem que ter a mesma assinatura!!*

Sobrecarga (Overloading) = métodos com o mesmo nome, mas com assinaturas diferentes.
Abstração
O conceito de abstração é montar as classes com apenas os atributos necessários para a construção do sistema e para solucionar dos problemas. É organizar os atributos evitando informações desnecessárias, ajuda no rendimento e velocidade do programa.
Interface
É uma classe abstrata que só possui métodos abstratos. Se querer usar atributos, só pode usar atributos estáticos (Pois é uma classe abstrata). Quando nós queremos “extender” nossa classe como na herança, nós usamos implementar(implements) ao invés de extender.
“Contrato” - A subclasse recebe uma lista de métodos da superclasse e tem que dar corpo pra eles, a partir disso ela se torna parte da superclasse.
Uma classe só pode implementar várias outras.
Na interface todos os métodos são públicos e abstratos por padrão. 
Quando usar? Quando temos classes em comum, mas não possuem nenhum atributo relacionado.
*Existe herança entre interfaces!*
Polimorfismo
É a capacidade de um método de apresentar várias formas diferentes baseado no objeto que ele está sendo chamado. Usa-se o polimorfismo através de herança ou interface pela sobrescrita de métodos.
**Tem como fazer casting de objetos**
Padrões de projeto - 1
Receitas a serem seguidas para resolver determinados problemas.
Como estruturar um projeto, separar as classes e consequentemente organizá-las:
MVC: Organiza as classes cada uma em sua pastinha. Pega o sistema e separa em tres partes: model, view e 
-Model(modelo): Entidades, enumerações, interfaces, classes abstratas.
-View(visão): Interfaces gráficas, tela.
-Controller(controle): Faz a comunicação entre o modelo e a visão. Pega informação da tela e salva no banco de dados, depois pega o que ta no banco de dados e mostra na tela.
Cada um deles se cria um pacote. Um pacote é uma pasta para organizar seu projeto.

Tratamento de exceção
Uma exceção é uma execução anormal do programa.
Exceções são execuções que você consegue recuperar e continuar o programa.
Um erro é irreparável e aborta o programa. Normalmente é um problema na máquina virtual.
Erro não são tratáveis, exceções sim. 
Um erro é causado devido à falta de recursos do sistema e uma exceção é causada por causa de seu código.
--Para criar uma exceção:
public class NomeInvalidoException extends Exception{
public NomeInvalidoException (String mensagem) {
super(mensagem);
Uma exceção armazenará uma mensagem.
--Para lançar uma exceção:
Quando uma exceção é encontrada, ela é lançada e, ou é tratada ou passa para frente.
Throw: Lança a exceção. Usado normalmente dentro de um if (dentro do set).
Throws: Lança a exceção dizendo que quem está lançando não é quem vai tratar, por isso ele vai passar adiante. Usado na assinatura do set.
public void setNome(String nome) throws NomeInvalidoException {
if (nome.isEmpty())
throw new NomeInvalidoException("O nome do aluno é inválido.");
this.nome = nome;}
--No main:
Try: Ele engloba o código onde pode ter uma exceção. Código de acesso ao banco de dados (Tente isso) É onde cria-se as coisas para verificar se tem erro, se tiver erro cai pro catch.
Catch: Onde capta e é feito o tratamento dos erros.
Finally: Fecha a conexão com o banco de dados. Sempre vai ser executado.

**IsEmpty () = verifica se a String é vazia.**
**System.err.println: Sysout para erros, a linha fica vermelha**
 
 
Estrutura de dados

Vetor: tempo constante (quando eu sei o índice da informação que eu quero) vs tempo linear (quando eu não sei o índice da informação que eu quero).
Árvore: Um nó (ou raiz) e dois galhos que levam a outros dois nós. Os últimos galhos que não tem novos nós chamamos de folhas.
Valores menores a esquerda e valores maiores a direita.
Armazena a informação de forma ordenada.
 





API e Bibliotecas
API de coleções no java: Collection Framework Hierarchy in Java.
 (em verde são interfaces, bege são classes, linhas normais são heranças e linhas pontilhadas são implementações)

Set (Conjunto): Não permite elementos repetidos.
Lista (List)
Sequência de elementos que podem ser acessados de forma aleatória. Ela permite elementos repetidos.
-Vetor: 
-Pilha: Não se pode colocar elementos em qualquer lugar. Fifo (first in first out). É uma lista que só se pode colocar e remover elementos no “topo”. O último a entrar é sempre o primeiro a sair. (Queue)
 
-Filas: Não se pode colocar elementos em qualquer lugar da fila, só se pode colocar elementos no final da fila. Se quiser remover um elemento só pode remover o primeiro. O primeiro a entrar é o primeiro a sair.
  

ArrayList: Uma classe que usa um vetor para recuperar informação e gerenciá-las. Tem tamanho 10 por padrão, mas pode ser mudado. Você passa as informações pra ela e ela mesmo se gerencia.
Sempre que é necessário o seu tamanho aumenta ou diminui em 50% do tamanho da lista, significa que se você tiver uma lista de tamanho igual a 10 e ela “encher”, seu tamanho aumentará para 15 automaticamente.

LinkedList(lista ligada): Usa uma lista de objetos nós (que guarda dois valores: o próprio valor e o próximo). 
-Lista duplamente ligada: o nó guarda o próprio valor, o próximo e o anterior.
-Lista cicla: O primeiro nó guarda o próprio valor e valor do último nó e vice-versa, criando um ciclo.
 

Link: https://www.devmedia.com.br/diferenca-entre-arraylist-vector-e-linkedlist-em-java/29162

Métodos de arraylist
Generics <E>: Artefato do java que cria classes genéricas. Um atributo que pode assumir qualquer tipo de dados.
add (E e): Adiciona um elemento na coleção. O e minúsculo é o tipo que você quer adicionar, o E maiúsculo é relacionado ao generics.
Add(int index, E element): Adiciona um elemento numa determinada posição.
AddAll(Collecition<? Extends E> c):  Adiciona uma lista.
Clear ():  Limpa a lista.
EnsureCapacity: Aumenta o vetor em determinado tamanho a mais.
Contains (Object o): Retorna se o elemento está ou não na lista.
ContainsAll (Collections <?> c): Retorna se uma coleção está ou não na lista
Get (int index): recupera o elemento na posição(indice) informada.
IndexOf (Object o): recupera o elemento onde está o objeto informado (o próprio objeto)
LastIndexOf(Object o): Informa o último índice que o objeto aparece na lista.
Equals (Object o): Compara elementos. (Apenas compara endereço de memória!!).
HashCode ():
Remove (int index): remove o objeto do índice. 
Remove (Object o): Tira o objeto da lista. (A primeira ocorrencia)
RemoveRange (int fromIndex int toIndex): Informa um indice A e um B e remove todos os elementos entre eles.
Size (): retorna o tamanho da coleção (quantidade de elementos).

Link: https://docs.oracle.com/javase/7/docs/api/java/util/Collections.html
Equals
O equals é um método que compara elementos pelos seus endereços de memória. Por este motivo, as vezes o equals padrão não é eficiente o suficiente. Por isso precisamos reescrevê-los nas nossas classes de entidade.
Comparação padrão:
public boolean equals (Object objeto) {
if (this == objeto)
return true;
if(objeto == null || this.getClass() != objeto.getClass())
return false;
E precisamos comparar todos os atributos para ter certeza de que eles são iguais:
Quadrilatero quadrilatero = (Quadrilatero) objeto;
return this.getLadoA() == quadrilatero.getLadoA() && this.getLadoB() == quadrilatero.getLadoB() && this.getLadoC() == quadrilatero.getLadoC() && this.getLadoD() == quadrilatero.getLadoD();

Git
Ferramenta para gerenciar o nosso código. É um controle de versão (registra mudanças no arquivo ao longo do tempo, o que possibilita recuperar versões anteriores específicas). Ainda vou fazer um resumo disso XD

Banco de Dados - MYSQL
-Dados transientes são dados salvos apenas em memória, que quando o computador é desligado os dados se perdem. (Antigamente só havia eles!)
-Dados persistentes que são salvos fisicamente, mesmo com o computador desligado. (importante para o desenvolvimento da tecnologia)
O mysql não é exatamente um banco de dados e sim um sgbd (um programa que gerencia um banco de dados). O banco de dados em si é a parte desse programa que guarda informações.
O mysql workbench é uma interface gráfica que interage com o mysql. É uma ferramenta para facilitar nossa vida.
Um Banco de dados relacionais se baseia em tabelas e suas relações. 
 --Registros, Tabelas e Arquivos
Registro é como se fosse um documento de uma pessoa, guardando sua informação.
Tabelas são como se fossem pastas, que guardam vários registros.
Banco de dados são como se fossem armários, que guardam várias tabelas.
Para mexer no banco de dados usamos uma linguagem chamada SQL. Uma linguagem estruturada de consulta. (Não é uma linguagem de programação!). Apesar de ser uma linguagem padronizada, os bancos diferentes mudam um pouco entre si.
Ela é baseada no inglês e garante a consistência do banco. Tem comandos responsáveis por pesquisar dados, inserir, alterar, excluir, etc. Pode ser escrita em uma ou mais linhas, tem quebra de linha.
A SQL sugere a tabulação e endentação.
Os comandos não são sensitivos e não podem ser abreviados. É uma linguagem não procedural.

Operações relacionais SQL
Restrição: Conjunto horizontal - tuplas
Projeção: Conjunto vertical - atributos
Produto: Todas as tuplas da 1ª relação estçao concatenados com as tuplas da 2ª relação.
Associação: Tuplas de duas relações concatenadas com uma específica condição ou condições.
União: Todas as tuplas da duas relações.
Intersecção: Tuplas comuns na relação.
Diferença: Tuplas da 1ª relação que não pertencem a 2ª relação.


A SQL tem sub-linguagens que englobam comandos com papéis parecidos:
DDL: Comandos de definição da estrutura da base de dados. Exemplo: create, alter, drop, rename, truncate.
DML: Manipulação dos dados. Exemplo: insert, update, delete.
DQL: Solicitações. Exemplo: Select.
DCL: Controle, definir quais usuários mechem no banco de dados e quais coisas eles podem mexer. Muda as autorizações do banco. Gerencia a segurança. Exemplo: grant, revoke.
DTL: Transações. Transação é qualquer solicitação que pode ser feita a um banco de dados que ele irá te atender da melhor forma possível usando quatro mandamentos chamados de D.I.C.A. É igual os commits do git. Exemplos: commit, rollback, savepoint.
D = Durabilidade: Todo dado que é colocado ou manipulado tem que permanecer dessa maneira até quando eu quiser que ele esteja lá.
I = Isolamento: Duas transações feitas ao mesmo tempo têm que ser executadas sem uma interferir na outra, tem que ser feita de forma isolada.
C = Consistência: Toda transação tem que levar de um estado consistente a outro estado consistente (Se tudo está ok antes, tem que estar tudo ok depois).
A = Atomicidade: Toda transação tem que dar tudo certo ou tudo errado. Ou dá certo completamente ou volta ao estado anterior.

---O sgbd tem vários objetos que gerenciam as informações, sendo eles:
Tabela: Unidade básica de armazenamento, composta de linhas e colunas (igual a tabela do excel). Divididas entre colunas (que separam os atributos) e linhas (que guardam as informações de um determinado aluno relativo à coluna).
View: Representa logicamente subconjuntos de dados de uma ou mais tabelas
Sequência: Gera valores de chave primária.
Índice: Melhora o desempenho de algumas consultas.
Sinônimo: Atribui nomes alternativos a objetos.
A mais importante definitivamente é a Tabela.

--Convenções para uma tabela: 
-Deve começar com uma letra
-Pode ter de 1 a 30 caracteres
-Deve conter somente A-Z, a-z, 0-9, _, $ e #
-Não deve duplicar o nome de outro objeto (dois objetos não podem ter nomes iguais)
-Não deve usar palavra registrada
Se criar uma tabela com seu usuário, apenas o usuário a verá!!

Alguns comandos
-Mostra os bancos: Show databases;
-Para criar um banco de dados o comando é: create database nome;
-Para ir para o banco desejado: Use nome;
-Para mostrar as tabelas do banco: show tables;
-Para mostra qual o banco de dados aberto: status;
-Para mostrar uma tabela: describe nomeTabela;
-Para apagar o banco de dados: drop database nome;
-Para apagar a tabela: drop table nome;
-Para criar uma tabela o comando é: create table nome (        );
**Para criar uma tabela precisa ter permissão e ter espaço no disco.
Precisa especificar o nome da tabela, os nomes das colunas, os tipos de dados das colunas e os tamanhos das colunas.
**Dentro dos parênteses estarão os campos, sendo organizados em nome e tipo primitivo. SERÃO DIVIDIDOS COM , !!!
Nome tipo,
Se quiser definir a quantidade que irá guardar previamente terá que por como parâmetro
Nome varchar(30),
--Se quiser criar uma tabela mesmo estando fora de um banco, precisa ser especificado o nome do banco ao cria-lá:
Create table nometabela nomeBanco.nomeTabela
--Para criar o nome dos campos da tabela sempre usamos uma junção do campo e da tabela. Por exemplo, se eu quiser criar uma tabela departamento em um banco de dados de uma empresa, eu criaria um atributo como numero_departamento, nome_departamento, etc. 

***Se criar uma tabela com seu usuário, apenas o usuário a verá!! Pois as tabelas que pertencem a outros usuários não estão visíveis para outros.
Por isso é necessário usar o nome do proprietário como um prefixo da tabela

---Criando uma tabela a partir de subconsulta:
 

Tipos de dados
---Os tipos primitivos do mysql separam as coisas em algumas famílias, como:
-Numéricos: Se dividem em:
Inteiros: TinyInt, SmallInt, Int, MediumInt e BigInt (Separados pela quantidade de bytes na ordem crescente).
Reais: Decimal, Float, Double e Real
Lógicos: Bit e Boolean
-Data e tempo: Date(somente uma data), DateTime e TimeStamp (data horas e mais coisas), Time (somente hora) e Year (somente ano).
-Literal: Se dividem em:
Caractere(Para textos curtos): Char (fixo) e VarChar (variante).
Texto(Para textos longos): TinyText, Text, MediumText e LongText 
Binário(Pode ser salvo qualquer informação): TinyBlob, Blob, MediumBlob, LongBlob 
Coleção(Para configurar os valores permitidos): Enum, Set
-Espacial(Coisas Volumétricas):  Geometry, Point, Polygon, MultiPolygon
 
 
Se quiser definir a quantidade que irá guardar previamente terá que por como parâmetro
Nome varchar(30)
--Para alterar uma tabela:
-Alter table nomeTabela (Vai ser o padrão para chamar a tabela para alterar)
-Add column nomeCampo tipoCampo; (Adiciona um novo campo)
-Drop column nomeCampo; (Remove um campo)
-Add column nomeCampo tipoCampo after nomeCampo; (adiciona um novo campo depois de um nome específico)
-Add column nomeCampo tipoCampo first; (Adiciona um novo campo na primeira posição)
-Modify column nomeCampo tipoCampo; (Muda o tipo do campo ou as constrains dele)
-Change column nomeAntigo novoNome tipoCampo (Muda o nome do campo)
-Rename to novoNome; (Muda o nome da tabela)
 
--Como alterar uma coisa específica na sua linha:
Update nomeTabela
Set nomeCampo = ‘novoNome’
Where nomePrimaryKey = ‘primary key desejada’
Limit 1; (limita o total de linhas que irá mudar)

---Campos com informação padrão:
 
Default ‘alguma coisa’ = significa que se ninguém digitar nada naquele campo, ele será ‘alguma coisa’ por padrão. A palavra entre ‘’ define o padrão do campo.
Uma alteração no valor padrão não alterará os registros passados, apenas os futuros.
Quando eu insiro um registro na minha tabela que determinada coluna não for preenchida, o valor inserido será o “Padrão”
Esse padrão definimos nas colunas da nossa tabela (o padrão é null)

Restrições/Constrains
Regras aplicadas nas colunas de uma tabela usadas para limitar os tipos de dados inseridos. Podem ser especificadas na hora de criar a tabela ou depois alterando ela. 
As restrições também evitam que uma tabela seja deletada se houver dependências. Podem ser criadas a nível de uma tabela ou de colunas.
Uma restrição pode ser adicionada, alterada e deletada.
 
Not null = Significa que você vai ter que preencher aquele dado. São obrigatoriamente digitáveis. Assegura que os valores nullos não sejam permitidos para a coluna. É somente a nível de coluna.
Unique Key = Será único (Não pode repetir). Não permite valores duplicados na tabela. Pode ser feita a nível de coluna ou tabela.
Primary key (chave primária) = Ela é obrigatoriamente not null e unique key. Usado para identificar os registros, geralmente é um valor inteiro.
 São campos únicos para cada entidade. Por exemplo, duas pessoas podem ter nomes iguais, mas um cpf nunca irá ser igual a outro. Por isso usamos essas chaves.
Podem ser definidas a nível de coluna ou tabela. Se as informações dependerem de duas ou mais colunas para a primary key ela pode ser definida a nível de tabela.
Todas as tabelas tem primare key!
Foreign Key (chave estrangeira) = A forma de relacionar uma tabela com outra através das chaves primárias.
 É uma restrição que indica que a coluna está ligada com uma chave primária de outra tabela.  Aponta para um valor que em outra tabela é uma chave primária.
 
Uma convenção para criar uma foreign key é sempre usar no nome: FK_tabela que sai a foreign key_tabela que a foreign key aponta.

Sempre que a chave primária da qual a chave estrangeira aponta é deletada ou é alterada (delet ou uptade) cria uma inconsistência, por isso, elas tem padrões para a solução desse problema:
Restrict: Quando a foreign key é restrita o banco não deixa apagar ou alterar a primary key, o programa não deixa. (Pois criaria uma inconsistência)
Cascade: Quando a foreign key é de cascata, as informações mudadas na chave primária passam para os outros. Se altera, altera os outros. Se deleta, deleta os registros também. Propaga as informações para outra tabela.
Set null: Quando a foreign key é set null, quando acontecem mudanças na chave primária ela define a foreign key como nulo. (Porém a coluna da foreign key não pode set not null!!)
Tem que ser definidos tanto para on delet (quando deletar) e para on update (quando alterar). Podem ser diferentes!!

Agregação: Duas tabelas ligadas, porém independentes.
Composição: Duas tabelas ligadas, porém dependentes.
********Até agora foram todos comandos DDL!*********

Manipulação de dados - DML
Responsável por inserir, alterar e apagar informações de linhas de uma tabela. Apenas meche com contéudo. 
*Cada linha é chamada de registro e é um objeto diferente.

--Para inserir dados na tabela:
Insert into nomeTabela
(campo, campo, campo, campo)
values
(‘nome’, ‘nome’, ‘nome’, ‘nome’);
Se os valores que você inserir forem exatamente na mesma ordem e tiver a mesma quantidade que os campos foram definidos não precia informar os campos na hora de inserir
 
Desta forma é inserido apenas uma linha por vez.
---Inserindo linhas com valores nulos:
Tem o modo implícito, que você não informa o valor, omitindo a informação.
Tem o modo explícito, especificando a palavra-chave NULL no lugar do valor.

--AUTO_INCREMENT
Permite que um número seja gerado quando um novo registro é inserido em uma tabela. O padrão inicial é 1 e se encrementa de 1 em 1. Para que ele começe em um valor diferente use: AUTO_INCREMENT = valor
Pode ter apenas um valor de auto increment na tabela e não é necessário especificá-lo ao inserir informações pois é automático.
Geralmente é do tipo inteiro e necessida da constraint NOT NULL

---DATA
Para definir uma data como a data de hoje use now() quando definir seu valor.

--Como alterar uma coisa específica na sua linha:
Usamos para atualizar linhas existentes na nossa tabela.
 
Update nomeTabela
Set nomeCampo = ‘novoNome’
Where nomePrimaryKey = ‘primary key desejada’
Limit 1; (limita o total de linhas que irá mudar)

Use o where para identificar onde você quer mudar esta informação e o limit para quantas linhas irá afetas.
 

--Como apagar uma linha:
Delet from nomeTabela
Where nomePrimaryKey = ‘primary key desejada’
 
Se você omitir o where, todos os registros da tabela serão apagados.
--Como apagar todos os registros da tabela:
Truncate nomeTabela;
---Commit
 
---Rollback
 
====================ERROS========================
 
 

--Como mostrar uma tabela
Describe nomeTabela (serve para ver a estrutura, os campos e seus tipos)
Select - DQL
Select * from tabela (Serve para ver os registros de uma tabela)
O * significa “todas as colunas”.
Select nome_coluna, nome_coluna from tabela (Serve para mostrar apenas as colunas desejadas de uma tabela e seus registros)
Para renomear as colunas na hora de mostrar (e apenas na hora de mostrar, não alterando seu nome real) damos um “apelido” a coluna com o objetivo de ficar mais legivel. Para isso usamos: Select nome_coluna as apelido from tabela;	
Para limitar a quantidade de linhas desejadas, devemos impor uma condição usando o where

-----Where
É usado com todos os operadores relacionais, sendo:
= (igual), <> (diferente), O resto é igua a java.
In: compara se determinada(s) coisa(s) está em uma lista
 
Like: Serve para ver todos os registros da coluna que começam com uma informação específica (o resto não importa). Usamos:
Select nome_coluna from tabela where nome_coluna like “informação%”
Também tem como ver todos os registros que terminam com essa informação, botando o % antes. Também é possível ver se existe no meio! Utilizando %informação%
Para pularmos uma quantidade específica de caracteres, usamos o _ nos caracteres que quero pular invés do % (Que é indefinido)

Is: Usamos para null e not null. Para retornar os que são nulos e os que não são.

-O operador lógico E (&&) é representado por and, que tem a mesma função que java.
-O operador lógico OU (||) é representado por or, que tem a mesma função que java.
-O operador lógico NOT(!) é representado por not, que tem a mesma função que java.

Between: Um valor maior que alguma coisa e menor que outra coisa. 
Exemplo: between 2000 and 3000.
Os limites também serão incluídos!

--Ordem de precedência: Parênteses (), operadores de comparação, not, and e or. 

----Order by: Especifica a ordem que quero mostrar na tela. Vai ordenar os registros das colunas.
Order by nome; informa os nomes em ordem alfabética.
Order by nome desc; informa a ordem descendente.
A coluna usada para ordenar não precisa estar no select.

Agregação de dados
Obter uma informação no banco de forma pulverizada e calcular outra informação. Por exemplo, calcular uma média dos salários guardados no banco.

---Funções de grupo: Funções que operam em várias linhas agrupando para gerar um resultado. 
AVG (coluna): Média. (Usado para dados numéricos).
Select avg(coluna) from tabela;

COUNT (*): Retorna o número de linhas de determinada tabela.
Select count(*) from tabela;
-Para contar coisas que tem uma coluna preenchida usamos count(coluna).

MAX (coluna): Valor máximo. (Qualquer tipo de dado).
Select max(coluna) from tabela;

MIN (coluna): Valor mínimo. (Qualquer tipo de dado).
Select min(coluna) from tabela;

SUM (coluna): Somatório. (Usado para dados numéricos).
Select sum(coluna) from tabela;
 
A função de grupo vem sempre junto da coluna. Posso usar um apelido para uma função de grupo. Posso usar where para restringir.
As funções de grupo sempre ignoram os valores nulos.
É possível usar uma função de grupo dentro de outra função de grupo.
------Grupos de dados (Group by)
Serve para agrupar linhas de uma tabela em grupos menores
 
-Todas as colunas no select que não sejam uma função do grupo tem que estar no group by.
Porém, se algo está no select não necessariamente precisa estar em cima.
 

-É possível ordenar por funções de grupo!! Também é possível usar funções de grupo no where.
-Para agrupar mais de uma coluna, insira uma “,” no group by.
-O where é usado para restringir a tabela e não para restringir grupos. Por isso ele sempre irá antes do group by.

-Para primeiro agrupar e depois restringir usamos o HAVING:
É uma condição de grupo. (Usamos o having para restringir agrupamentos)
 

Ordem final
 
Subconsulta

Pense na pergunta: “Quem funcionários têm o maior salário que o salário de Jones?”. Percebe-se que primeiramente é preciso saber quanto o Jones ganha para depois comparar quem tem os maiores salários.
Para isso é preciso fazer uma subconsulta(salário do Jones), para usar o retorno na consulta principal (Pessoas com maior salário que Jones).
Tem como usar funções de grupo em uma subconsulta!
É possível ter uma subconsulta no from.
A utilidade mais importante das subconsultas é fazer consultas baseadas em valores desconhecidos.
-Três tipos:
 

--Retorna uma única linha
 
Subconsultas de uma coluna sempre estarão entre parênteses e no lado direito do operador de comparação.
Não adicione order by a uma subconsulta.
Use apenas operadores de uma única linha com subconsultas de uma única linha.
Operadores de uma subconsulta de uma única linha: >,<, >=, <=, <>, =.

--Retorna várias linhas
Operadores de comparação de várias linhas:
IN: compara se é igual a qualquer membro na lista.
ANY: Compare o valor a cada valor retornado pela subconsulta. (parecido com o ou). Exemplo: É maior que x ou maior que x...
ALL: Compara o valor a todo valor retornado pela subconsulta. (parecido com o e). Exemplo: É maior que x e maior que x
EXEMPLO: Qual o nome e o salário de todos os empregados onde o salário vai ser menor que qualquer empregado que começou a trabalhar na empresa entre 1990 e 2010
--Retorna várias colunas
Usa-se o IN.
 

--Como exibir dados de mais de uma tabela.

JOIN - junção
Use uma junção para consultar dados a partir de uma ou mais tabelas.
Quando for usar o join sempre terá que ser usado com uma condição de junção. Uma condição de junção é quando uma linha está ligada a um registro de outra tabela. É a informação é usada para juntar essas tabelas.
Cria-se uma condição de junção no WHERE.
 
Use uma junção para consultar dados a partir de uma ou mais tabelas.
Quando o join não ter uma condição de junção ele sempre gerará um produto cartesiano. Um produto cartesiano se baseia em uma combinação de todos os elementos de uma tabela com os elementos de outra tabela.
Um produto cartesiano é formado quando: Uma condição de junção estiver omitida, quando a condição de junção estiver inválida e quando todas as linhas na primeiras tabelas estão unidas a todas as linhas da segunda tabela.
Para evitar sempre use uma condição de junção válida no where.

------Junção idêntica (Inner join) *O mais usado! *
A consulta é feita pelos valores idênticos nas determinadas tabelas. Só vai retornar o que está em um e no outro, não irá retornar o nulo. O inner join irá retornar sempre o que está no meio das tabelas!
É ligado de chave estrangeira a chave primária.
-Quando um join é feito com várias tabelas é preciso identificar de que tabela determinada coluna veio.
-Para isso usamos: tabela.nomeColuna
Select tabela1.nomeColuna, tabela2.nomeColuna from tabela1
Inner join tabela2
On tabela1.nomeColuna = tabela2.nomeColuna
O on serve para identificar a condição de junção.
------Left join
Irá retornar todas as informações da tabela da esquerda e as informações que estão no meio da junção. Se você escrever o JOIN sozinho, sem especificar, é left por padrão.
------Right join
Irá retornar todas as informações da junção e da tabela a direita.
------Outer join
Pega a diferença da junção. O que não está nas duas.
------Full join
Mostra tudo, o que está na junção e nas duas tabelas.
------Self join

 

Conectar o java com o banco
O conjunto de classes para ligar o java com o banco é o JDBC (Que o próprio java que gerencia). É um conjunto de códigos de consulta que irá mexer no banco. Ele serve para qualquer tipo de banco.
Quem faz o meio termo entre o JDBC e o banco é o Driver. É um conjunto de código responsável por fazer esse meio termo. O Driver tem que ser específico do seu banco.
--------------------MAVEN: Ferramenta para fazer a gestão da dependência e fazer o build(processo de compilação)
Arquétipos: Templates de configuração.
O maven trabalha com artefatos, um projeto será um artefato que poderá ser compartilhado.
-Para criar: Maven project
-Group id: Organização ou empresa que aquilo pertence.
-Artifact id: Nome do projeto
----Versionamento semântico:
  
O patch aumenta com a correção de bugs ou melhorias de código simples (correção). O Minor significa funcionalidades novas, atualizações grandes. O major é onde muda muito a estrutura do projeto, onde ele é reformulado e pode gerar problemas para quem não atualizar esta versão.
POM: Outro padrão de projeto, é a parte mais importante do projeto maven e é nele que vai ficar toda a informação do projeto.
Muitas vezes o projeto maven tem dependências de terceiros. Para isso adicionamos dependências para o projeto.
Após adicionar as dependências, quando rodarmos o projeto precisará instalar essas dependências. Para isso clique com o botão direito, vá em run as e clique em maven install. (Isso só precisa ser feito na primeira vez)
DAO: Serve para criar uma camada de abstração entre a fonte dos dados e quem está usando os dados. O DAO é como se fosse uma interface. Ele diz que métodos poderão ser executados no banco. O dao serve para o programa não acessar o banco diretamente, mas ter um meio termo entre eles que ajuda na molaridade do programa, já que o modal pode ser substituído dependendo da fonte do banco.
Cada entidade terá um DAO! Cria-se uma interface com o nome da classe+DAO. Nessa interface terão que ter todos os métodos para manipular todos os dados do banco.
Os métodos sendo: void nomeMétodo (Objeto objeto);
Os métodos de consulta(select) também estarão no DAO.
A classe que irá implementar a classeDAO é a classeDAOImpl. Ela irá dizer como esses métodos irão gerenciar o banco.
O DAO não meche com estrutura do banco, apenas com os registros.

JDBC
Ela está dentro da java.sql
A classe Connection (java.sql.Connection) serve para iniciar a conexão com o banco.
É preciso criar um método privado para conectar ao banco e devolver uma conexão.
Private Connection conectarBanco() throws SQLException {
Return DriverManager.getConnection(“jdbc:mysql://localhost/cadastro? user=admin&password=password”);
}
O local host serve para conectar com um banco na sua máquina, o “cadastro” é o nome do banco, o ? É os parâmetros para conectar, o user=admin significa que o user para acessar tem que ser “admin” e a mesma coisa para o password.
Se todas essas coisas forem verdadeiras (se existirem) ele irá retornar o objeto de conexão.
DriverManager: gerencia o drive.

--Método inserir um objeto.
Crie um método público, com retorno vazio e recebendo um objeto como parâmetro.
==============================================
Connection conexao = null
PreparedStatement insert = null;
Try {
conexao = conectarBanco();
insert = conexao.prepareStatement(“INSERT INTO tabela (colunas) VALUES (?,?,?,?)”);
Insert.setString(1, classe.getColuna());
Insert.setString(2, classe.getColuna());
Insert.setString(3, classe.getColuna());
Insert.setString(4, classe.getColuna());

Insert.execute();
} catch(SQLException erro) {
Erro.printStackTrace();
}
Finally{
Try{
If(insert != null)
Insert close();
If(conexão != null)
Conexao.close();
} catch (SQLException erro) {
erro.printStackTrace();
}
===============================================
O statement é fixo (usado quando sempre será o mesmo texto, um select por exemplo), o preparedStatement é alterável (Ele irá receber informações de terceiros como parâmetro). 
Os ??? São os parâmetros
O finally dentro do try serve para fechar o preparedStament e a conexão. Sempre terá que ser fechado na ordem contrária que abriu.

--Para criar os outros métodos é a mesma estrutura, porém o “insert” será substituído pelo nome que a classe exerce(delet por exemplo).
--O select irá usar o Statement no lugar do preparedStatement. A estrura também será um pouco diferente. Após a criação da conexão será criado um ResultSet resultado = null;
NomeResultSet.next(): Analisa se ainda tem alguma linha para trabalhar após a linha que ele executou.
O resultSet também terá que ser fechado!
JPA
É uma especificação. Algo que diz o que algo deve fazer e não como fazer.
É uma implementação concreta dessa especificação, através de várias classes.
O programa manda informação para o DAO, o DAO usando o hybernate salva a informação no banco.
Uma anotação é colocar @ para informar qual atributo é qual. A jpa faz essas anotações, quem usa aquelas anotações para converter é o hybernate. Tem uma anotação pra herança e restrições como not null.
Toda entidade tem que importar serializable (import java.io.Serializable)
FetchType.LAZY retorna os atributos nulos!
Na relação chave estrangeira de um pra um, uma vai guardar a chave primaria de outra coisa e a outra não terá um ID.
GeneretionType.IDENTITY é o autoincremento para cada tabela.
Mapeamento 	um pra um, um pra muitos e muitos pra muitos.
CascadeType.ALL (deleta todos igual o cascade do banco)
OrphanRemoval = true
-Quando fazer herança, apenas a superclase terá um DAO
Front End.
Tá tudo aí, só saber inglês.
https://www.w3schools.com/html/default.asp

ANOTAÇÕES SENIOR – GODEV
Informações gerais
Contrato de 10 meses, iniciando dia 09/11/21 e com término em 08/09/22 (não pode mudar de escola nesse período!!).
Plataforma interna: Senior X
Manter dados atualizados em: Gestão de Pessoas > Painel de Gestão > Perfil > Meu Perfil
Vale Alimentação (VA)/Vale Refeição (VR): O cartão será entregue em até 7 dias úteis com o valor retroativo desde a admissão. A carga mensal é efetuada no último dia útil do mês. Valor diário de R$21 + incremento de R$200 por mês.
Convênio com farmácias: liberado a partir do mês seguinte da sua admissão. Limite de compras de R$100 por mês com desconto na folha de pagamento. Fornecedores: Catarinense, Sesi e Panvel.
Vale Transporte: Tem que ir até a blumob retirar o cartão em até 7 dias úteis pois será feita a carga (com valor retroativo). A carga é efetuada no último dia útil de cada mês.
O pagamento será realizado no 5º dia útil do mês.
O crachá oficial chegará em torno de 30 dias.
Marcação do Ponto: Será obrigatório o registro diário dos pontos (são 4 marcações diárias). Pode ser feito através do Senior X em Marcação de ponto 2.0 ou no aplicativo com o mesmo nome.
Caso o ponto não seja marcado por algum motivo, é necessário editar isso nos “Meus acertos de ponto” no Senior X com alguma justificativa.
As férias de fim de ano será de 27/12/2021 à 11/01/2021.
A folha de pagamento pode ser acessada pelo Senior X em “Meus demonstrativos de pagamento” ou no aplicativo Wiipo(inserindo CPF e número de telefone informado na admissão). Ela será disponibilizada assim que calculada, o aplicativo notifica quando disponível.
Time de Admissão da Matriz:
Bruna Cubas – Fernanda Quevedo – Luana Schimitt – Suelen Pacca e Evelyn Ribeiro e Luana Gnemwach(aprendizes).
Competências Convergentes que precisamos ter: Cliente no centro, Simplicidade, Orientado a resultados, Aprender Continuamente, Colaboração. Essas competências serão levadas em consideração para a efetivação, é necessário ter ou desenvolver elas para trabalhar na Senior. CLT tem avaliações sobre elas!
-Presidente: Carlênio Castelo Branco
-Diretor de Desenvolvimento: Carlos Valle
-Diretor de Serviços: Marcelo Martins
Em caso de atestado ou afastamento, ir no mesmo caminho que a gestão de pontos, porém ao invés de editar, clicar em “Inserir histórico de afastamento”.
Tem um sistema de feedback, onde você pode dar um feedback a outro colaborador em que só ele e o seu respectivo líder tem acesso (o colaborador que recebeu o feedback decide se ele ficará público ou apenas privado). Não é feito de forma anônima!
BPM: É o fluxo de benefícios. Onde você tem que ir para abrir uma solicitação de benefícios.
Universidade Corporativa Senior: Onde fica disponível cursos e trilhas de conteúdo para estudo. É possível acessar pelo Senior X, o login é o cpf e a primeira vez acessada também é o cpf, porém é necessário mudar a senha depois. Os cursos da UCS geram certificados e há provas no fim dos cursos (com 10 tentativas).
Soft Skills (são difíceis de mensurar): Relacionamento interpessoal, Comunicação, Liderança, Pensamento Crítico, Atitude, Criatividade, Empatia, Resolver Conflitos, Persuasão, Trabalho em Equipe e Saber OUVIR!
Cuidar com: Horários excessivos de intervalo, Saídas sem marcar pontos, Uso frequente do celular.
Venda: Não é permitida a venda de produtos dentro da empresa. Os alimentos por questões sanitárias e o resto por questões de pirataria. As vendas através do Classificados devem ser entregues na loja de entrega, mas fora do horário de trabalho.
A área de Sustentação corrige os bugs das demandas antigas, do sistema pronto que está em mercado. A área de Desenvolvimento recebe demandas novas e produz novas funções no programa conforme a demanda.
Java Básico
A linguagem foi criada em 1990 pela Sun Microsystems. Inicialmente foi desenvolvida para funcionar em processadores de eletrodomésticos. Suas características são herdadas dp C e C++ e ganhou destaque pelo seu surgimento WEB. O Java ganhou respeito a partir da versão 1.3 e 1.4 e foi adquirida pela Oracle em 2009. Pode ser utilizado para desenvolvimento de aplicações Desktop, mobile e Web.
O compilador Java é o JavaC, transforma a linguagem de alto nível para bytecode (uma linguagem intermediária). Qualquer computador com uma JVM (máquina virtual que lê o bytecode) irá rodar o programa sem problemas.
É uma linguagem fortemente tipada e case-sensitive. Possui um garbage collection e é orientada a objetos.
Palavras reservadas do Java (não podem ser usadas em nomes de atributos e métodos):
 
Dica: No eclipse as palavras reservadas ficam com uma cor diferente (com um rosa no padrão branco).	
Métodos de formatação de String:
 

 
 
IF ternário:
  
Static
Um método ou atributo estático(static) pertence à própria classe.
Um método ou atributo estático não precisa ser instanciado, basta chamar pelo nome da classe.
 
Por exemplo, na primeira linha das imagens, o método main é estático e pode ser chamado através do Exemplo.main, sem precisar ser instanciado. 
No segundo exemplo com o main não estático, seria preciso criar uma instancia de exemplo com “Exemplo e = new Exemplo();” e aí sim usar aquele método com o novo objeto criado, ficando e.main.
Uma classe não pode ser estática.
--> DecimalFormat: Necessário criar uma instância dela e passar a formatação do número. Exemplo:
 
-> Instanceof: usado normalmente para lançar o tipo de usuário para login. Permite testar se um objeto é uma instância de um tipo específico de class, subclasse ou interface.

DICA PARA HERANÇA E COMPOSIÇÃO:
 
-> Collections.sort ordena os arrays.

Coisas para estudar
Java 8+  Language Features
-Anotations
-Operators
-HashMap, HashCode, HashSet
-Documentações Java
-Apache Utilitys
-Logging
Git
-Rebase
-Cherry pick
-Bisect
Rest & WEB content
-curl
-Swagger
-Postman
Spring
-Spring REST
-Spring Boot
-Spring Core
-Dependency Injection
-Inversion of control
Docker
-Container, Container com um jar executável
-Volumes
Banco de Dados
-DDL E DML
-Constrains
-Normalização
-Sequences
-Indices
-Postgres
-Dbeaver
JPA – Hibernate e QueryDSL
-Repositories
-Entity
-Filters
-CustomRepository
-Validators
JUnit
-Criação de Testes Unitários
-Mocks(Mockito)
Angular 2+
-Typescritp
-Webpack(Lint, Custom Styles, angular.json)
-Componentização
-Subjects vs Observables
-Stores(Akita)
-Teste Unitário

HashMap, HashSet e HashCode
-> HashMap
HashMap é utilizado normalmente nos cadastros para garantir que não há dados iguais sendo cadastrados. Trabalha com o conceito de key-value pairs, ou seja, cada elemento de sua lista possui uma chave e valor associado, assim podemos realizar uma busca rápida pela chave que desejamos, sem precisar percorrer toda lista ou saber o index/posição que desejamos consultar. É como se fosse o id no banco de dados.
Ele implementa Map e é feito dessa forma: T<K,V>
Com o HashMap e Generics podemos especificamente dizer qual o tipo da nossa chave (string, int, double e etc) e o tipo do nosso valor, que obviamente podem diferir sem problema algum.
A capacidade padrão do HashMap é 16 e pode ser instanciado com mais ou menos posições. Exemplo:
Map<String,String> example = new HashMap<String,String>();
example.put( "K1", new String( "V1" ));
-> Usamos o método put() para inserir um novo par de elementos em nossa lista;
-> containsKey: irá procurar por uma chave dentro da tabela
 	String keyToSearch = "K1";
if ( example.containsKey( keyToSearch ) ) {      
System.out.println("Valor da Chave " + keyToSearch+ " = " + example.get(keyToSearch));       	        
}else { 
System.err.println("Chave não existe");       	    
   }

Generics
 
Criando uma classe genérica podemos definir um valor para ela na hora que instanciamos no main. No exemplo acima, o T será o símbolo da nossa classe genérica. O Generics não aceita tipo primitivo. Os atributos e métodos que terão valor T, também serão definidos após a instância.
A letra não precisa ser obrigatoriamente T, pode ser qualquer outra, porém os atributos e os métodos terão que seguir o mesmo padrão.

Datas
 
Formatação:
 
-> Usado o localDate aqui.

Threads
Threads é uma subrotina que roda ao mesmo tempo que seu programa. Normalmente usada para testes. Em um programa em Java podemos querer executar 2 ou mais threads ao mesmo tempo, ou seja, 2 ou mais procedimentos internos do programa ao mesmo tempo. As Threads são essênciais no nosso programa para melhorar o desempenho, considerando que há métodos mais simples que muitas vezes não dependem do usuário e podem acabar atrasando o programa principal com sua execução. A solução então é fazer com que esse procedimento seja executado ao mesmo tempo em que o usuário está realizando o cadastro.
Caminho de uma thread:
 
Ela é uma classe e estende de Thread.
 
Java 8+  /  Language Features – Jonathan Pavanello
-> Na versão 1.5 do Java que chegou as Generics. Na versão 1.7 a Oracle comprou o Java, porém ainda deixou ser gratuito. 
-> Quando for usar APIS ou meio externos para programação, verificar se essa API continuará a ter o desenvolvimento ou se terá correção de Bug. Caso a API não seja mais utilizável e você tiver implementado ela no seu programa, o prejuízo de reformulação e desenvolvimento perdido do projeto é grande demais. Use coisas que tem CERTEZA que terá SUPORTE e que seja ESTÁVEL!! 
-> A senior usa uma OpenJDK, muda um pouco em relação a Oracle, mas a base é a mesma. 
-> Toda vez que sair uma versão nova, é necessário estudar essa nova Versão (caso for utilizada no seu programa), para fins mais performáticos. 
-> Swing é a interface gráfica do Java.
-> Programar para interface e não com implementação.
-> Jeito de formatar string:
 ALT SHIFT L --> Clicar após selecionar um texto, ele dá a opção de renomear todos desse texto na classe.
-> Padrão de formatação de fonte é importante para trabalhar em equipe!!!
 
 
-> Apache Commons: utilitários ->IO utilites
-> Tem como fazer um .jar executável!!
 
-> No Java foi implementado uma função parecida com as variáveis do javascript, que as variáveis só são declaradas o seu tipo quando atribuímos algo para ela (no Java quando inicializamos a variável temos que pôr o tipo).  Para isso usamos o var antes da variável.
-> Sonarqube: ajuda a gerenciar seu código. Ele verifica bugs (analisa o que eu programei e se pode gerar possíveis bugs). Mostra os códigos duplicados e faz um tipo de teste com os métodos de cálculos.

Exceções
Praticas ruins no tratamento de exceção:
 
 
 
 
 
 

LOGGING
Logs são necessários para monitoramento e solução de problemas. Algumas ferramentas são: SLF4J (framework), LOG4J(apache), LOGBack, JAVA UTIL LOGGING (nativo do Java). Exemplos de logs da senior:
 
Como usar o logging
 
Níveis de Logging:
 
Piores Práticas de Logging:
-> Não deixe extremamente genérico!
 
Exemplo de configuração do Logging: 
 

 
-> Uma forma de, se o produto já tiver cadastrado na lista, adicionar +1 a quantidade dele. 

Debug
-> Nas expressões do debug, posso fazer um pequeno método com uma variável para fazer verificações.
 
->Na área de debug Shell também da para fazer pequenos métodos ou até programas para visualizar o funcionamento do programa, para executar é necessário clicar cntrl D. Após isso ele imprimirá o valor da função pedida na tela. No debug Shell também é possível alterar os valores em tempo de debug:
 
-> É possível fazer um breakpoint condicional, por exemplo, dentro de um foreach, quando determinado valor for 5 ele para.
->É possível verificar as linhas de código quando debuga, quando elas estão verdes, selecione a linha e aperte CNTRL SHIFT i
 
->CONTRL / comenta e descomenta o código selecionado.
->BigDecimal: Quando temos valores monetários.
É um objeto especialista em valores monetários, tem sistema de arredondamento, formatação
Add (incrementa/adiciona um valor)
Divide (divide)
RoudingMode.HALF_EVEN (arredonda o valor)
 

STREAMS
STREAMS é uma API com vários métodos e funções com o objetivo de reduzir o código. Elas funcionam com Arrays. Algumas funções:
count - Retorna a quantidade de elementos presentes em uma stream. Mas se você tem uma lista prefira clientes.size(). Exemplo: clientes.stream().count();
limit - Retorna uma nova stream que contém apenas os N primeiros elementos da stream original. Ex: limit(10);
skip - Retorna uma nova stream que não contém os N primeiros elementos da stream original. Ex: skip(10);
sorted - Retorna uma nova stream contendo os elementos da stream original ordenados pela forma natural em ordem crescente. 
E assim vai. Outros métodos: https://medium.com/@racc.costa/streams-no-java-8-e-no-java-9-36177c5c3313
Alguns exemplos: https://imasters.com.br/desenvolvimento/streams-e-lambdas-em-java
Documentação: https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html
Optionals
Surgiram para evitar nullPointerExceptions e antes de tentar obter algo, podemos validar se realmente existe. A principal proposta deste recurso é encapsular o retorno de métodos e informar se um valor do tipo <T> está presente ou ausente. Para que usá-lo:
•	Evitar erros NullPointerException.
•	Parar de fazer verificações de valor nulo do tipo if (cliente != null).
•	Escrever código mais limpo e elegante.
Alguns métodos:
empty - Retorna uma instância de Optional vazia. Exemplo:
Optional<Cliente> retorno = Optional.empty();
of - Retorna um Optional com o valor fornecido, mas o valor não pode ser nulo. Se não tiver certeza de que o valor não é nulo use Optional.ofNullable. Exemplo:
Optional<Cliente> retorno = Optional.of(buscaCliente(cpf));
ofNullable  - Se um valor estiver presente, retorna um Optional com o valor , caso contrário, retorna um Optional vazio. Este é um dos métodos mais indicados para criar um Optional.
filter - Se um valor estiver presente e o valor corresponder ao predicado retorna um Optional com o valor, se não, retorna um Optional vazio. Exemplo:
Optional<Cliente> retorno = buscaCliente(cpf)
.filter(cliente -> !cliente.getNome().isEmpty());
isPresent - Se um valor estiver presente retorna true, se não, retorna false. Exemplo:
Outros métodos e exemplos: https://medium.com/@racc.costa/optional-no-java-8-e-no-java-9-7c52c4b797f1
Documentação: https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html

Interface Funcional
Uma interface é chamada de funcional quando ela apresenta um único método abstrato, ou seja, a classe que herdar essa interface irá herdar esse método. Apesar de poder ter apenas um método abstrato, ela pode ter vários métodos default, que já terão uma implementação padrão. O compilador reconhece essas interfaces e permite que elas estejam disponíveis para que os desenvolvedores trabalhem, por exemplo, com expressões lambda.
Supplier
 
A letra T significa que é genérica (genérico significa que pode ser de qualquer tipo), e neste caso significa que a operação get( ), quando executada, vai devolver algo para nós e pode ser de qualquer tipo. Por outro lado, não precisamos passar um argumento. Em resumo, chamamos isso e recebemos algo - como um fornecedor(Supplier). O generate() é um exemplo.
 Stream.generate(() -> new Random().nextInt()) (gera um Int aleatório).
Documentação:https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html
Consummer
 
É uma interface simples, o oposto de Supplier. Ela recebe uma variável genérica, faz algo com ela e depois, não devolve nada. O .forEach() é um exemplo.
Documentação:https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html
Predicate
 
A classe Predicado tem um método chamado teste, que recebe um argumento, e retorna um booleano. Este método é utilizado para validar hipóteses. O .filter() é um exemplo.
Documentação: https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html
 
Lambdas
As expressões Lambdas vieram no Java após o sucesso da Programação Funcional com linguagens como JavaScript ou Python. A principal vantagem das funções lambdas no Java 8 foi permitir o uso de Streams. Sem elas seria praticamente impossível utilizar Streams com facilidade. Uma função lambda é uma função sem declaração, isto é, não é necessário colocar um nome, um tipo de retorno e o modificador de acesso. A ideia é que o método seja declarado no mesmo lugar em que será usado. As funções lambda em Java tem a sintaxe definida como (argumento) -> (corpo).
 
Pode ter nenhum ou vários parâmetros e seus tipos podem ser colocados ou podem ser omitidos. Pode ter nenhum ou vários comandos: se a mesma tiver apenas um comando as chaves, não são obrigatórias e a função retorna o valor calculado na expressão; se a função tiver vários comandos, é necessário colocar as chaves e também o comando return. Exemplo de uso no caso de listar os elementos de uma lista:
Sem Lambda:
 
Com Lambda:
 

Annotations
Site que o professor passou: https://www.baeldung.com/java-custom-annotation
Anotações são modificadores que podem ser aplicados a pacotes, declarações de tipos, construtores, métodos, campos, parâmetros e variáveis. Elas vieram para atender a demanda de anotar campos, métodos e classes, os quais devem ter atributos particulares que indicam que eles devem ser processados de forma especial por ferramentas de desenvolvimento, de implantação, ou bibliotecas runtime. O parágrafo da especificação conclui que tais anotações são chamadas metadados.
A utilização mais comum de metadados é na documentação de código. Entretanto elas podem ser empregadas como informação para o compilador, para utilização em testes de unidade ferramentas de persistência, a exemplo do Hibernate, e de análise de código, tal como o Findbugs.
