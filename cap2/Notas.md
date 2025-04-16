# ex2_2.html
## Funções - Método getElementById()

Método utilizado para referenciar um  elemento HTML pelo "id" que lhe foi atribuído.
Para armazenar a referencia a um elemento em uma variável e depois obter sua propriedade, utiliza-se:
    
    var inputNome = document.getElementById("nome");
    var nome = inputNome.value

O mesmo pode ser feito com uma linha, caso o elemento não seja utilizado mais de uma vez
    
    var nome = document.getElementById("nome").value;
        
**Objeto** - representa uma instÂncia de uma classe. 

**Método** - representa uma instrução ou um conjunto de instruções que executam uma tarefa.

**Propriedade** - representa uma característica (atributo) de um objeto.

| Comando     | Descrição                                                                                                                                                                    |
|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| textContent | Consulta ou altera o texto exibido por elementos HTML como *p*, *h1*, *h2*, ou containers, *span*, *div*.                                                                    |
| innerHTML   | Consulta ou altera o texto exibido por elementos HTML como *p*, *h1*, *h2*, ou containers, *span*, *div*. Códigos HTML presentes no conteúdo são renderizados pelo navegador |
| value       | Consulta ou altera o conteúdo de campos de formulário.                                                                                                                       |

