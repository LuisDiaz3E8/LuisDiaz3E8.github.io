<!DOCTYPE html>
<html>
    <head>
        <title>Mi Blog</title>
        <style>
            
            body {
              background-color: rgb(2, 79, 110);
              font-family: 'Hanlee', cursive;
              

              
            }
            
            h1,h2 {
              color: rgb(58, 156, 236);
              text-align: center;
              padding: 18px 0 18px 0;
              margin: 0 0 10px 0;
            }
            h1 span {
              border: 9px dashed #20bcd5;
              padding: 10px;
              
            }
            
            p {
              font-family: verdana;
              font-size: 20px;
              color: bisque;
              text-align: left;
            }

            li span {
              color: bisque;
            }

            form {
               text-align: center; /* centra el contenido del formulario */
            }

            input , textarea {
               display: block; /* convierte los elementos en bloques para que se ajusten a todo el ancho disponible */
               margin: 0 auto; /* centra los elementos horizontalmente */
               width: 50%; /* ajusta el ancho de los elementos */
               font-size: 1.2em; /* aumenta el tamaño de fuente */
               padding: 10px; /* agrega un relleno interno para una apariencia más agradable */
               }



            
            </style>
    </head>
    <body>
        
        <script src= "script.js"></script>
       
        <h1 style="color: #20bcd5;">Sobre mi</h1>
        <hr>
        
        <h1>Luis Alejandro Diaz Quevedo</h1>
        <img src ="avatar2.jpg" alt="Foto de perfil">
        <p>¡Bienvenidos a mi blog! Mi nombre es Luis Alejandro Díaz Quevedo y les hablo desde el corazón de la tecnología.<br>
          <br>Soy un joven apasionado por la programación y el diseño web, y en mi tiempo libre disfruto jugando videojuegos,
          <br> aprendiendo cosas nuevas y corriendo en el malecón. Aunque pueda parecer un poco vago, en realidad me encanta 
          <br>estar al tanto de las últimas tendencias en tecnología y me gusta aplicarlas a mi trabajo.<br>
          <br>Me gusta compartir mis conocimientos y experiencias con los demás, por lo que he creado este blog con la intención 
          <br>de brindar información valiosa sobre programación y diseño web. Además, quiero motivar a todos aquellos 
          <br>que, como yo, buscan mejorar sus habilidades y aprender cosas nuevas.<br><br>
          Así que si eres un apasionado de la tecnología y quieres estar al tanto de las últimas tendencias, ¡suscríbete a mi blog y no te pierdas nada!</p>
          <hr>
          <h1><span> Mis habilidades</span></h1>
          <ul>
            <li><span>HTML</span></li>
            <li><span>CSS</span></li>
            <li><span>Javascript</span></li>
            <li><span>Python</span></li>
            <li><span>C++</span></li>
          </ul>
          <hr>
          <ul>
            <li><span><b>Junior Developer en Facebook</b>
            <p>Un Junior Developer es un programador de nivel principiante o junior que tiene menos experiencia que un<br> 
              desarrollador intermedio o senior. Por lo general, un Junior Developer tiene un conocimiento básico de<br> 
              lenguajes de programación y herramientas de desarrollo, y está aprendiendo nuevas habilidades y técnicas.<br> 
              A menudo trabajan bajo la supervisión de un desarrollador más experimentado y pueden ser responsables de<br> 
              tareas más simples o de menor complejidad dentro de un proyecto de desarrollo de software.</p></span></li>

              <li><span><b>Senior Developer en OpenAI</b><P>
                Un Senior Developer es un programador con mucha experiencia y habilidades avanzadas en el desarrollo de software.<br> 
                Por lo general, un Senior Developer tiene un conocimiento profundo de múltiples lenguajes de programación,<br>
                herramientas y tecnologías relacionadas, y una comprensión sólida de los patrones y prácticas de diseño de<br> 
                software. A menudo tienen la capacidad de liderar proyectos y equipos de desarrollo, y pueden ser responsables<br> 
                de tomar decisiones técnicas importantes. También pueden tener habilidades de resolución de problemas más avanzadas<br>
                 y un conocimiento más profundo de la arquitectura de software.
              </P></span></li>
          </ul>
          
          <div align="center"><h2>Contacto</h2>
           <a href="" >Twitter</a>
           <a href="" >Youtube</a> 
          </div>
          <h1><i>Enviame un Mensaje</i></h1>
          </div>
          <form>
            <input placeholder="Nombre" required></br>
            <input placeholder="Email" required></br>
            <textarea placeholder="Mensaje"></textarea></br>
            <input type="submit" value="Enviar">
          </form>

          <footer style="color: bisque;">Pryvacy policy, terms of service, copyright</footer>

          
        
    </body>
</html>
