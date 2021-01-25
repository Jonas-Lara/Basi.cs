# Basi.cs

_Este repositorio esta destinado a ser un biblia con ejemplos prácticos y concisos sobre el uso de C#, ojala puedas aportar_

## Comenzando 🚀

_Mira dentro de las carpetas **Basics**, **Fundamentals**, **Hacks** y **OOP (Oriented Objects Programing)** para conocer a fondo el proyecto._


### Pre-requisitos 📋

_Que cosas necesitas para usar este repositorio_

```
#1 Una máquina con Linux (SUSE, Fedora, Debian, Ubuntu, Etc.)
```
```
#2 MONO, en nuestro caso usaremos Mono para ejecutar C# y no .NET core.
```
```
#3 NuGet Package Manager para Mono, ¿Alguna vez has intentado usar NuGet con Mono?
```
```
#4 Un editor de texto plano, te recomiendo encarecidamente que utilices Gedit, Emacs ó Vim. Aprenderás más.
```
```
#5 La mayoría de estos ejercicios son fuentes de Microsoft, Mono, Uno Platoform, Odyssey, W3schools, FreeCodeCamp, Etc. 
```
```
#6 Paciencia, Gusto y disciplina.
```

### Instalación de mono 🔧

_Primero claro, necesitamos mono_

_Para Ubuntu 20.04, agregamos estos cértificados para acceder y descargar paquetes a traves de HTTPS_

```
sudo apt install gnupg ca-certificates
```
_Agrega la clave de registro_

```
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
```
_Agrega una dirección de repositorios_
```
echo "deb https://download.mono-project.com/repo/ubuntu stable-focal main" | sudo tee /etc/apt/sources.list.d/mono-official-stable.list
```
_Finalmente actualizamos los repositorios_
```
sudo apt update
```

_E instala _

```
sudo apt install mono-devel -y
```

_Otros paquetes de mono_

_Instalar todo el paquete de mono, resuelve problemas como "Assembly not found"_

```
sudo apt install mono-complete -y
```

_Depurador de código_

```
sudo apt install mono-dbg -y
```
_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.



---
⌨️ con ❤️ por [Villanuevand](https://github.com/Villanuevand) 😊
