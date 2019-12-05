## Conceitos iniciais

Segundo o Google o Kotlin é uma linguagem de programação moderna e modelada estaticamente que aumentará sua produtividade e sua satisfação como desenvolvedor. 

## Vantagens da linguagem 

### Moderno e expressivo
Os recursos modernos da linguagem Kotlin permitem que você se concentre em expressar suas ideias e escrever menos código clichê (*boilerplate code*). Dessa forma, também haverá menos código para testar e fazer manutenção.

### Código mais seguro 
Melhore a qualidade do seu app com o Kotlin. Os tipos `@Nullable` e `@NonNull` são integrados ao sistema de tipos do Kotlin para ajudar você a evitar *NullPointerExceptions*. O Kotlin também conta com muitos outros recursos de linguagem para ajudar a evitar erros comuns de programação. 

### Interoperável 
Chame código baseado em Java com o Kotlin ou chame o Kotlin com código baseado em Java. O Kotlin é completamente interoperável com a linguagem de programação Java. Portanto, é possível ter o quanto de Kotlin que você quiser no seu projeto. 

## Desenvolvimento Android Otimizado para Kotlin
O Kotlin é voltado ao desenvolvimento de apps para Android.

### Android Studio
O Android Studio oferece suporte de alto nível a Kotlin. Além disso, ele possui ferramentas integradas que ajudam a converter código baseado em Java para Kotlin. A ferramenta Show Kotlin Bytecode permite que você veja o código baseado em Java equivalente à medida que aprende Kotlin. 

### Android KTX
O Android KTX torna o desenvolvimento do Android com o Kotlin mais conciso, agradável e idiomático aproveitando os recursos da linguagem Kotlin. 

### SDK otimizado para Kotlin
A partir do Android 9 (nível 28 da API), o Android SDK contém anotações de anulação para ajudar a evitar NullPointerExceptions. A documentação de referência da API também está disponível em Kotlin. 
 
## Como é o código Kotlin?

![Code Sample Kotlin](https://raw.githubusercontent.com/eduardowgmendes/Kotlin-Study/master/images/code-sample-large.png)

## O Kotlin é gratuito e aberto 
O Kotlin é um projeto de código aberto e gratuito da licença do Apache 2.0. O desenvolvimento e distribuição como software gratuito são garantidos pela Fundação Kotlin. A escolha do Kotlin reafirma nosso compromisso com um ecossistema de desenvolvimento aberto à medida que expandimos a plataforma Android. Além disso, estamos ansiosos para ver a linguagem evoluir. 

### JVM 
A linguagem Kotlin também faz uso da máquina virtual JVM que compila os arquivos com extensão .kt para bytecodes da mesma maneira que o Java.   

### Função Main
Assim como no Java o ponto de partida de uma aplicação escrita em Kotlin é a função `Main` que é que pode ser expressa da seguinte maneira: 

```kotlin
fun main(){
 //Main Function
}
```

Note que não é necessário usar um array de String como o parâmetro como no Java

```java
public static void main(String[] args){
 //Main function on Java 
}  
```

Em cada arquivo de código fonte somente uma função main pode existir o exemplo a seguir nem compilaria: 

```kotlin
var firstName = "Eduardo"
var lastName = "Mendes"

fun main(){
 println(firstName + " " + lastName);
}

fun main(){
 // It's not compile
}

//Remainder of code
...

```

  

