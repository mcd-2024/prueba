# Ejemplo Práctico de Uso de un Fork en GitHub:

1. Hacer un Fork del Repositorio:

- Ve al repositorio de GitHub que te interesa.
- Haz clic en el botón "Fork" en la esquina superior derecha de la página.
- Esto creará una copia del repositorio en tu cuenta de GitHub.

2. Clonar el Fork a tu Máquina Local:

- Una vez que el fork esté en tu cuenta de GitHub, puedes clonarlo a tu máquina local para trabajar en él.
  Usa:
  > git clone https://github.com/tu-usuario/nombre-del-repositorio.git
- Ahora tienes una copia local del repositorio en tu máquina.

3. Crear una Nueva Rama para tus Cambios:

- Es una buena práctica no trabajar directamente en la rama principal (master o main). En su lugar, crea una rama para tus cambios:
  > git checkout -b mi-nueva-caracteristica

4. Hacer tus Cambios:

- Realiza las modificaciones o mejoras que deseas en el código.
- Una vez que estés satisfecho con los cambios, haz commit a esos cambios en tu rama:
  > git add .
  > git commit -m "Descripción de los cambios realizados"

5. Subir los Cambios a GitHub:

- Push tus cambios a tu fork en GitHub:
  > git push origin mi-nueva-caracteristica

6. Crear una Pull Request:
- Ve a tu repositorio en GitHub.
- Verás un botón para "Comparar y crear una pull request". Haz clic en él.
- Proporciona una descripción de los cambios y envía la pull request.
- El propietario del repositorio original recibirá tu pull request y podrá revisar tus cambios.

7. Esperar Feedback o Aprobación:
- El propietario del repositorio original revisará tu pull request. Puede aceptarlo, solicitar cambios o rechazarlo.
