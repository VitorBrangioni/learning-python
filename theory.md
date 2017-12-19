## Tipos Python 3

**int:**  Inteiros são virtualmente ilimitados e podem crescer até o limite da memória.
  ex: 100, int('100').

**float:** no interpretador padrão CPython, os float são implementados usando o tipo double do C. Entretanto, em outros 
interpretadores – como Jython –, isso é feito por meio do tipo flutuante de precisão dupla da plataforma abaixo, no caso a JVM.
  ex: 3.4, float('3.4')

**numeros complexos (complex):** Eles têm a parte imaginária e a real,sendo que cada uma delas é um float . Os números complexos, por exem-
plo, dão resposta como a raiz quadrada de um número negativo e são usados em domínios como engenharia elétrica, estatística etc.
  ex: 1+2j, 1+2J, complex(1, 2), 1+2k.real, 1+2k.imag.
  
 
## Operadores Aritméticos

- x + y (adição);
- x - y (subtração);
- x / y (divisão em ponto flutuante);
- x // y (divisão descartando parte fracionária);
- x * y (multiplicação);
- x % y (resto);
- -x (negação);
- x ** y (potência).

## Operadores de Bits

- x | y (ou);
- x ^y (ou exclusivo);
- x & y (e);
- x << y (x com y bits deslocados à esquerda);
- x >> y (x com y bits deslocados à direita);
- ~x (inverso em bits).

## Operações misturando tipos diferentes e as regras de coerção

Se operarmos um int e um float , vamos ter como resultado um float . Se operarmos um int ou float com um complex,
vamos ter como resultado um complex .
