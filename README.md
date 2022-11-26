.clear { clear: both; }
img { border: none; }

/*-- Layout ----------------------------------------------------------*/
#contenedor {
  width: 90%;
  max-width: 900px;
 background-color: rgba(6, 9, 10, 0.552);
  margin: auto;
}

#cabecera, #menu, #lateral, #contenido, #contenido #principal, #contenido #secundario, #pie {
  border: 1px solid rgba(64, 251, 245, 0.715);
}

#cabecera { clear: both; }
#menu { clear: both; }
#lateral { float: left; width: 20%; }
#contenido { float: right; width: 78%; }
#contenido #principal { float: left; width: 78%; }
#contenido #secundario { float: right; width: 20%; }
#pie { clear: both; }

/*-- Cabecera --------------------------------------------------------*/
#cabecera #logo { float: left; }
#cabecera #buscador { float: right; }

/*-- Menu ------------------------------------------------------------*/
#menu_principal li { display: inline; float: left;
border: 1px solid rgb(29, 20, 20);
margin-right:10px; 
padding: 3px ;
background-color: rgb(42, 222, 57); } 

#menu_principal a {
text-decoration:none ;
font-family :cursive }

#menu_principal a:hover {
color: rgb(243, 9, 9);}
#menu_principal a :active {
color: black;}

/*-- Sección Principal -----------------------------------------------*/
#contenido #principal .articulo img { width: 100px; float: left; }

/*-- Pie de página ---------------------------------------------------*/
#pie .enlaces   { float: left; }
#pie .copyright { float: right; }
#cabecera,
#menu,
#lateral,
#lateral #noticias,
#lateral #publicidad,
#contenido,
#contenido #principal,
#contenido #secundario,
#pie {

  
  padding: .5em;
}

#lateral {
  padding: 0;
  background-color: rgba(235, 122, 222, 0.622);}

#secundario {
padding: 0;
background-color: rgba(211, 63, 233, 0.602);
}

#cabecera {
  padding: 0em;
}

#menu {
  margin-bottom: .5em;
}

#contenido {
  width: 77%;
  padding: 0;
}

#contenido #principal {
  width: 73%;
}

#pie {
  padding: .5em 0;
  margin-top: 1em;
}

#contenido #principal .articulo {
  margin-bottom: 1em;
  background-color: rgb(30, 227, 191);
}

#contenido #principal .articulo img {
  margin: .5em;
  
}

#lateral #publicidad {
  margin-top: 1em;
  
}
