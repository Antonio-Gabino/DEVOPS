# DEVOPS
![Herramientas](https://github.com/Antonio-Gabino/DEVOPS/blob/main/img/Herramientas.jpg?raw=true)

## Índice
1. [Fase de Control de Código Fuente](#Fase-de-Control-de-Codigo-Fuente)
2. [Las herramientas más populares para cada fase del ciclo de DevOps](#las-herramientas-más-populares)
3. [Empresas que han implementado DevOps](#empresas-que-han-implementado-devops)
4. [Empresas y casos reales de implementación de DevOps](#Empresas-y-casos-reales-de-implementación-dedevops)
5. [Infojobs, oferta empleo DevOps](#Infojobs,-oferta-empleo-DevOps)
6. [Infojobs, requisitos de la oferta](#Infojobs,-requisitos-de-la-oferta)
7. [Opinión sobre la oferta empleo](#Opinión-sobre-la-oferta-empleo)

  
## Las herramientas más populares para cada fase del ciclo de DevOps.
<div align="justify"> 
  
 #Fase de Control de Código Fuente.
  
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


|                                         |    Tabla de Herramientas DevOps       |                                                                          |
|-----------------------------------------|---------------------------------------|--------------------------------------------------------------------------|
|                Fase                     |          Herramientas Clave           |                            Descripción                                   |   | Control de Código Fuente                | Git, IDEs                             | Gestión de versiones, colaboración en el código                          |
| Integración Continua (CI)               | Jenkins, CircleCI, Travis CI, etc.    | Automatización de la construcción, pruebas y despliegue                  | 
| Gestión Configuración e Infraestructura | Ansible, Chef, Puppet                 | Automatización de la configuración de sistemas y aplicaciones            |
| Construcción y Empaquetado              | Docker, Packer                        | Creación y gestión de contenedores y imágenes                            | 
| Despliegue y Orquestación               | Kubernetes, Helm                      | Orquestación de contenedores y gestión de clusters                       |
| Monitoreo y Seguridad                   | Prometheus, Grafana, Nagios, ELK Stack| Monitoreo del rendimiento, detección de anomalías y gestión de logs      |
| Colaboración y Planificación            | Jira, Confluence                      | Gestión de proyectos, seguimiento de tareas y documentación              |
| Pruebas Automatizadas                   | Selenium, JUnit                       | Automatización de pruebas funcionales y unitarias                        |



