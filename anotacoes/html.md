[◀️ *Início*](https://github.com/LeiteEduardo/Estudos)
# HTML

#### ❓ O que é?
HTML (Hypertext Markup Language) é a linguagem de marcação padrão usada para criar páginas da web. Nele contém uma série de elementos e atributos que definem a estrutura e o conteúdo de uma página Web. Alguns elementos existentes são os cabeçalhos, parágrafos, links, imagens, listas e muito mais. É uma maneira de descrever a estrutura e o conteúdo para que os navegadores da web possam exibi-la corretamente.

#### 🏗️ Estrutura
A estrutura básica do HTML é a seguinte: 
```
<html >
    <head>

    </head>
    <body>
    
    </body>
</html>
```

#### Elementos
São blocos que permitem organizar e construir páginas web. Alguns dos elementos HTML mais utilizados são:

- ``` <html> ``` : Define a raiz de um documento HTML;
- ``` <head> ``` : Local onde armazena-se informações sobre o documento, como o título, ícone, etc;
- ``` <body> ``` : Contém o conteúdo principal do documento;
- ``` <h1> ``` ao ``` <h6> ``` : Defina títulos de diferentes níveis, do mais importante (```<h1>```) ao menos importante (```<h6>```);
- ``` <p> ``` : Define um parágrafo;
- ``` <a> ``` : Define uma âncora ou um link, que permite os usuários navegarem para outras páginas ou para locais específicos dentro de uma página;
- ``` <img> ``` : Exibe imagens em uma página;
- ``` <ul> ``` : Define uma lista não ordenada, que é uma lista com marcadores;
- ``` <ol> ``` : Define uma lista ordenada, que é uma lista com números;
- ``` <li> ``` : Define um item da lista, tanto da ``` <ul> ``` quanto da ``` <ol> ```;
- ``` <table> ``` : Define uma tabela para exebição de dados em linhas e colunas;
  - ``` <thead> ``` : Define o cabeçalho da ``` <table> ```;
  - ``` <tbody> ``` : Local onde irá exibir os dados;
  - ``` <tfoot> ``` : Define o pé da ``` <table> ```;
- ``` <form> ``` : Define um formulário para entrada dos usuários;
- ``` <input> ``` : Define vários tipos de entradas geralmente utilizados em formulários, a seguir listarei os tipos existente de ``` <input> ```;
  - text : define um ``` <input> ``` de texto de linha única;
  - password : define um ``` <input> ``` de senha, ocultando a informação digitada;
  - submit :  define um botão para enviar os dados de um ``` <form> ```;
  - reset :  define um botão para resetar os dados dos ``` <input> ``` de um ``` <form> ```, redefinindo para os valores padrões;
  - radio : define um botão de opção, esse botão de opção permite que o usuário selecione somente um dentre as opções;
  - checkbox : define um botão de opção, esse botão de opção permite que o usuário selecione zero ou mais de uma dentre as opções;
  - button : define um botão;
  - color : utilizado em ``` <input> ``` que receberá uma cor. Dependendo do suporte do navegador, um seletor de cores pode aparecer no ``` <input> ```;
  - date : utilizado em ``` <input> ``` que receberá uma data;
  - datetime-local : utilizado em ``` <input> ``` que receberá uma data e hora;
  - email : utilizado em ``` <input> ``` que receberá um e-mai. Dependendo do suporte do navegador, o endereço de e-mail pode ser validado automaticamente quando enviado;
  - image : transforma o ``` <input> ``` em uma imagem, mas o funcionamento é semelhante ao submit;
  - file : utlizado em um ``` <input> ``` para receber um arquivo, junto ao ``` <input> ``` é criado um botão "Procurar" para uploads de arquivos;
  - hidden : utlizado em um ``` <input> ``` para oculta-lo;
  - month : utlizado em um ``` <input> ``` para que o usuário selecione um mês do ano. Dependendo do suporte do navegador, um seletor de data pode aparecer no campo de entrada;
  - number : utlizado em um ``` <input> ``` para que o usuário insira apenas valores numéricos;