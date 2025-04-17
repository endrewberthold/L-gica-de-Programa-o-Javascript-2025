# ex2_2.html
## Funções - Método getElementById()

Método utilizado para referenciar um  elemento HTML pelo "id" que lhe foi atribuído.
Para armazenar a referencia a um elemento em uma variável e depois obter sua propriedade, utiliza-se:
    
    var inputNome = document.getElementById("nome");
    var nome = inputNome.value

O mesmo pode ser feito com uma linha, caso o elemento não seja utilizado mais de uma vez
    
    var nome = document.getElementById("nome").value;
        
**Objeto** - representa uma instância de uma classe. 

**Método** - representa uma instrução ou um conjunto de instruções que executam uma tarefa.

**Propriedade** - representa uma característica (atributo) de um objeto.

| Comando     | Descrição                                                                                                                                                                    |
|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| textContent | Consulta ou altera o texto exibido por elementos HTML como *p*, *h1*, *h2*, ou containers, *span*, *div*.                                                                    |
| innerHTML   | Consulta ou altera o texto exibido por elementos HTML como *p*, *h1*, *h2*, ou containers, *span*, *div*. Códigos HTML presentes no conteúdo são renderizados pelo navegador |
| value       | Consulta ou altera o conteúdo de campos de formulário.                                                                                                                       |

## Variáveis

Importante declarar o escopo da variável, tanto para uso global quanto para uso local. Variáveis locais só ocupam espaço quando estão sendo utilizadas, diferente das varáveis globais.


## Funções matemáticas

| Comando             | Descrição                                                                                                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Math.abs(num)       | Retorna o valor absoluto de um número, se for negativo convertido para positivo e se for positivo se mantem. *Math.abs(-3) => 3.*                                                           |
| Math.ceil(num)      | Arredonda o valor para cima. *Math.ceil(4.2) => 5.*                                                                                                                                         |
| Math.floor(num)     | Arredonda o valor para baixo. *Math.floor(7.9) => 7.*                                                                                                                                       |
| Math.pow(base, exp) | Retorna a base elevada ao expoente. *Math.pow(3, 2) => 9.*                                                                                                                                  |
| Math.random()       | Retorna um número aleatório entre 0 e 1, com várias casas decimais. *Math.random() => 0.650131407422906.*                                                                                   |
| Math.round(num)     | Arredonda o valor para o inteiro mais próximo. A partir de .5 na parte fracionário, o valor é arredondado para cima, abaixo de .5 o valor é arredondado para baixo. *Math.round(2.7) => 3.* |
| Math.sqrt(num)      | Retorna a raiz quadrada do numero. *Math.sqrt(16) => 4.*                                                                                                                                    |

