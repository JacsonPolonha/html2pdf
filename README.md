# html2pdf

link da biblioteca:
https://ekoopmans.github.io/html2pdf.js/

Na tag head deverá adicionar o link CDN do script da biblioteca. Após isso, dentro do body o script que será codificado.

Dentro do "body" tem uma div com a classe "content" onde está todo o conteúdo da página.

Fora da div "content" tem um botão que vai chamar a função, esse botão deve ficar fora da div para que não apareça no arquivo pdf.

No script, tem uma função, invocada pelo botão. Nessa função, vamos capturar todo o conteúdo da div, chamada nesse exemplo de “content”, utilizando o comando "document.querySelector", que captura as propriedades do elemento em questão.

Após isso, vamos definir algumas configurações que o arquivo PDF deverá conter. Você pode verificar mais detalhes sobre essas configurações acessando a documentação da biblioteca. De modo geral, elas abordam aspectos sobre o tipo de arquivo gerado, tamanho da margem, escala de qualidade e formato do documento.

Por fim, vamos chamar a função da biblioteca html2pdf. Ela vai realizar as configurações atribuídas e transformar o HTML recebido em PDF, realizando o download do arquivo logo em seguida.