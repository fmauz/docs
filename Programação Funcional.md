# Programação Funcional

`Em ciência da computação, programação funcional é um paradigma de programação que trata a computação como uma avaliação de funções matemáticas e que evita estados ou dados mutáveis. ` - Wikipédia

## Functions, functions, functions...

* Fist-Class Functions

As funções são tratadas como variáveis e isso permite passar as funções como argumento para outra função, envolver uma função por outra função e atribuir em uma variável.

```javascript
// Example 1
const say = console.log;
say("Hello!")

// Example 2 
const i18n = function (lang) {
    return function(name) {
        if(lang === 'pt-br'){
            return name.replace('Hello', `Ola`)
        } else {
            return name
        }
    }
}
const speaker = console.log
const translate = i18n('pt-br')
speaker(translate("Hello!"))
```

* Pure/Impure Functions

Funções onde o valor retornado é determinado pelas valores de entrada, não podendo alterar variáveis/estados/dados externos e deve retorna sempre o mesmo valor quando dado o mesmo input. Exemplo: 

```javascript
const pure = function(x){
	return x + 2
}
```

Se a função executasse outras ações antes de realizar a soma então ela seria uma Impure Function, Exemplo:

```javascript
const impure = function(x) {
	const y = x + 2
	console.log(y)
	return y;
}
```

* Closures



* High Order Functions



## Imutabilidade ?

**Constantes** invés de *variáveis*. Devido ao seu viés matemático, um número sempre será aquele valor, independente de onde esteja ou como está sendo usado. Se vc tem uma função `f(x) = x + 2`, você pode passar o número 3 infinitas vezes, a função sempre retornará **5**.

## Abstração ?

