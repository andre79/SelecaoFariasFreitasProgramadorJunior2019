# Seleção C++ Farias & Freitas - Instruções

Os projetos devem ser feitos no QT Creator. Caso seu código não compile, ele não será avaliado. Você será avaliado pela corretude da resposta, estilo de programação e desempenho. 

<strong>Prazo de envio: 17/07/2019 até às 08:00:00 da manhã.</strong><br>
Enviar projetos para os 4 e-mails descobertos no primeiro desafio.
 
# Atenção

- C++ NÃO é Java, nem C#<br>
- Não programe em C++ como se estivesse programando em C
<p>Resolva da melhor forma possível, considerando padrões, uso da memória, simplicidade, complexidade, melhores práticas e o que há de melhor no C++ (use, preferencialmente, as versões 14 ou 17 do C++) para resolver os problemas abaixo:</p>


<strong>Questão 1)</strong>
Nesta questão deve-se implementar em C++ uma lista duplamente encadeada, com a suas devidas operações básicas:

- Inserção na cabeça;
- Inserção na cauda;
- Remoção na cabeça;
- Remoção na cauda;
- Busca por elemento.

Além disso, a lista deverá ser salva e carregada em um arquivo json.<br>
<strong>Observação:</strong> Essa lista deve ser implementada utilizando template .


<strong>Questão 2)</strong>
Nesta questão deve-se implementar, usando o QT para C++, a seguinte tela:

 ![alt text](https://github.com/andre79/SelecaoFariasFreitasProgramadorJunior2019/blob/master/exemplo_gui.png)

A tela acima deve ser <strong>auto ajustável</strong>, se adequando à qualquer redimensionamento das suas proporções.

A tarefa consiste do usuário selecionar 2 arquivos de texto qualquer. Nas opções da esquerda, o usuário pode selecionar 3 itens:
- Exibir arquivo 1: exibe na tela de preview o texto do arquivo 1;
- Exibir arquivo 2: exibe na tela de preview o texto do arquivo 2;
- Exibir ambos: exibe na tela de preview a concatenação do texto do arquivo 1 com o texto do arquivo 2.

<strong>Existem duas opções no rodapé da tela:</strong>
- <strong>Frequência de caracteres ordenadas pela quantidade de ocorrências:</strong> para essa tarefa, deve-se exibir a frequência de caracteres ordenadas pela quantidade de ocorrências, considerando o texto exibido na tela de preview. Use a forma que você considerar mais representativa para mostrar o resultado calculado;
- <strong>Frequência de caracteres ordenada lexicograficamente:</strong> para essa tarefa, deve-se exibir a frequência de caracteres ordenada lexicograficamente, considerando o texto exibido na tela de preview. Use a forma que você considerar mais representativa para mostrar o resultado calculado.

<strong>Exemplos:</strong>
Considere o texto: “XAACXAXCVAACC”.
A frequência de caracteres ordenadas pela quantidade de ocorrências é:
- A: 5
- C: 4
- X: 3
- V: 1

A frequência de caracteres ordenada lexicograficamente é:
- A: 5
- C: 4
- V: 1
- X: 3
