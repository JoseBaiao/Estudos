---
tags:
  - JavaScript/Estudo/FundamentosLinguagem/TiposPrimitivos
  - Estudo/Conhecimento
data_criacao: " 08-01-2026"
status: ✅ Concluído
---
---
# Tipos de dados primitivos ( String, Number, Boolean, etc. )

No Javascript, os dados e as informações são classificados em 4 **tipos primitivos** definindo a natureza em que os estamos a manipular. Os tipos fundamentais são:

- **String:** É o tipo utilizado para representar texto, como palavras, frases ou caracteres individuais, sendo sempre declarada entre aspas duplas.
```js
let nome = "Jose";
console.log("Olá, " + nome + " !");
```

- **Number:** Este tipo engloba todos os valores numéricos, permitindo a realização de cálculos e operações matemáticas. 
```js
let idade = 23;
console.log("Tu tens " + idade + " anos.");
```

- **Boolean:** Representa valores lógicos e pode assumir apenas dois estados: **true** (verdadeiro) ou **false** (falso). 
```js
let eMaiorDeIdade = idade >= 18;
console.log("É maior de idade " + eMaiorDeIdade);
```

- **Null:** Corresponde a um **valor vazio** intencional, sendo utilizado quando o programador quer indicar explicitamente que uma [variável](obsidian://open?vault=JoseBaiao&file=Inbox%2FDeclara%C3%A7%C3%A3o%20de%20vari%C3%A1veis) não possui conteúdo ou que o valor é desconhecido. 
```js
let endereco = null;
console.log("Endereço;", endereco);
```

- **Undefined:** Indica que uma variável foi declarada, mas **ainda não foi inicializada**, ou seja, ainda não lhe foi atribuído nenhum valor.
```js
let telefone
console.log("Telefone:" + telefone);
```

>[!IMPORTANT] IMPORTANTE:
>O `null` é um vazio definido de forma explícita, enquanto o `undefined` é o estado natural de algo que ainda não foi definido.

- **NaN (Not a Number):** não é um tipo em si, mas um resultado que surge quando o JavaScript tenta realizar operações matemáticas inválidas, como multiplicar uma string de texto por um número.

```js
// NULL e UNDEFINED => São tratados como false em contexto booleanos
// Strings e Numeros => São tratados como true em contexto booleanos
//exceto o 0 e String vazia ("") => São tratados como true em contexto booleanos

//Em contexto de interação entre diferentes tipos o JavaScript tenta converter os valores para um tipo comum (coerção de tipos)
```

---
## 🔗 Relacionado
- [[JavaScript Dashboard]]
- [[Declaração de variáveis]]


