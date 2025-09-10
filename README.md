# Action Deploy
Este repositorio es para la prueba número 1 de Ingeniería DevOps en el que consiste en hacer un deploy con una estrategia de ramas
_____________________________________________________________________
## Tipo de estrategia de ramificación
Voy a utilizar la estrategia de Trunk-Based-Development porque este es un proyecto chico de poca duración y tampoco lo integra un equipo de muchos desarrolladores porque este repositorio está solamente desarrollado por mí utilizando ramas temporales llamadas:
- **main**: Esta rama es la rama oficial en la que la aplicación será desplegada.
- **develop**: Esta rama sirve para ir desarrollando el código del workflow haciendo pruebas antes de desplegarlo a producción.
- **feature/desplegar mensaje**: esta funcionalidad servirá para desplegar un mensaje en caso de que falle.
- **hotfix/errores**: esta rama va a servir para la revisión de errores de código que pueden haber durante el proceso.
No utilicé GitFlow porque para esa técnica de rama se utiliza para proyectos de larga duración en el cual también se desarrollan para ir versionando ya que un versionamiento constante es para proyectos que van durando y para proyectos grandes.
_____________________________________________________________________
## Proyecto
Este proyecto consiste en un despligue de un código de python a través de un workflow que automatizará un código de python mío que hará auto-commit y auto-push
utilizando:
- `auto-commit https://github.com/marketplace/actions/git-auto-commit`
