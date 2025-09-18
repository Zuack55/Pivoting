# Pivoting en Redes: Guía Práctica de Movimiento Lateral

![Banner del Repositorio](bannerpiv.png)

Este repositorio contiene un documento técnico y recursos visuales que explican de manera detallada el proceso de **pivoteo** en ciberseguridad. El objetivo principal es demostrar cómo un atacante puede utilizar una máquina comprometida como punto de apoyo estratégico para acceder a redes y sistemas que no son directamente accesibles desde el exterior.

El material está diseñado como un caso de estudio práctico, ideal para estudiantes, profesionales de seguridad y entusiastas que deseen comprender a fondo las técnicas de **movimiento lateral** y las defensas contra ellas.

---

### Contenido del Documento

El documento abarca los siguientes temas clave, proporcionando una guía paso a paso del ataque:

* **Acceso Inicial:** Explotación de una vulnerabilidad para comprometer una máquina Windows 7.
* **Reconocimiento de Red:** Descubrimiento de la topología de red de la máquina comprometida y las subredes adyacentes.
* **Establecimiento del Pivote:** Configuración de una ruta de red para que la máquina atacante pueda comunicarse con la red interna.
* **Escaneo y Enumeración:** Identificación de servicios vulnerables en la máquina objetivo final.
* **Explotación Final:** Explotación de un servicio específico para obtener acceso privilegiado en la máquina interna (Linux).

---


### Requisitos del Laboratorio

Si deseas replicar el entorno descrito en el documento, necesitarás las siguientes máquinas virtuales:

* **Kali Linux:** Máquina del atacante.
* **Windows 7:** Máquina pivote con dos adaptadores de red (uno en la red externa y otro en la red interna).
* **Metasploitable Linux:** Máquina objetivo final.

---

### Uso y Contribuciones

Siéntete libre de descargar y usar este documento para fines educativos. Cualquier comentario o sugerencia para mejorar el contenido es bienvenida.
