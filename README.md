# **javascript_types**

> **Números**:

<br/>

Os números representam valores numéricos, positivos ou negativos, inteiros ou decimais. Por exemplo:

<br/>

```
let x = 10;
let y = -5.5;
```

<br/>

> **Strings**:

<br/>

Strings são cadeias de caracteres. Eles podem conter letras, números, símbolos e espaços em branco. Eles são definidos entre aspas simples ou duplas. Por exemplo:

<br/>

```
let nome = "Maria";
let sobrenome = 'Silva';
```

<br/>

> **Booleanos**:

<br/>

Os booleanos são valores verdadeiro ou falso. Eles são úteis para fazer comparações e condições. Por exemplo:

<br/>

```
let temLicenca = true;
let estaAutenticado = false;
```

<br/>

> **Null**:

<br/>

Null é um valor especial que representa a ausência de valor. Por exemplo:

<br/>

```
let valor = null;
```

<br/>

> **Undefined**:

<br/>

Undefined é um valor especial que é atribuído automaticamente às variáveis que não têm valor atribuído. Por exemplo:

<br/>

```
let x;
console.log(x); // imprime undefined
```

<br/>

> **Objetos**:

<br/>

Os objetos são estruturas de dados complexas que podem conter múltiplos valores de diferentes tipos. Eles são definidos entre chaves e podem ter propriedades e métodos. Por exemplo:

<br/>

```
let pessoa = {
  nome: "João",
  idade: 30,
  endereco: {
    rua: "Rua A",
    numero: 123
  },
  hobbies: ["ler", "viajar"]
};
```

<br/>

> **Arrays**:

<br/>

Os arrays são coleções de valores que podem ser acessados por um índice. Eles são definidos entre colchetes e podem conter valores de qualquer tipo. Por exemplo:

<br/>

```
let numeros = [1, 2, 3, 4, 5];
let frutas = ["maçã", "banana", "laranja"];
```

<br/>

> **Symbol**:

O tipo de dados Symbol no JavaScript é uma das novidades introduzidas no ECMAScript 2015 (também conhecido como ES6). Um símbolo é um valor primitivo exclusivo e imutável que pode ser usado como identificador para propriedades de objetos.

Cada valor de símbolo é único e pode ser usado como chave para acessar uma propriedade em um objeto. Isso é útil para criar propriedades privadas em objetos ou para evitar conflitos de nome de propriedades.

Aqui está um exemplo de como criar e usar um símbolo:

<br/>

```
// Criando um símbolo com descrição opcional
const mySymbol = Symbol('My Symbol');

// Usando um símbolo como chave de propriedade em um objeto
const myObject = {
  [mySymbol]: 'Valor do símbolo'
};

// Acessando a propriedade usando o símbolo como chave
console.log(myObject[mySymbol]); // Output: 'Valor do símbolo'
```

<br/>

Neste exemplo, um símbolo é criado usando a função Symbol() e armazenado na variável mySymbol. Em seguida, um objeto é criado com uma propriedade que usa o símbolo mySymbol como chave.

Ao acessar a propriedade do objeto usando o símbolo como chave, o valor 'Valor do símbolo' é retornado.

É importante notar que cada valor de símbolo é único e não pode ser comparado com outro valor de símbolo usando o operador ===. Por exemplo:

<br/>

```
const mySymbol1 = Symbol('My Symbol');
const mySymbol2 = Symbol('My Symbol');

console.log(mySymbol1 === mySymbol2); // Output: false
```

<br/>

Neste exemplo, dois símbolos são criados com a mesma descrição, mas ainda assim são valores diferentes e não podem ser comparados usando o operador ===.
