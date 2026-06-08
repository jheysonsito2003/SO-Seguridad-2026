# INFORME FINAL DE SEGURIDAD INFORMÁTICA

## Introducción

Durante el desarrollo de esta actividad se utilizaron diversas herramientas y mecanismos de seguridad con el propósito de proteger la información almacenada y controlar adecuadamente el acceso a los datos. Asimismo, se aplicaron buenas prácticas relacionadas con la gestión de repositorios, autenticación segura e integridad de archivos.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/34afebcc-a901-4fd5-872e-5bbf8bade448" />


---

## Amenazas Detectadas

### Acceso indebido a la información

Existe el riesgo de que personas sin autorización intenten acceder a los archivos o repositorios del proyecto, comprometiendo la confidencialidad de la información.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/ae130189-a88c-4a9d-98cf-6521cd700701" />

### Sustracción de credenciales

Las contraseñas, claves de acceso o credenciales pueden ser obtenidas por terceros mediante diferentes técnicas, permitiendo el acceso no autorizado a los sistemas.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/880d1c3c-bbfb-4e30-b71a-9bd575d1d230" />

### Alteración de archivos

Los documentos y evidencias pueden sufrir modificaciones accidentales o intencionales, afectando la confiabilidad de la información almacenada.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/d05ea1df-1da3-4ca7-b6dd-8fc2a5609f89" />

### Exposición de información sensible

La publicación accidental de archivos privados, claves o datos personales puede ocasionar problemas de seguridad y privacidad.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/fec6f077-7bf2-45da-9f7f-7ce72092bcef" />

---

## Medidas de Seguridad Aplicadas

### Permisos en Linux

Se configuraron permisos de acceso para restringir las acciones que pueden realizar los usuarios sobre determinados archivos y directorios.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/3cc9ce12-8720-4656-8149-11e5341628e6" />

### Uso de ACL

Las listas de control de acceso (ACL) permitieron asignar permisos específicos a usuarios concretos, proporcionando un control más detallado sobre los recursos.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/e42bc734-042d-4179-8be1-40070b32c785" />

### Verificación mediante SHA-256

Se generaron hashes utilizando el algoritmo SHA-256 para comprobar que los archivos no hayan sido modificados después de su creación.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/a22a93fe-39da-4587-80e4-ea3eec45e7e6" />

### Control de versiones con Git

Git fue utilizado para registrar cada cambio realizado en el proyecto, permitiendo mantener un historial completo de modificaciones.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/0d6791f4-8e44-4578-93aa-76394eb99058" />

### Repositorio privado en GitHub

El repositorio fue configurado como privado para garantizar que únicamente personas autorizadas tengan acceso a las evidencias almacenadas.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/f2e5ef82-6270-46c6-afdc-ceb19c11d632" />

### Autenticación mediante SSH

Se implementó una clave SSH para establecer conexiones seguras entre el equipo local y GitHub.

📷 **Imagen 11:** Configuración de clave SSH.

### Autenticación de dos factores (2FA)

Se activó la autenticación de dos factores para reforzar la seguridad de la cuenta y reducir el riesgo de accesos no autorizados.

📷 **Imagen 12:** Verificación en dos pasos.

---

## Conclusiones

La aplicación de herramientas como Git, GitHub, claves SSH, permisos Linux, ACL, hashes SHA-256 y autenticación de dos factores permitió fortalecer significativamente la seguridad de la información. Estas medidas contribuyen a proteger los datos frente a accesos indebidos, modificaciones no autorizadas y posibles pérdidas de información, garantizando una mejor administración de las evidencias digitales.
