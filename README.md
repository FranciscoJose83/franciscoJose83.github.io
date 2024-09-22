# fjmr.github.io
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  background: #5AB507;
  font-family: Arial, sans-serif;
  color: #fff;
  margin: 0;
  padding: 20px;
  font-family: Arial, Helvetica, sans-serif;
}
   h1 {
    color: #FFD700;
    text-align: center;
   }
   h2 {
    color: #FFA500;
    border-bottom: 2px solid #fff;
    padding-bottom: 5px;
   }
   ul, ol {
    background: #4C9A2A;
    padding: 25px;
    border-radius: 8px;
   }
   li {
    margin-bottom: 10px;
   }

/* Style the side navigation */
.sidenav {
  height: 100%;
  width: 200px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
}


/* Side navigation links */
.sidenav a {
  color: white;
  padding: 16px;
  text-decoration: RED;
  display: block;
}

/* Change color on hover */
.sidenav a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the content */
.content {
  margin-left: 200px;
  padding-left: 20px;
}
</style>
</head>
<body>

<div class="sidenav">
  <a href="HOME.html">HOME</a>
  <a href="MI CV HTML.HTML">MI CV HTML</a>
  <a href="MI CV CSS.HTML">MI CV HTML</a>
</div>

<div class="content">
  <h1>Francisco José Martí Rodilla</h1>
  <h2>Datos personales</h2>
  <ul>
   <li>Direccion: C/Pla de arguines, nº2, 3º, 10-B</li>
   <li>Telefono: 676419846</li>
   <li>Correo electronico: FranJose@hotmail.com</li>
  </ul>
  <h2>Datos de interes</h2>
  <ul>
   <li>Carnet de conducir B</li>
   <li>Veiculo propio</li>
  </ul>
  <h2>Experiencia Laboral</h2>
  <ol>
   <li>Operador de proceso 2008-Actualidad</li>
   <li>Mantenimiento electrico 2007-2008</li>
   <li>Operador bobinero 2002-2006</li>
   <li>Reponedor en gran superficie 2001-2001</li>
   <li>Limpieza industrial 2000-2000</li>
   <li>Instalador electrico 1999-1999</li>
  </ol>
  <h2>Estudios</h2>
  <ol>
   <li>ASIR (Actualmente en curso)</li>
   <li>Mantenimiento industrial G.S. 2007</li>
   <li>Automacion G.M 2003</li>
   <li>EGB</li>
  </ol>
  <h2>Cursos</h2>
  <ol>
   <li>Carretillero</li>
   <li>Prevencion de riesgos lavorales</li>
   <li>Instalaciones en media y baja tension</li>
   <li>Primeros axilios</li>
  </ol>
</div>

</body>
</html>
