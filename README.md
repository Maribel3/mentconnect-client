# MentConnect
Una aplicación que permite mejorar el seguimiento de pacientes con trastorno mental grave -TMG-

## Descripción
MentConnect es un aplicativo móvil y web que aporta novedades y una gran mejora con respecto a las actuales aplicaciones relacionadas con la salud, puesto que permite un seguimiento continuo del/la paciente por parte de los/as profesionales sanitarios proporcionando al usuario/a una atención holística y generando una estrecha alianza terapéutica.

Esta aplicación demuestra la viabilidad de llevar a cabo un seguimiento continuo de los/las pacientes a través de la potenciación de su autonomía y el empoderamiento. Este puede llevarse a cabo de manera deslocalizada sin ser imprescindible una asistencia presencial y garantizando su seguridad y usabilidad.

## Beneficios
Los beneficios que aporta MentConnect son:
* Disminuir los efectos secundarios provocados por el tratamiento en pacientes con Trastorno Mental Grave.
* Monitorizar el proceso terapéutico y rehabilitador del/la paciente.
* Potenciar la autonomía de los/las pacientes con trastorno mental grave.
* Aumentar la socialización de los/las pacientes con trastorno mental grave.
* Incrementar la comprensión de la enfermedad y sus consecuencias.
* Reducir recaídas e ingresos hospitalarios.
* Establecer y mantener la alianza terapéutica.
* Mejorar la accesibilidad a los servicios sanitarios.
* Coordinar los recursos implicados en los casos de unidad de salud mental.
* Estimular la adherencia y la implicación en el tratamiento.
* Una interfaz de fácil uso y acceso para los/las usuarios/as.

## Diagrama de flujo de la aplicacción

### Web
Dirigida para los profesionales sanitarios.
<p align="center"><img src="src/assets/readme/diagrama-web.PNG"/></p> 

### Móvil
Dirigida para los pacientes.
<p align="center"><img src="src/assets/readme/diagrama-movil.PNG"/></p> 
 
## Ejemplo de uso

### Creación de cuestionarios
<p align="center"><img src="src/assets/readme/creacion-cuestionario.PNG" width = "750"/></p>

### Listado de cuestiones
<p align="center"><img src="src/assets/readme/listado-preguntas.PNG" width = "250"/></p>

### Formulario de respuesta
#### Respuesta numérica
<p align="center"><img src="src/assets/readme/respuesta-numerica.PNG" width = "250"/></p>

#### Respuesta dicotómica
<p align="center"><img src="src/assets/readme/respuesta-dicotomica.PNG" width = "250"/></p>

#### Respuesta cualitativa politómica
<p align="center"><img src="src/assets/readme/respuesta-cualitativa.PNG" width = "250"/></p>

#### Respuesta cuantitativa politómica
<p align="center"><img src="src/assets/readme/respuesta-cuantitativa.PNG" width = "250"/></p>

## Instalación

### Dependencias
El módulo requiere la presencia de Angular CLI

### Ejecución
Ejecutar ng serve. Navegar a http://localhost:4200/. La aplicación se recargará automáticamente si cambia alguno de los archivos de origen.

## Construido con
* [Angular CLI](https://angular.io/cli)

## Seguridad
La seguridad esta basada el Token JWT, para generar un token valido se debe realizar una llamada POST donde
la contraseña debe estar encriptada con MD5.

* URL: http://localhost:8080/security/login

Como Body se adjunta las credenciales:

```json
{
    "username":"XXX",
    "password":"***"
}
```  

La respuesta provee del token necesario para realizar las llamadas pertinentes a los endpoint publicados.

## Licencia
Este proyecto está bajo la Licencia Creative Commons 4.0
<p align="center"><img src="https://conogasi.org/wp-content/uploads/2017/05/CC-BY-NC-SA-4.0.jpg"/></p> 

## Autores
* **Andrea Candela Villagrasa** - *Documentación y desarrollo*
* **[Universidad de Valencia](https://www.uv.es/)** - *Trabajo final de grado*
