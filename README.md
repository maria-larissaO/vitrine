# vitrine
Contexto:  
Organização de uma Vitrine de Produtos  
Você está desenvolvendo a vitrine de uma loja online de roupas. A vitrine precisa exibir os 
produtos de diferentes maneiras, dependendo do layout desejado. Além disso, alguns 
produtos podem estar temporariamente indisponíveis ou esgotados, e você precisa ocultá-los 
sem remover completamente da página.  

Estrutura Básica do Projeto  
• Crie uma pasta para o projeto (ex: vitrine-produtos).  
• Dentro da pasta, crie dois arquivos:  
o index.html: para a estrutura HTML.  
o styles.css: para os estilos CSS.  

Estrutura HTML  
• No arquivo index.html, crie a estrutura básica de uma página HTML.  
• Adicione uma seção para a vitrine de produtos, utilizando divs para representar cada produto.  
• Cada produto deve conter:  
o Uma imagem (imagens fictícias).  
o Um nome (ex: "Camiseta Básica").  
o Um preço (ex: "R$ 49,90").  
• Adicione pelo menos 6 produtos para trabalhar com diferentes cenários. 

Estilização Básica  
• No arquivo styles.css, defina estilos básicos para os produtos:  
o Adicione uma borda, padding e margem para cada produto.  
o Centralize o conteúdo de cada produto.  
o Defina uma largura e altura fixas para as imagens.
  
Aplicando display: inline  
• Selecione dois produtos e aplique a propriedade display: inline a eles.  
• Observe como os produtos são exibidos em linha, ocupando apenas o espaço 
necessário.  
• Note que a largura e altura definidas anteriormente podem não funcionar como 
esperado.  
Aplicando display: block  
• Selecione outro produto e aplique a propriedade display: block.  
• Observe como o produto ocupa toda a largura disponível, quebrando a linha.  
• Compare com o comportamento dos produtos com display: inline.  
Aplicando display: inline-block  
• Selecione mais dois produtos e aplique a propriedade display: inline-block.  
• Defina uma largura fixa para esses produtos (ex: 200px).  
• Observe como os produtos são exibidos em linha, mas respeitam a largura e altura 
definidas.  
Aplicando display: none  
• Selecione um produto e aplique a propriedade display: none.  
• Observe como o produto desaparece completamente da página, sem ocupar espaço.  
Aplicando visibility: hidden  
• Selecione outro produto e aplique a propriedade visibility: hidden.  
• Observe como o produto fica invisível, mas ainda ocupa espaço na página.  
• Compare com o comportamento de display: none. 