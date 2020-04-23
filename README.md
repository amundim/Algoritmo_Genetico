# Algoritmo_Genetico
Algoritmo genético do zero.

Nesse projeto desenvolvi um algoritmo genético para propósito geral, com o intuito de desenvolver conhecimentos no assunto assim como disponibilizar o código para demais interessados.

A base teórica e experimentos estão disponíveis em minha página do Medium, nos seguintes links:

https://medium.com/@alexandremundim92

Os algoritmos genéticos possuem uma diversa gama de implementações e variações, sendo essas definições de projeto a cargo do desenvolvedor. Para o presente estudo, foram implementadas as seguintes funções:
  1.	Seleção
    -	Torneio
    -	Roleta
    -	Roleta modificada: foi aplicado o logaritmo para o “achatamento” dos resultados da função. Dessa forma, reduz-se as probabilidades de seleção de indivíduos com melhor desempenho e aumenta as chances daqueles com pior. A abordagem visa garantir a diversidade da população.
  2.	Cruzamento
    -	Cruzamento em um ponto: em nosso desenvolvimento, cada cruzamento foi realizado em um ponto diferente, inclusive para uma mesma geração.
  3.	Mutação
    -	Mutação em um ponto: em nosso desenvolvimento, cada mutação foi realizada em um ponto diferente, inclusive para uma mesma geração.
  4.	Elitismo
    -	Em nossa implementação do elitismo, optamos pela variação SSGA.
