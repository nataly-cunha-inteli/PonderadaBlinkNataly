# Atividade ponderada 1 de Computação

Estudante: Nataly de Souza Cunha | T11 | G04

Professor(a): <a href="https://www.linkedin.com/in/kizzyterra/">Profª Kizzy Terra</a> 

## 🎯 Atividade

&nbsp;&nbsp;&nbsp;&nbsp;Realização de um circuito arduíno que executa o programa de piscamento de um LED.

## Materiais:

- Arduíno UNO
- 1 LED
- 2 Jumpers Macho-macho
- 1 Resistor

# Parte 1 - Blink interno

&nbsp;&nbsp;&nbsp;&nbsp;Este programa foi realizado a partir do código "Blink" presente nos templates de programas do Arduíno IDE.

https://github.com/user-attachments/assets/52c90c14-af86-4fc1-999f-d5019a91dfa3

### Código

```
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
}
```

# Parte 2 - Blink interno

## Circuito e execução

<div align="center">

<sub>Figura 1 - Circuito</sub>

<img src="assets/circuito1.jpg" width="80%" >

<sup>Fonte: Autoria própria (2024)</sup>

</div>

<div align="center">

<sub>Figura 2 - Circuito ligado ao computador</sub>

<img src="assets/circuito_pc.jpg" width="80%" >

<sup>Fonte: Autoria própria (2024)</sup>

</div>

&nbsp;&nbsp;&nbsp;&nbsp;Também é possível observar a execução do LED piscando **a partir do seguinte [link](https://drive.google.com/file/d/12EJAMkZ47X0NR3pvzWDGlDemm1YC7Y-Q/view?usp=sharing)**.

## Código

&nbsp;&nbsp;&nbsp;&nbsp;A seguir, tem-se o código utilizado para a execução do programa, com a adição de comentários explicativos para auxiliar no aprendizado.

<div align="center">

<sub>Figura 2 - código no Arduíno IDE</sub>

<img src="assets/codigo.png" width="100%" >

<sup>Fonte: Autoria própria (2024)</sup>

</div>

## Tinkercad

<sub>Figura 3 - Circuito virtual no Tinkercad </sub>

<img src="assets/tinker.png" width="80%" >

<sup>Fonte: Autoria própria (2024)</sup>

</div>
