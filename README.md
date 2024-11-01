# DEVOPS

## Índice
1. [Introducción](#introducción)
2. [Las herramientas más populares para cada fase del ciclo de DevOps](#las-herramientas-más-populares-para-cada-fase-del-ciclo-de-DevOps)
3. [Empresas que han implementado DevOps](#empresas-que-han-implementado-devops)
4. [Empresas y casos reales de implementación de DevOps](#Empresas-y-casos-reales-de-implementación-dedevops)
5. [Infojobs, oferta empleo DevOps](#Infojobs,-oferta-empleo-DevOps)
6. [Infojobs, requisitos de la oferta](#Infojobs,-requisitos-de-la-oferta)
7. [Opinión sobre la oferta empleo](#Opinión-sobre-la-oferta-empleo)

## Introducción.

<p align="justify">
La filosofía DevOps es una metodología para creación de software basada en la integración entre desarrolladores de software y administradores de sistemas, permitiendo fabricar software más rápidamente, con mayor calidad, menor coste y una altísima frecuencia de releases, siendo el objetivo final minimizar el riesgo de los cambios que se producen en las entregas y dar así, un mayor valor tanto a los clientes como al propio negocio.
</p>  
<div align="center">  
<img src="img/DevOps.png" alt="DevOps" width="500" height="auto">
</div>

<p align="justify">
<strong>La integración continua</strong> (CI), permite que los equipos desarrollen de manera más ágil y con mayor confianza, minimizando riesgos y mejorando la calidad del código a lo largo del proceso de desarrollo, automatizando el mecanismo de revisión, validación, prueba y alertas.
El <strong>despliegue continuo</strong> (CD) y la <strong>entrega continua</strong> (CE), garantiza que las aplicaciones estén listas para su despliegue en cualquier momento, permitiendo a las empresas ser más ágiles y capaces de lanzar nuevas características rápidamente, permitiendo así, implantar una nueva versión de la aplicación.
IaC reduce la complejidad y el esfuerzo de gestionar <strong>infraestructura</strong>, mejorando la agilidad y permitiendo a los equipos desplegar y escalar entornos de manera rápida y segura.
La <strong>monitorización</strong> y el <strong>logging</strong>, permiten identificar problemas y optimizar el rendimiento, jugando un papel clave en garantizar la seguridad y la resiliencia del sistema.
La <strong>cultura colaborativa</strong> promueve la comunicación abierta entre los equipos que deben colaborar en todo el ciclo de vida del software, desde la planificación hasta la implementación y el mantenimiento. 
</p>

## Las herramientas más populares para cada fase del ciclo de DevOps.
<div align="justify"> 
  
1.  Fase de Control de Código Fuente.
  
<strong>Git</strong> es el sistema de control de versiones más utilizado, permitiendo a los desarrolladores rastrear cambios en el código, colaborar y crear ramas. 
<em>GitHub, GitLab y Bitbucket</em> son plataformas basadas en Git que también ofrecen características como revisión de código, CI/CD y gestión de proyectos.   
<strong>IDEs</strong> (Entornos de Desarrollo Integrados): Como Visual Studio Code, IntelliJ IDEA, Eclipse, que proporcionan un entorno completo para escribir, depurar y probar código.

2.	Fase de Integración Continua (CI).
   
<strong>Jenkins</strong> es un servidor de automatización de código abierto (open-source) que permite construir, probar e implementar software de forma repetible. 
**CircleCI, Travis CI, GitLab CI/CD**, plataformas de CI en la nube que ofrecen una configuración más rápida y fácil, permitiendo integrar, probar y desplegar código de manera automática. 
**Maven, Gradle** Herramientas de gestión de dependencias que automatizan la construcción de proyectos Java.
3.	Fase de Gestión de Configuración e Infraestructura.
**Ansible** es una herramienta de automatización que permite gestionar y configurar sistemas, desplegar aplicaciones y orquestar tareas de forma declarativa. Usa archivos YAML y es "agentless", lo que significa que no necesita instalar software en los nodos a gestionar.
__Chef / Puppet__  gestiona la configuración que permiten definir la infraestructura como código (IaC). Usan un enfoque declarativo para asegurar que las máquinas estén en un estado deseado, instalando el software y configuraciones necesarias automáticamente.
4.	Fase de Construcción y Empaquetado.
**Docker** es una plataforma de contenedores que permite empaquetar aplicaciones y sus dependencias en contenedores aislados, facilitando el desarrollo, pruebas,  portabilidad y escalabilidad.
**Packer** utiliza la creación de imágenes de máquina (VMs o contenedores) a partir de un solo archivo de configuración, facilitando la creación de imágenes consistentes en diferentes plataformas.
5.	Fase de Despliegue y Orquestación.
**Kubernetes** es una plataforma de orquestación de contenedores que automatiza la implementación, escalado y gestión de aplicaciones contenedorizadas a gran escala, garantizando una alta disponibilidad.
**Helm** se utiliza junto con Kubernetes como un gestor de paquetes. Ayuda a simplificar la gestión y despliegue de aplicaciones Kubernetes mediante la creación de gráficos (charts) reutilizables para la implementación de aplicaciones complejas.
6.	Fase de Monitoreo y Seguridad.
**Prometheus** es un sistema de monitoreo y alertas de tiempo serie que permite recopilar y almacenar métricas de aplicaciones y sistemas integrándose fácilmente con Kubernetes y Docker, y permitiendo monitorear el estado de las aplicaciones y la infraestructura.
**Grafana** es una plataforma de visualización que permite crear dashboards (paneles interactivos) personalizados para visualizar las métricas recopiladas por Prometheus y otras fuentes, facilitando la recogida de datos.
**Nagios** es otra herramienta popular de monitoreo que permite supervisar servidores, aplicaciones, servicios de red y otros recursos, generando alertas cuando se detectan problemas.
**ELK Stack** (Elasticsearch, Logstash, Kibana), recolecta, almacena y analiza logs de sistemas y aplicaciones en tiempo real. Kibana se usa para visualizar los datos recolectados en Elasticsearch y Logstash los procesa.
7.	Fase de Colaboración y Planificación.
Jira es una herramienta de gestión de proyectos ágil que permite planificar, rastrear y gestionar tareas, bugs y epics, visualizar el progreso del proyecto y fomentar la colaboración entre equipos.
Confluence es un complemento de Jira que permite a los equipos documentar y compartir información en un espacio de trabajo colaborativo.
8.	Fase de Pruebas Automatizadas.
Selenium realiza pruebas automatizadas para aplicaciones web, permitiendo a los desarrolladores crear scripts que simulen la interacción del usuario con una aplicación web para verificar que las funcionalidades estén correctamente implementadas.
Junit es un popular framework de pruebas unitarias para Java, que permite a los desarrolladores escribir y ejecutar pruebas de código a nivel unitario, asegurando que cada parte funcione correctamente.
</div>













