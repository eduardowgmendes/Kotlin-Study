## Variáveis 
Kotlin usa duas palavras reservadas diferentes para declaração de variáveis: `val` e `var`

### `val`
Use `val` para variáveis constantes e imutáveis que não podem receber nenhum valor após a atribuição inicial. 

```kotlin 
val pi : Double = 3.151692
 
pi = 5.14 // It's not compile

```  

### `var`
Use `var` para variáveis comuns.

```kotlin
var firstName : String = "Eduardo"

firstName = "Richard"

```

## Inferência de Tipo
A abordagem de Kotlin à inferência de tipos fornece concisão e segurança de tipos. Sendo assim é possível omitir na declaração de uma varíavel o seu tipo como no seguinte exemplo: 

```kotlin 

var firstName = "Eduardo"

```
Note que não foi declarado nenhum tipo de forma explícita e isso é válido pois o compilador verifica o tipo do valor que foi atribuído à variável e com base nesse tipo ele concluí que se trata de uma String.     

