# Portafolio de Seguridad de Software — CS 305

## Descripción del proyecto

Este repositorio contiene mi trabajo del curso CS 305: Seguridad de Software, de mi programa de Ciencias de la Computación. Incluye una reflexión sobre el proyecto Artemis Financial y el informe de prácticas de codificación segura desarrollado durante el curso.

## 1. Cliente y requisitos del software

Artemis Financial fue el cliente del proyecto. La empresa necesitaba mejorar la seguridad de su aplicación, proteger la información intercambiada y evaluar posibles vulnerabilidades. Para atender estas necesidades, trabajé con HTTPS, un certificado digital, el algoritmo SHA-256 y herramientas de análisis de dependencias.

## 2. Identificación de vulnerabilidades e importancia del código seguro

Una decisión importante fue utilizar OWASP Dependency-Check para identificar dependencias con vulnerabilidades conocidas. También revisé la configuración de la comunicación segura y la generación de hashes. Desarrollar código seguro ayuda a proteger la información, reducir los riesgos de ataques y mantener la confianza de los clientes. La seguridad contribuye a la continuidad de las operaciones y a la reputación de una empresa.

## 3. Parte más difícil o útil de la evaluación

La parte más útil fue analizar el informe de OWASP Dependency-Check y comprender cómo las dependencias de terceros pueden introducir riesgos. Una dificultad fue interpretar los resultados y reconocer las limitaciones de la herramienta. Durante el análisis se presentó un error de autorización de OSS Index, por lo que fue importante considerar esa limitación al interpretar el informe.

## 4. Capas de seguridad y recursos futuros

Reforcé la seguridad mediante la configuración de HTTPS, el uso de un certificado digital y la generación de hashes SHA-256. También analicé las dependencias con OWASP Dependency-Check. En futuros proyectos utilizaría recursos como OWASP, la Base de Datos Nacional de Vulnerabilidades (NVD) y herramientas de análisis de dependencias. Priorizaría las correcciones según la gravedad, la aplicabilidad y el impacto de cada vulnerabilidad.

## 5. Verificación del funcionamiento y la seguridad

Comprobé el funcionamiento de la aplicación ejecutándola localmente, accediendo al endpoint mediante HTTPS y verificando que mostrara la información y el hash esperados. También generé un informe de OWASP Dependency-Check para identificar riesgos en las dependencias. Estas pruebas ayudaron a verificar las funciones evaluadas, aunque el análisis no garantiza la ausencia de todas las vulnerabilidades y presentó una limitación relacionada con la autorización de OSS Index.

## 6. Herramientas y prácticas útiles

Utilicé Java, Eclipse, Maven, HTTPS/TLS, certificados digitales, SHA-256 y OWASP Dependency-Check. Estas herramientas me permitieron practicar la configuración de comunicaciones seguras, la generación de hashes y el análisis de dependencias. En futuros proyectos aplicaré estas prácticas, revisaré las dependencias periódicamente y protegeré las credenciales y claves privadas.

## 7. Evidencia para futuros empleadores

Este proyecto demuestra mi experiencia práctica con una aplicación Java, la configuración de HTTPS, la generación de hashes criptográficos y la evaluación de dependencias vulnerables. El informe, el código y las evidencias de las pruebas pueden servir para explicar cómo identifiqué riesgos, utilicé herramientas de seguridad y documenté las limitaciones encontradas.

## Conclusión

Este proyecto me permitió comprender que la seguridad debe formar parte de todo el ciclo de desarrollo de software. La comunicación segura, las técnicas criptográficas, el análisis de dependencias y las pruebas funcionales contribuyen a mejorar la protección y la confiabilidad de las aplicaciones.
