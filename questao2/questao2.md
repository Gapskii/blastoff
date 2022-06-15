# QUESTÃO 2. Em um determinado projeto os cabeçalhos devem estar previamente definidos com fonte Arial, devem estar em negrito e em caixa alta. Como você faria para esses parâmetros serem implementados neste projeto?

Há três formas de fazer isso, seja por css interno ou externo, ou por inline. O inline, neste caso, é o menos indicado, pois exigiria que cada cabeçalho fosse estilizado individualmente da forma desejada.

Entre CSS interno ou externo, entretanto, depende muito do tamanho do projeto. Sendo algo grande, o CSS externo se torna uma necessidade, mas como neste caso o projeto é enxuto, então eu implementaria os parâmetros no projeto por CSS interno, conforme index.html anexo.

Se eu sei que irei utilizar apenas h1 no meu projeto, então eu utilizaria o seletor dessa tag para realizar a estilização. Entretanto, como o enunciado abre para a possibilidade de diferentes cabeçalhos (h1 a h6), que poderiam ter diferentes peculiaridades, acho por melhor atribuir a todos uma mesma classe, por meio da qual eu realizaria a estilização.