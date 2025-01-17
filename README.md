# Atividades da 2ª aula do curso de Java: criando a sua primeira aplicação

## Descrição
Este repositório é dedicado as atividades iniciais de Java, do curso de "Java: criando a sua primeira aplicação" feito na Alura. As atividades deste repositório estão relacionadas a prática do uso de variáveis, 
operadores de incremento, formatação e comparação de string, e resolução de atividade de lógica de programação em Java. 

## Detalhes técnicos
Para a realização dessas atividades foi utilizada a IDE Intellij. Não houve instalação de bibliotecas externas. A versão do Java utilizada nas atividades é: Java 21. 

## Pré-requisitos
Antes de executar os códigos Java presentes neste repositório, é necessário instalar o JDK (Java Development Kit).
O JDK é indispensável para compilar o código-fonte (.java) e gerar arquivos .class, que contêm os bytecodes essenciais para que a máquina execute o programa. O bytecode é uma linguagem intermediária compreendida pela Máquina Virtual Java (JVM), mas não diretamente pelos seres humanos. Essa conversão da linguagem Java para bytecode ocorre durante a compilação, por isso a instalação do JDK é imprescindível.

Caso este repositório já incluísse os arquivos .class gerados a partir do código-fonte, seria necessário apenas instalar o JRE (Java Runtime Environment). O JRE fornece o ambiente necessário para executar o bytecode, dispensando a necessidade de compilação. Da mesma forma, se o repositório contivesse um arquivo .jar (um executável Java), apenas a instalação do JRE seria suficiente.

Essas instalações, tanto do JDK quanto do JRE, são importantes porque incluem a Máquina Virtual Java (JVM), responsável por interpretar e executar o bytecode, garantindo a execução do programa Java.

**Link de instalação do JDK e JRE:**
1. JDK: https://www.oracle.com/br/java/technologies/downloads/
2. JRE: https://www.java.com/pt-BR/download/manual.jsp
   
*Importante: ao instalar o JDK escolha a versão com suporte, ela é identificada pela sigla LTS*

**Link de instalação do Intellij e tutorial de uso:**
1. Instalação: https://www.jetbrains.com/pt-br/idea/
2. Tutotrial de uso: https://www.youtube.com/watch?v=0_e9Egeyk2E

*Importante: ao instalar o Intellij escolha a edição community, ela é gratuita*

## Sobre os programas deste repositório:
1. **Variáveis:**
   - neste programa iniciamos o conhecimento de variáveis em Java, o significado de tipagem estática, o conhecimento da classe String, a formatação de String usando os métodos: *String.format() e .formatted(), e também aprendemos sobre o casting (conversão de tipos em Java);
2. **Operador de incremento:**
   - neste programa aprendemos sobre as diferenças entre o pré-incremento e o pós-incremento. Incremento em programação é a adição de mais 1 em um valor numérico. Quando fazemos um pré-incremento essa adição ocorre antes do valor da variável ser utilizado, e o pós-incremento essa adição ocorre depois do uso do valor da variável.
3. **Comparação de String:**
   - neste programa aprendemos sobre as diferenças entre equals e equalsIgnoreCase, ambos são métodos da classe String que servem para comparar o valor de uma String com outra String. A diferença entre eles está que o método equalsIgnoreCase ignora letras maiúsculas e minúsculas no momento da verificação de igualdade, enquanto que o equals leva em consideração as letras maiúsculas e minúsculas dando por diferente Strings que estejam letras distintas, por exemplo: "Java" seria diferente de "java".
4. **Conversão de temperatura:**
   - Escreva um programa que converta uma temperatura em graus Celsius para Fahrenheit. Utilize variáveis para representar os valores das temperaturas e imprima no console o valor convertido de Celsius para Fahrenheit. A fórmula para converter temperaturas de graus Celsius para Fahrenheit é: (temperatura * 1.8) + 32.

## Conteúdo estudado e aprendido com o desenvolvimento dessas atividades: 
1. Tipagem Estática;
2. Conversão de tipos (casting);
3. Métodos de formatação de String;
4. Incremento
5. Métodos de comparação de String;
6. Aplicação da lógica de programação para a conversão de temperatura
