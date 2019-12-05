## Função Main

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

Restante do código 
...

```

  

