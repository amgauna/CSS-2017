# CSS
## CSS - Exemplos de Código

/* CSS Folha de Estilo */ 
/* Código de página UTF-8 / ISO-8859-1 / PT-BR */

   @charset "UTF-8";

/* Style for Portuguese text */
    p:lang(pt), 
	span:lang(pt), 
	i:lang(pt), 
	b:lang(pt), 
    body:lang(pt), 
	blockquote:lang(pt), 
	article:lang(pt) 
	{ 
    font-family: Geneva, Tahoma, Verdana, sans-serif;
    font-style: normal;
    font-variant: normal;
    font-weight: bold;
    }

/* ================================================================================ */

   /* CSS Inicializar todas as propriedades do template */
   
   * { top:0; bottom:0; right:0; left:0; margin:0; padding:0;
      list-style: none;
      list-style-type: none;
      list-style-image: none;
      text-decoration: none;
      text-decoration-style: none;
      }			
	   
      @import url("css/w3.css");
     
      @import url("css/w3mobile.css");

      @import url("https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css");
     
      @import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css");

/* ================================================================================ */
