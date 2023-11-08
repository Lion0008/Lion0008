# ¡Hola! 👋 Soy Bryan León

¡Bienvenido a mi perfil de GitHub!

Como profesional especializado en el desarrollo de software, dispongo de una sólida formación y amplia experiencia en áreas críticas como la programación, diseño y implementación de sitios web. Esto me permite diseñar soluciones de software innovadoras y de alta calidad.

Mi mayor fortaleza como profesional es mi dedicación y compromiso con mi trabajo. Estoy siempre al tanto de las últimas tendencias y tecnologías en mi área. Además, poseo habilidades analíticas y resolutivas, lo que me permite identificar y solucionar problemas de manera eficiente y efectiva.

## Acerca de mí

- 👨‍💻 Tecnólogo Superior en Desarrollo de Software.

## Tecnologías y Herramientas

![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Estadísticas de GitHub

[![Mis estadísticas en GitHub](https://github-readme-stats.vercel.app/api?username=Lion0008&show_icons=true&count_private=true&theme=radical)](https://github.com/Lion0008)

## Contacto

- 📧 Puedes contactarme por correo electrónico en [bgleon17@gmail.com].
- 💼 Conéctame en [LinkedIn](https://www.linkedin.com/in/bryan-leon-46930722b/).

## Juego: Adivina el Número

Puedes jugar adivinando un número del 1 al 10. Abre la consola en tu navegador y prueba suerte:

```javascript
let numeroAleatorio = Math.floor(Math.random() * 10) + 1;
let intentos = 3;

function adivinaElNumero() {
  let respuesta = prompt("Adivina el número del 1 al 10:");

  if (respuesta === null) {
    alert("¡Hasta luego! 👋");
  } else {
    let numeroElegido = parseInt(respuesta);

    if (numeroElegido === numeroAleatorio) {
      alert("¡Correcto! ¡Has adivinado el número!");
    } else {
      intentos--;
      alert(`Incorrecto. Te quedan ${intentos} intentos.`);

      if (intentos > 0) {
        adivinaElNumero();
      } else {
        alert(`¡Agotaste tus intentos! El número era ${numeroAleatorio}.`);
      }
    }
  }
}

adivinaElNumero();

¡Gracias por visitar mi perfil!
