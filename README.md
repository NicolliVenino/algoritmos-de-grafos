# Atividade Ponderada - Engenharia da Computação - Algoritmos de Grafos

**Nome:** Nicolli Venino Santana

**RA:** A2025.1A.0176

# Etapas Obrigatórias:

## 1.1 Tabela de pesos do RA: apresente os 6 dígitos do seu RA (D1 a D6), o destino (S6 ou S7) e os 13 pesos calculados. 

D1 = 5

D2 = 1

D3 = 0

D4 = 1

D5 = 7

D6 = 6

Origem = S0

Destino = S7 

Pesos: 

| num | aresta | formula | resultado
| --- | --- | --- | --- |
e1 | (S0, S1) | w1 = 10 + (D6 mod 5) | 16
e2 |(S0, S2) | w2 = 15 + (D5 mod 7) | 16
e3 |(S1, S2) |w3 = 8 + (D4 mod 4) | 9
e4 |(S1, S3) |w4 = 12 + (D3 mod 6) | 12
e5 |(S2, S4) |w5 = 14 + (D2 mod 5) | 15
e6 |(S2, S5) |w6 = 9 + (D1 mod 6) | 14
e7 |(S3, S4) |w7 = 7 + ((D5 + D6) mod 5) | 9
e8 |(S3, S6) |w8 = 11 + ((D4 + D5) mod 6) | 12
e9 |(S4, S5) |w9 = 6 + ((D3 + D4) mod 4) | 7
e10 |(S4, S7) |w10 = 16 + ((D2 + D3) mod 7) | 17
e11 |(S5, S7) |w11 = 18 + ((D1 + D2) mod 8) | 24
e12 |(S6, S7) |w12 = 9 + ((D5 + D1) mod 5) | 11
e13 |(S1, S4) |w13 = 20 + (D6 mod 4)| 21


## 1,2 e 1.3 e 1.4 Diagrama topológico: desenhe o grafo com os 8 vértices (S0 a S7) e as 13 arestas rotuladas com seus pesos. Matriz de pesos 8×8: construa a grade completa, indexada de S0 a S7 e garanta M[i][j] = M[j][i]. Pares sem conexão direta devem conter explicitamente NULO (ou "—"). 

![Texto Alternativo](matriz.jpeg)

## 2. Teste de mesa tabular de Dijkstra

![Texto Alternativo](parte2.jpeg)

## 3.TAD e algoritmos: implemente em código executável (por exemplo, Python) o TAD Grafo (Aula 01) e os algoritmos de Dijkstra e Prim (Aula 03). O uso assistido de LLM é permitido, desde que acompanhado de auditoria crítica documentada.


