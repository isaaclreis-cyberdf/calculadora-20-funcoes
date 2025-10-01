# 🧮 Calculadora Científica em C

Este projeto é uma calculadora interativa em C que suporta **20 operações matemáticas diferentes**, incluindo operações básicas, trigonometria, logaritmos, exponenciação, entre outras. É uma ótima ferramenta de aprendizado para quem está estudando C e funções matemáticas da biblioteca `math.h`.

---

## 📌 Funcionalidades

A calculadora oferece as seguintes operações:

1. Soma (`a + b`)
2. Subtração (`a - b`)
3. Multiplicação (`a * b`)
4. Divisão (`a / b`)
5. Potência (`a ^ b`)
6. Raiz quadrada (`√a`)
7. Logaritmo natural (`ln(a)`)
8. Logaritmo base 10 (`log10(a)`)
9. Exponencial (`e^a`)
10. Valor absoluto (`|a|`)
11. Seno (`sin(a)`)
12. Cosseno (`cos(a)`)
13. Tangente (`tan(a)`)
14. Arco seno (`asin(a)`)
15. Arco cosseno (`acos(a)`)
16. Arco tangente (`atan(a)`)
17. Fatorial (apenas inteiros positivos)
18. Parte inteira (`floor(a)`)
19. Porcentagem (`(a * b) / 100`)
20. Hipotenusa (`√(a² + b²)`)

---

## 🛠️ Requisitos

* Compilador C (como `gcc`)
* Biblioteca padrão do C (`stdio.h`, `math.h`)

---

## 🚀 Como Compilar e Executar

### Usando o GCC:

```bash
gcc -o calculadora calculadora.c -lm
./calculadora
```

> ⚠️ O parâmetro `-lm` é necessário para linkar a biblioteca matemática (`math.h`).

---

## 💡 Exemplos de Uso

* Para somar dois números, selecione a opção `1`, insira os dois valores e veja o resultado.
* Para calcular a raiz quadrada de um número, escolha a opção `6` e forneça o valor.
* Para obter o seno de um ângulo (em radianos), escolha a opção `11`.

---

## 🧠 Notas Importantes

* A maioria das funções trigonométricas e logarítmicas requerem que o usuário insira valores válidos (ex: logaritmo de número positivo, arco seno entre -1 e 1).
* O programa trata divisões por zero e fatorial de números negativos com mensagens de erro apropriadas.
* A entrada do usuário é validada apenas de forma básica.

---

## 📄 Licença

Este projeto é de domínio público ou pode ser usado livremente para fins educacionais.

---

## 🙋‍♂️ Autor

Desenvolvido como exemplo de prática com operações matemáticas em linguagem C.

---
