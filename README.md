
# Modelagem Frisbee 

Este projeto explora a análise matemática e física da dinâmica do Frisbee, abordando o Princípio de Bernoulli, a Inércia Giroscópica e a Aerodinâmica para modelar e simular o voo do Frisbee em ambiente idealizado.

## Objetivos

- Modelar matematicamente o movimento do Frisbee.
- Aplicar princípios físicos fundamentais para entender o fenômeno.
- Realizar simulações numéricas do voo.
- Comparar simulações com resultados experimentais.

## Tópicos Principais

### Princípio de Bernoulli

$$
p + \frac{1}{2}\rho v^2 + \rho g y = \text{constante}
$$

### Inércia Giroscópica

$$
\tau = \frac{dL}{dt}, \quad L = I \cdot \omega
$$

### Forças Aerodinâmicas

$$
L = \frac{\rho v^2 A C_L}{2}, \quad D = \frac{\rho v^2 A C_D}{2}
$$

## Modelagem

O Frisbee é considerado um corpo rígido e simétrico, com espessura desprezível. As forças consideradas são:

- Gravidade
- Arrasto aerodinâmico
- Sustentação aerodinâmica

As equações diferenciais do movimento são:

$$
m \ddot{x} = -\frac{C_D A \rho \dot{x}^2}{2}, \quad m \ddot{z} = \frac{C_L A \rho \dot{x}^2}{2} - mg
$$

## Simulação

Simulações numéricas foram realizadas e comparadas com resultados experimentais coletados por vídeo-análise.

## Autores

- [João Pedro Silva de Sousa](https://github.com/djonpietro)
- [Pedro Henrique Honorio Saito](https://github.com/saitoi)
- [Marcos Henrique Junqueira](https://github.com/mhjmbs)

Universidade Federal do Rio de Janeiro, 2024.

