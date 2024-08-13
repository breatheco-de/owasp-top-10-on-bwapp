# Proyecto de Explotación de OWASP Top 10 en bWAPP
<!-- hide -->
> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/owasp-top-10-on-bwapp/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*These instructions are [available in english](https://github.com/breatheco-de/owasp-top-10-on-bwapp/blob/main/README.md)*

### Antes de empezar...

> ¡Te necesitamos! Estos ejercicios se crean y mantienen en colaboración con personas como tú. Si encuentras algún error o falta de ortografía, contribuye y/o repórtalo.

<!-- endhide -->


## 🌱 ¿Cómo empezar este proyecto?

En esta actividad, trabajaremos con la máquina virtual beebox, que contiene bWAPP, para explotar vulnerabilidades del [OWASP Top 10](https://owasp.org/www-project-top-ten/). A continuación, se proporciona un ejemplo detallado sobre cómo explotar la vulnerabilidad **Security Misconfiguration (A05:2021)**. Los estudiantes deberán aplicar los mismos pasos para las demás vulnerabilidades del OWASP Top 10.

## 📝 Instrucciones

* Abre esta URL y forkea el siguiente repositorio https://github.com/breatheco-de/owasp-top-10-on-bwapp

 ![fork button](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/fork_button.png?raw=true)

Un nuevo repositorio se creará en tu cuenta.

* Clona este nuevo repositorio forkeado utilizando Git para descargartelo a tu maquina local.
* Una vez que hayas clonado, sigue los pasos de mas abajo hasta el final.

¡Comencemos! 🤓


### Paso 1: Configuración Inicial

- [ ] Inicia la máquina virtual beebox.
- [ ] Accede a la interfaz web de bWAPP desde tu navegador usando la dirección IP de la máquina beebox.

- [ ] **Inicia sesión en bWAPP**:

```bash
    - Usuario: bee
    - Contraseña: bug
```
 
- [ ] **Selecciona el OWASP Top 10**. En el menú de bWAPP, selecciona "OWASP Top 10" en la lista desplegable para ver las vulnerabilidades disponibles.


### Paso 2: Exploración de Vulnerabilidades

-  **Revisión de las vulnerabilidades disponibles**. Explora las diferentes vulnerabilidades del OWASP Top 10 listadas en bWAPP.
- [ ] Selecciona **Security Misconfiguration (A05:2021)** para la actividad guiada.

### Paso 3: Explotación de "Security Misconfiguration (A05:2021)"

> 💡 Este paso es un ejemplo detallado sobre cómo explotar una de las vulnerabilidades del OWASP Top 10. Los estudiantes deben seguir estos pasos como guía para las otras vulnerabilidades.


1. **Comprensión de la vulnerabilidad**:
   - **Security Misconfiguration** ocurre cuando un sistema no está adecuadamente configurado, lo que puede llevar a la exposición de configuraciones sensibles, servicios no seguros habilitados, entre otros.

2. **Enumeración y Reconocimiento**:
   - Utiliza herramientas como **Nmap** para por ejemplo identificar puertos abiertos. `ejemplo: nmap -sS -p- [IP_de_beebox]`
   - Escanea la máquina beebox para descubrir configuraciones predeterminadas inseguras y servicios expuestos que podrían estar mal configurados.

3. **Explotación de la Vulnerabilidad**:
   - Una vez que hayas identificado una configuración insegura (por ejemplo, un puerto innecesariamente abierto), intenta acceder a ella utilizando credenciales por defecto o sin credenciales.
   - En bWAPP, utiliza la funcionalidad disponible bajo "Security Misconfiguration" para probar cómo estas configuraciones pueden ser manipuladas para comprometer la seguridad del sistema.

4. **Documentación del Proceso**:
   - Documenta cada paso realizado: desde la identificación de la configuración insegura, el escaneo y la explotación, hasta los resultados obtenidos.
   - Incluye capturas de pantalla y descripciones claras.

5. **Propuesta de Mitigación**:
   - Describe cómo solucionar la configuración insegura identificada. Por ejemplo, asegurando puertos, deshabilitando servicios innecesarios, o aplicando parches.

### Paso 4: Aplicar otras vulnerabilidades de OWASP Top 10

- [ ] **Repite el proceso**:
    - Sigue los mismos pasos detallados anteriormente para cada una de las vulnerabilidades restantes del OWASP Top 10.
    - **Es importante que apliques las técnicas de pentesting que aprendiste en semanas anteriores**, asegurándote de completar el proceso de escaneo, identificación, explotación, y documentación para cada vulnerabilidad.

### Paso 5: Documentación Final

- [ ] **Elabora un informe estructurado** que incluya:
   - **Introducción**: Descripción general del ejercicio.
   - **Vulnerabilidades Exploradas**: Detalles de cada una de las vulnerabilidades del OWASP Top 10 que se han explotado.
   - **Métodos de Explotación**: Descripción de las técnicas utilizadas para explotar cada vulnerabilidad.
   - **Propuestas de Prevención y Mitigación**: Soluciones para prevenir o corregir cada vulnerabilidad identificada.
   - **Conclusión**: Reflexión sobre el proceso y la importancia de la configuración segura en entornos web.

#### ⚠ ¡Importante!

- Asegúrate de que cada paso realizado siga los principios básicos de pentesting: reconocimiento, escaneo, enumeración, explotación, y mitigación.
- Al documentar los pasos, se deben incluir todos los detalles posibles para asegurar que el informe final refleje un análisis completo.

## 🚛 ¿Cómo entregar este proyecto?

- En la raíz del proyecto bifurcado, cargue el informe en formato `.pdf` con el nombre `petesting-report-OWASP-top10.pdf`. 


<!-- hide -->

## Colaboradores

Gracias a estas personas maravillosas ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodríguez (rosinni)](https://github.com/rosinni) contribución: (build-tutorial) ✅, (documentación) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribución: (detector bugs) 🐛

Este proyecto sigue la especificación [all-contributors](https://github.com/kentcdodds/all-contributors). ¡Todas las contribuciones son bienvenidas!

Este y otros ejercicios son usados para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/coding-bootcamps/desarrollador-full-stack/?lang=es), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning).Tambien puedes adentrarte al mundo de ciberseguridad con nuestro [Bootcamp de ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad).
<!-- endhide -->