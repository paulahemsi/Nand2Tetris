# Nand2Tetris

Projeto de Noam Nisan e Shimon Schocken que propõe a construção de um computador do zero, hardware e software, para estudar e entender como as abstrações que lidamos na programação de fato funcionam por debaixo dos panos.

[website do projeto](https://www.nand2tetris.org/)

[vídeos no coursera](https://www.coursera.org/learn/build-a-computer?utm_medium=email&utm_source=other&utm_campaign=opencourse.welcome.build-a-computer.~opencourse.welcome.ct7G8DVLEeWfzhKP8GtZlQ.)

### Temas por projeto

  * _Project 01 Boolean Logic_: Álgebra boleana, funções boleanas, leis para simplificação de funções, tabela da verdade e a construção dos chips básicos que usaremos nos próximos projetos usando apenas o Nand como ponto de partida. Chips construídos (família dos Mux sempre dando mais trabalho o.O): Not, And, Or, Xor, Mux e DMux (*Elementary Logic Gates*), Not16, And16, Or16, Mux16 (*16-bit variants*), Or8Way, Mux4Way16, Mux8Way16, DMux4Way, DMux8Way (*Multi-way variants*).
  * _Project 02 Boolean Arithmetic_: Números boleanos, adição binária, números negativos, subtração. Construção dos chips: Half Adder, Full Adder, Add16, Inc16 e da ALU (Arithmetic Logic Unit).
  * _Project 03_: Sequential Logic
  * _Project 04_: Machine Language
  * _Project 05_: Computer Architecture
  * _Project 06_: Assembler
  * _Project 07_: VM I: Stack Arithmetic
  * _Project 08_: VM II: Program Control
  * _Project 09_: High-Level Language
  * _Project 10_: Compiler I: Syntax Analysis
  * _Project 11_: Compiler II: Code Generation
  * _Project 12_: Operating System

### Materiais que estou utilizando pelo caminho

  * [Vídeo sobre Karnaugh Maps (K-maps)](https://www.youtube.com/watch?v=RO5alU6PpSU) - foi fundamental para entender como chegar na função boleana construindo o k-map de duas dimensões.
  * comando *diff* no bash para comparar a saída com o resultado esperado e confirmar que o chip se comportou como deveria (```diff saida.out teste.tst > comparativo.diff```)
