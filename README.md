# Informe Laboratorio 2

## Información del Autor

- **Nombre**: Cristóbal León
- **Correo Electrónico**: cristobal.leon1@mail.udp.cl
- **Fecha**: 14 de Septiembre de 2023

## Índice

1. [Descripción de actividades](#descripción-de-actividades)
2. [Desarrollo de actividades según criterio de rúbrica](#desarrollo-de-actividades-según-criterio-de-rúbrica)
    - [Levantamiento de docker para correr DVWA](#levantamiento-de-docker-para-correr-dvwa)
    - [Redirección de puertos en docker](#redirección-de-puertos-en-docker)
    - [Obtención de consulta a replicar (burp)](#obtención-de-consulta-a-replicar-burp)
    - [Identificación de campos a modificar (burp)](#identificación-de-campos-a-modificar-burp)
    - [Obtención de diccionarios para el ataque (burp)](#obtención-de-diccionarios-para-el-ataque-burp)
    - [Obtención de al menos 2 pares (burp)](#obtención-de-al-menos-2-pares-burp)
    - [Obtención de código de inspect element (curl)](#obtención-de-código-de-inspect-element-curl)
    - [Utilización de curl por terminal (curl)](#utilización-de-curl-por-terminal-curl)
    - [Demuestra 5 diferencias (curl)](#demuestra-5-diferencias-curl)
    - [Instalación y versión a utilizar (hydra)](#instalación-y-versión-a-utilizar-hydra)
    - [Explicación de comando a utilizar (hydra)](#explicación-de-comando-a-utilizar-hydra)
    - [Obtención de al menos 2 pares (hydra)](#obtención-de-al-menos-2-pares-hydra)
    - [Explicación paquete curl (tráfico)](#explicación-paquete-curl-tráfico)
    - [Explicación paquete burp (tráfico)](#explicación-paquete-burp-tráfico)
    - [Explicación paquete hydra (tráfico)](#explicación-paquete-hydra-tráfico)
    - [Mención de las diferencias (tráfico)](#mención-de-las-diferencias-tráfico)
    - [Detección de SW (tráfico)](#detección-de-sw-tráfico)

---

## Descripción de actividades

Este informe abarca la evaluación de seguridad de aplicaciones web mediante el uso de DVWA y herramientas como Burp Suite, cURL y Hydra.

---

## Desarrollo de actividades según criterio de rúbrica

### Levantamiento de docker para correr DVWA

Se describe el procedimiento para desplegar DVWA en Docker.

### Redirección de puertos en docker

Se explica cómo se redirigen los puertos en el entorno Docker para acceder a DVWA.

### Obtención de consulta a replicar (burp)

Se detalla el proceso de interceptar la página de inicio de sesión usando Burp Suite.

### Identificación de campos a modificar (burp)

Se señalan los campos en el formulario de inicio de sesión que necesitan modificaciones para el ataque.

### Obtención de diccionarios para el ataque (burp)

Se describe cómo se obtuvieron los diccionarios de ataque.

### Obtención de al menos 2 pares (burp)

Se muestra cómo se obtuvieron al menos dos pares de credenciales válidas mediante el ataque de fuerza bruta.

### Obtención de código de inspect element (curl)

Se detalla el proceso de utilizar la función "Inspect Element" del navegador para preparar un ataque con cURL.

### Utilización de curl por terminal (curl)

Se describen los pasos seguidos para realizar el ataque utilizando cURL a través del terminal.

### Demuestra 5 diferencias (curl)

Se listan cinco diferencias entre las respuestas obtenidas durante los ataques exitosos e infructuosos.

### Instalación y versión a utilizar (hydra)

Se detalla el proceso de instalación y la versión de Hydra utilizada.

### Explicación de comando a utilizar (hydra)

Se explica el comando utilizado en Hydra para realizar el ataque de fuerza bruta.

### Obtención de al menos 2 pares (hydra)

Se describen los pasos para obtener al menos dos conjuntos de credenciales válidas usando Hydra.

### Explicación paquete curl (tráfico)

Se describe el tráfico de red generado al utilizar cURL.

### Explicación paquete burp (tráfico)

Se detalla el tráfico de red generado al utilizar Burp Suite.

### Explicación paquete hydra (tráfico)

Se explica el tráfico de red generado al utilizar Hydra.

### Mención de las diferencias (tráfico)

Se mencionan las diferencias clave en el tráfico de red entre las tres herramientas utilizadas.

### Detección de SW (tráfico)

Se discuten métodos para identificar la herramienta que generó un determinado tráfico.

---

## Conclusiones y comentarios

El informe proporciona un análisis detallado y comparativo del uso de diversas herramientas en la evaluación de la seguridad de aplicaciones web.

