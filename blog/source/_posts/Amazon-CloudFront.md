---
layout: cloudfront
title: Amazon CloudFront
date: 2020-05-15 23:39:44
tags:
---


## ¿Qué es Amazon CloudFront?
Amazon CloudFront es una red de entrega de contenido (CDN) proporcionada por Amazon Web Services. Mediante el uso de un CDN, las empresas pueden acelerar la entrega de archivos a los usuarios a través de Internet y al mismo tiempo reducir la carga en su propia infraestructura. CloudFront es la solución CDN propia de AWS que se integra con otros productos de AWS, por lo que es conveniente para las empresas que ya se ejecutan en AWS.


## ¿Por qué CloudFront es una parte esencial del ecosistema sin servidor?
Según el modelo sin servidor, muchos sitios web y aplicaciones dependen de archivos estáticos para realizar la mayor parte del trabajo, con solo partes del contenido personalizadas mediante API sin servidor. Las partes estáticas incluyen páginas web HTML, archivos CSS, código Javascript y medios como imágenes y archivos de video.

## ¿Cómo se integra CloudFront con otros servicios de AWS?
Para hablar de CloudFront integrado con otro servicio de AWS, se refiere principalmente a la capacidad de CloudFront de usar ese servicio como fuente de datos para su distribución. Estas integraciones incluyen:

### Amazon S3 
Es posible (y de hecho muy común) usar un bucket de Amazon S3 como fuente desde la cual CloudFront solicitará archivos antes de colocarlos en sus ubicaciones de borde. Esto funciona tanto con los depósitos estándar S3 como con los depósitos configurados como puntos finales del sitio web . Cuando se configura CloudFront, el depósito S3 puede continuar usándose sin cambios.

### Amazon EC2
CloudFront admite el uso de un servidor Amazon EC2 o un punto final Elastic Load Balancing como origen de archivos en una distribución de CloudFront. El soporte de CloudFront para orígenes HTTP / HTTPS personalizados es lo que permite esta integración, lo que significa que también es posible utilizar un servidor que no sea EC2 como origen de archivo.

### AWS Lambda 
Funcionando esencialmente como AWS Lambda , las funciones de Lambda @ Edge se ejecutan en ubicaciones de borde de CloudFront. Esto significa que el código de las funciones de Lambda @ Edge corre más cerca de donde se encuentran sus usuarios y, como resultado, puede proporcionar una experiencia más rápida y fluida a los visitantes de su sitio web o usuarios de la aplicación. 

## Beneficios de usar CloudFront
El uso de CloudFront proporciona a los desarrolladores sin servidor una serie de beneficios, que se analizan a continuación.

* Escalabilidad 
* Facilidad de configuración  
* Configuración flexible  

