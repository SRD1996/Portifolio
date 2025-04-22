Documentação do Código HTML  

<!DOCTYPE html> 
Define que este é um documento HTML5. 

<html lang="pt-br"> 
Início do documento HTML, com idioma definido como Portugues Brasileiro. 

<head> 
Início da seção de cabeçalho do HTML. 

<meta charset="UTF-8" /> 
Define a codificação de caracteres como UTF-8 para suportar acentuação. 

<meta name="viewport" content="width=device-width, initial-scale=1.0"/> 
Garante que o site será responsivo em dispositivos móveis. 

<title>Douglas Wilhan</title> 
Define o título da aba do navegador como "Douglas Wilhan". 

<link rel="stylesheet" href="Portifolio.css" /> 
Importa o arquivo de estilos CSS para aplicar o design personalizado da página. 

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" /> 
Importa os ícones do Font Awesome. 

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" /> 
Importa a fonte "Inter" do Google Fonts para uso na página. 

</head> 
Fecha a seção de cabeçalho. 

<body> 
Início do corpo do documento HTML, onde o conteúdo visível da página é definido. 

<header class="navbar"> 
Define o cabeçalho da página com a classe "navbar". 

<div class="logo"></i> Douglas Wilhan</div> 
Cria a área de logo com o nome "Douglas Wilhan". 

</nav> 
Fecha a tag de navegação que estava comentada anteriormente. 

</header> 
Fecha o cabeçalho da página. 

<main class="hero"> 
Inicia o conteúdo principal da página com a classe "hero". 

<div class="content"> 
Cria uma seção de conteúdo dentro do main. 

<div class="text"> 
Inicia a seção de texto de boas-vindas. 

<div class="line"></div> 
Cria uma linha decorativa acima do título. 

<h1>Olá! Sou o Douglas<br><span></span></h1> 
Título de apresentação com destaque para o nome. 

<p>Desenvolvedor Front-end ...</p> 
Parágrafo descrevendo quem eu sou e meu trabalho como desenvolvedor. 

</div> 
Fecha a div "text". 

</div> 
Fecha a div "content". 

<div class="image2"> 
Cria uma div para a imagem do desenvolvedor. 

<img src="DW.png" alt="Generic Developer" /> 
Adiciona uma imagem com a foto ou ilustração do desenvolvedor. 

</div> 
Fecha a div da imagem. 

<div class="sidebar"> 
Cria uma barra lateral com informações adicionais. 

<div class="box"> 
Cria uma seção dentro da barra lateral. 

<h3>HABILIDADES</h3> 
Título para a seção de habilidades. 

<p>Altamente motivado, ...</p> 
Texto descritivo sobre minhas habilidades. 

<a href="#">LEARN MORE <i class="fa-solid fa-arrow-right"></i></a> 
Link para saber mais com ícone de seta. 

</div> 
Fecha a primeira caixa. 

<div class="box"> 
Início da segunda caixa da barra lateral. 

<h3>SOBRE MIM</h3> 
Título da seção "Sobre mim". 

<p>Comunicativo, atencioso ...</p> 
Texto que descreve mais sobre minha personalidade e perfil profissional. 

<a href="#">PROJETOS <i class="fa-solid fa-arrow-right"></i></a> 
Link para ver projetos com ícone de seta. 

</div> 
Fecha a segunda caixa. 

<div class="social"> 
Cria a seção de redes sociais. 

<div class="icons"> 
Agrupa os ícones das redes sociais. 

<a href="https://www.facebook.com/..."><i class="fab fa-facebook-f"></i></a> 
Link para meu Facebook com ícone. 

<a href="https://x.com/..."><i class="fab fa-twitter"></i></a> 
Link para meu Twitter com ícone. 

<a href="https://www.linkedin.com/..."><i class="fab fa-linkedin-in"></i></a> 
Link para meu LinkedIn com ícone. 

<a href="https://www.instagram.com/..."><i class="fab fa-instagram"></i></a> 
Link para meu Instagram com ícone. 

<a href="https://github.com/..."><i class="fab fa-github"></i></a> 
Link para meu GitHub com ícone. 

</div> 
Fecha o grupo de ícones. 

</div> 
Fecha a seção social. 

</div> 
Fecha a barra lateral. 

</main> 
Fecha o conteúdo principal. 

</body> 
Fecha o corpo do HTML. 

</html> 
Finaliza o documento HTML. 

 

 
Documentação do CSS  

* { 
Define que todas as margens e preenchimentos padrões são zerados e o box-sizing é definido para facilitar o controle dos elementos. 

  margin: 0; 
Remove margens padrão dos elementos. 

  padding: 0; 
Remove preenchimentos padrão dos elementos. 

  box-sizing: border-box; 
Inclui a borda e o padding no cálculo total de largura e altura. 

} 
 

body { 
Define o estilo geral do corpo da página com fonte, fundo em gradiente e cor de texto branco. 

  font-family: 'Inter', sans-serif; 
Aplica a fonte Inter para o texto da página. 

  background: linear-gradient(to bottom, #0f111a, #1a1e2d); 
Cria um fundo com gradiente de cima para baixo. 

  color: #ffffff; 
Define a cor do texto como branco. 

} 
 

a { 
Estiliza os links para que fiquem com a mesma cor do texto e sem sublinhado. 

  color: inherit; 
Faz com que o link herde a cor do elemento pai. 

  text-decoration: none; 
Remove o sublinhado dos links. 

} 
 

/*... outras regras seguem com a mesma estrutura ...*/ 
As próximas regras seguem a mesma lógica de estilização específica para layout e responsividade. 
