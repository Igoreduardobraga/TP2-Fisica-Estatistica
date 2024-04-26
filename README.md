# TP2-Fisica-Estatistica
Neste trabalho, me dedico às Simulações de Monte Carlo do modelo de Ising 2D, utilizando o algoritmo de Metropolis, que é bastante relevante na física estatística. O objetivo central é aprofundar meu entendimento sobre como sistemas com muitos graus de liberdade, especificamente sistemas de spins em uma rede bidimensional, alcançam o equilíbrio termodinâmico e como suas características mudam sob diferentes condições de temperatura e tamanho de sistema.

A eficiência é um ponto crucial. Desenvolvi um código computacional robusto e otimizado, selecionando cuidadosamente as estruturas de dados e utilizando ferramentas como a biblioteca Numba em Python, que compila o código just-in-time para acelerar os cálculos numéricos intensivos.

Não foquei apenas na implementação técnica, mas também na análise crítica dos resultados. Medidas fundamentais como a energia por spin e a magnetização foram calculadas para uma variedade de configurações de tamanho de rede e intervalos de temperatura. Essa análise detalhada me permitiu observar o comportamento das fases do sistema e entender o impacto do tamanho da rede nas propriedades observadas.

Um dos desafios mais intrigantes foi estimar a temperatura crítica de transição de fase, especialmente no limite de um sistema infinitamente grande, o limite termodinâmico. Esse ponto de transição é crucial, pois marca uma mudança significativa nas propriedades macroscópicas do sistema, frequentemente relacionada a fenômenos como magnetização espontânea e quebras de simetria.

Tratei os erros estatísticos e sistemáticos com o respeito necessário: a precisão das simulações foi reforçada por uma metodologia rigorosa para estimar e minimizar esses erros. Utilizei a abordagem de divisão em blocos para estabelecer uma margem de erro confiável nas grandezas termodinâmicas calculadas, um passo essencial para assegurar a solidez dos resultados.

O ponto culminante do trabalho foi a interpretação dos dados, onde gráficos detalhados ilustram as variações das propriedades físicas com a temperatura. As barras de erro, meticulosamente calculadas, ofereceram um panorama visual da confiabilidade dos dados.

Em última análise, este projeto não apenas proporcionou uma imersão técnica nas simulações de Monte Carlo e no modelo de Ising, mas também se destacou como um modelo para estudos computacionais na física, onde a complexidade dos sistemas exige uma mistura sagaz de métodos numéricos e teóricos para desvendar comportamentos emergentes.
