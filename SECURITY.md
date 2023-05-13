# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
rechazado, etc
- nombre: Configuración Java JDK

  usos: acciones/setup-java@v1.4.4

  con:

    # La versión de Java para que esté disponible en la ruta. Toma una versión completa o parcial de Java, o la sintaxis 1.x (por ejemplo, 1.8 => Java 8.x). Las versiones de acceso anticipado se pueden especificar en forma de, por ejemplo, 14-ea, 14.0.0-ea o 14.0.0-ea.28

    versión java:

    # El tipo de paquete (jre, jdk, jdk+fx)

    paquete java: # opcional, por defecto es jdk

    # La arquitectura (x86, x64) del paquete.

    arquitectura: # opcional, por defecto es x64

    # Ruta a donde se encuentra el JDK comprimido. La ruta podría estar en su repositorio de origen o en una ruta local en el agente.

    jdkFile: # opcional

    # ID del repositorio de distributionManagement en el archivo pom.xml. El valor predeterminado es `github`

    server-id: # opcional, el valor predeterminado es github

    # Nombre de la variable de entorno para el nombre de usuario para la autenticación en el repositorio de Apache Maven. El valor predeterminado es $GITHUB_ACTOR

    nombre de usuario del servidor: # opcional, el valor predeterminado es GITHUB_ACTOR

    # Nombre de variable de entorno para contraseña o token para autenticación en el repositorio de Apache Maven. El valor predeterminado es $GITHUB_TOKEN

    contraseña del servidor: # opcional, el valor predeterminado es GITHUB_TOKEN

    # Ruta donde se escribirá el archivo settings.xml. El valor predeterminado es ~/.m2.

    configuración-ruta: # opcional

    # Clave privada GPG para importar. El valor predeterminado es una cadena vacía.

    gpg-clave-privada: # opcional

    # Nombre de la variable de entorno para la frase de contraseña de la clave privada de GPG. El valor predeterminado es $GPG_PASSPHRASE.

    frase de contraseña gpg: # opcional
