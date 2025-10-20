# fundamentos-de-informatica-ifpr.
Minha experiênica com o Simbler foi muito boa, exceto pelo fato de que ao adicionar 50 o valor adicionado é 27. Essa é minha única reclamação


### 1. Desafio da Calculadora (`VAGNER1.sbl`)

*   **Objetivo:** Calcular a expressão matemática `(100 + 50 - 30) * 2 / 10`.
*   **Comandos Utilizados:** `LOAD`, `ADD`, `SUB`, `STORE`, `MUL`, `DIV`, `HLT`.
*   **Resultado Esperado:** Ao final da execução, o valor **24** é armazenado nos registradores AX e CX.

### 2. Desafio do Porteiro Digital (`VAGNER2.sbl`)

*   **Objetivo:** Simular uma verificação condicional. O programa verifica se o valor inicial é igual a 18.
*   **Comandos Utilizados:** `LOAD`, `CMP` (Comparar) e `JZ` (Pular se Zero).
*   **Lógica de Funcionamento:**
    *   Se o valor de entrada for `18`, o programa termina com `1` no registrador AX (acesso permitido).
    *   Se o valor for diferente de `18`, ele termina com `0` em AX (acesso negado).
*   **Conceito-Chave:** Este programa demonstra o uso do **Zero Flag (Z)** para controlar o fluxo de execução com um salto condicional.

### 3. Desafio da Contagem Regressiva (`VAGNER3.sbl`)

*   **Objetivo:** Implementar um loop simples que decrementa um contador de 5 até 0.
*   **Comandos Utilizados:** `LOAD`, `DEC` (Decrementar), `CMP`, `JZ` e `JMP` (Pular).
*   **Lógica de Funcionamento:** O programa entra em um ciclo onde subtrai 1 do valor em AX e verifica se já chegou a zero. Enquanto não for zero, ele volta ao início do loop usando `JMP`. Quando chega a zero, ele usa `JZ` para sair do loop e encerrar.
