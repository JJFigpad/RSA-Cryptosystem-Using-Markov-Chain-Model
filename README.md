# Study of The RSA Cryptosystem Using Markov Chain Model - Resumen

## Juan Jose Figueroa Padilla

### Departamento de Matemáticas y Ciencias de la Computación, Universidad Nacional de Colombia sede Bogotá, Bogotá, Colombia.
[jufigueroap@unal.edu.co](mailto:jufigueroap@unal.edu.co)

**Keywords:** RSA, Markov Chain, Montgomery, Extra-Reduction, Applied Mathematics

El criptosistema *RSA* se erige como el método de cifrado de clave pública predominante a nivel global, debido a su resistencia contra ataques tradicionales. Esto se debe principalmente al problema de Factorización. Sin embargo, los sistemas criptográficos no son inmunes, y siempre habrán métodos para atacarlos. En esta investigación, examinamos la explotación de vulnerabilidades de canal lateral en el cifrado *RSA*, centrándonos en la información de *Extra-Reduction* (ER) facilitada por el algoritmo de *Multiplicación Modular de Montgomery*. Aprovechando la ER como fuente de vulnerabilidad del sistema, construimos un modelo probabilístico utilizando la teoría de *cadenas de Markov discretas*. El modelo aclara la distribución de probabilidad de obtener una clave de cifrado correcta en medio de vectores de ER ruidosos. Todo siguiendo la metodología de ataque de canal lateral propuesta por M. Dugardin, W. Schindler y S. Guilley en el paper *Stochastic methods defeat regular RSA exponentiation algorithms with combined blinding methods*.

Los objetivos de esta investigación son comprender el uso de los *Procesos Estocásticos*, en particular de las *cadenas de Markov*, en el contexto de un ataque al criptosistema *RSA*. También buscamos examinar cómo funcionan y qué tan buenos los métodos probabilísticos utilizados para recuperar información oculta utilizando ejemplos de implementación en un ambiente controlado.

Esta investigación implementó con éxito un ataque teórico al criptosistema *RSA*, demostrando su alta eficacia y peligro. Destaca la importancia de los modelos de *cadenas de Markov* en la evaluación de la seguridad de los criptosistemas. Se identificaron áreas de mejora, como la necesidad de un algoritmo eficiente para calcular probabilidades y la optimización de los procesos de obtención de información clave. Estas investigaciones plantean preguntas importantes sobre la seguridad y el desarrollo futuro de los criptosistemas de clave pública.
