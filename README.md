# Aula de Kotlin - Aula 1


## Tipos de váriaveis em kotlin

```Var => Váriavel que pode ser alterada```
    
```Val => Imutável```

## Tipos de dados numéricos

```

Byte: 1 byte   => 8 bits
Short: 2 bytes => 16 bits
Int: 4 bytes   => 32 bits
long: 8 bytes  => 64 bits

```

## Dados numéricos com casas decimais

```

Float: 4 bytes   => 32 bits

```

```

Double: 8 bytes  => 64 bits

```

### Convertendo int para double
```

valor.toDouble()

```

### Convertendo double para int
```

valor.toInt()

```

# Tipo Char
```

val letra: Char = 'B'

```

# String

```

/*
* O rato roeu
* a roupa do
* rei de Roma 
*/

val s1: String = "O rato roeu\na roupa do rei de \"Roma\"."
```

```
 val s2: String = """
    O rato roeu
    a roupa do
    rei de "Roma"
 """.trimIndent() -> corta os espaços em branco mais a esquerda do primeiro  caracter da string
```

# Kotlin - Aula 2 - Operadores

```
//Aritméticos

+ Adição
- Subtração
* Multiplicação
/ Divisão
% Módulo
```

```
//Relacionais
== Verifica igualdade entre valores
!= Verfica diferença entre valores
> Verifica se valor é maior
< Verifica se é menor
>= Verifica se valor é maior ou igual
<= inverso do anterior
```

```
//Lógico
&& Somente é verdadeiro se as duas premissas forem verdadeiras 
|| Apenas é falso se as duas premissas forem falsas
! Negação (inverte valores booleanos) !true => false !false => true
```

```
//Estrutura de seleção
If como uma expressão que retorna valores
val r = if(n % 2 == 0) { 
   "Par" 
}else {
   "Impar"
}
```

```
when
```
