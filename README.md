# Implementações de Métodos Numéricos

Este repositório contém as anotações da implementações dos métodos da bissecção, da posição falsa e do ponto fixo. Destes, apenas o método do ponto fixo não pode ser d. As explicações sobre as funções podem ser vistas a seguir.


## Método da bissecção

### ``bissecao(f, a, b, epsilon, maxIter=150)``

**f**: deve receber como argumento uma função que receba x e retorne o valor de f(x).
**a e b**: recebem os extremos de um intervalo [a, b] onde o zero da função pode estar.
**epsilon**: valor da tolerância.
**maxIter**: quantidade máxima de iterações.
	
## Método da posição falsa	

### ``PFalsa(f, a, b, epsilon, maxIter=150)``

**f**: deve receber como argumento uma função que receba x e retorne o valor de f(x).
**a e b**: recebem os extremos de um intervalo [a, b] onde o zero da função pode estar.
**epsilon**: valor da tolerância.
**maxIter**: quantidade máxima de iterações.
	
## Método do ponto fixo

### ``PFixo(f, fi, x, epsilon, maxIter=150)``

**f**: deve receber como argumento uma função que receba x e retorne o valor de f(x).
**fi**: deve receber uma função que que recebe x e retorna o valor de fi(x) sendo fi alguma opção do valor isolado de x. Essa função deve ser definida com cuidado, pois nem todo x isolado permite convergência. 
**x**: uma aproximação inicial de x.
**epsilon**: valor da tolerância.
**maxIter**: quantidade máxima de iterações.
	
