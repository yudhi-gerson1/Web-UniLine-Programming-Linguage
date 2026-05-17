# 📘 Documentação Técnica: UniLine 

**Lema:** "Se tem uma linha, tem história!"  
**Fundação:** 11/05/26  
**Criador:** Yudhi Gerson

---

### ⌨️ Comandos Base (Core)
* **`show()`**: Exibe informações no terminal (equivalente ao print).
* **`nome = valor`**: Definição de variáveis.
* **`waitkb()`**: (*Wait KeyBoard*) Pausa a execução e aguarda uma entrada do usuário.
* **`calculate(conta)`**: Realiza operações matemáticas e exibe o resultado.
* **`elev`**: Operador de potenciação (ex: `2 elev 3`).
* **`x`**: O separador oficial. Substitui a tecla Enter para permitir programação em linha única.

### ⚖️ Estruturas Condicionais e Lógica
* **`if(condicao) then(acao)`**: Estrutura de decisão inicial.
* **`elif(condicao) then(acao)`**: Condicional intermediária.
* **`else(acao)`**: Ação executada caso nenhuma condição anterior seja atendida.
* **`verify(comparacao)`**: Compara dois valores e retorna `yes` ou `no`.
* **Valores Lógicos:**
    * **`yes`**: Equivalente a *True*.
    * **`no`**: Equivalente a *False*.
    * **`wdef`**: (*Will Define*) Equivalente a *None* ou *Null*.

### 🔁 Estruturas de Repetição (Loops)
* **`for(i = 1, i++ until 5): show(i)`**: Loop com contador.
* **`while(1): show("Olá")`**: Loop condicional infinito ou finito.
* **`repeat(5): show("Olá!")`**: Repete uma ação um número determinado de vezes.

### 📦 Módulos e Bibliotecas (ww - Work With)
Para utilizar funções estendidas, utilize o comando `ww` seguido do nome da biblioteca.

#### 🎲 Biblioteca `random`
* **`randomint(a, b)`**: Sorteia um número inteiro entre `a` e `b`.
* **`randomdb(a, b)`**: Sorteia um número decimal entre `a` e `b`.
* **`randomstr(a)`**: Gera uma string aleatória com `a` caracteres.
* **`choose(lista)[n]`**: Escolhe `n` itens aleatórios de uma lista ou conjunto.

#### 🚥 Biblioteca `boolean`
* **`verifyBool()`**: Compara booleanos utilizando operações lógicas.
* **`intBool()`**: Converte palavras lógicas em números.
* **`kwBool()`**: Converte números em palavras lógicas (`yes`/`no`).

### 🏗️ Funções e Comentários (v1.2)
* **`fn nomeFuncao[parâmetro]: x acao x call(nomeFuncao)`**: Define e chama funções.
* **`opinion:`**: Comentário de linha única.
* **`opinions: ... stopOpinion`**: Bloco de múltiplos comentários ou opiniões.

### ⏳ Controle de Tempo
* **`wait(s)`**: Pausa o terminal por `s` segundos.
* **`waitms(ms)`**: Pausa o terminal por `ms` milissegundos.

### 🔠 Manipulação de Strings (strman)
* **`cesar("texto")[nível]`**: Aplica a Cifra de César ao texto.
* **`replace("alvo", "novo", of objeto)`**: Substitui partes de um texto.
* **`lower()` / `upper()`**: Altera a capitalização para minúsculas ou maiúsculas.
* **`transform("máscara", "alvo")`**: Regex simplificado utilizando seletores `<x>`, `<num>`, `<bool>` e `<char>`.

### 📊 Arrays e Listas (arrays)
* **Definição:** `lista = [valor1, valor2]`
* **`position(n, lista)`**: Retorna o valor na posição `n`.
* **`total(lista)`**: Soma todos os valores numéricos de um array.
* **`read(lista, s)`**: Lê todos os valores do array com intervalo de `s` segundos.
* **`divisibility(lista, divisor)`**: Filtra números divisíveis pelo valor informado.
