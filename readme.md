Despliegue de Infraestructura Híbrida para Big Data: De Servidores Locales a AWS con Docker y Bash



Fase 1: On-Premise Lab (Cimientos): Implementación de nodos Rocky Linux 9 en VirtualBox bajo arquitectura 
de recursos optimizados (2GB RAM).

Fase 2: Cluster Distribuido: Configuración de un cluster de 3 nodos (Master, Worker1, Worker2) con 
intercomunicación mediante Llaves RSA (Passwordless SSH) y resolución de nombres vía /etc/hosts.

Fase 3: Cloud Migration (AWS): Aprovisionamiento de instancias EC2 en la nube de Amazon, gestión de Security
 Groups (Firewalls) y acceso remoto profesional mediante archivos .pem.

Fase 4: Microservicios y Contenedores: Orquestación de servicios (Nginx y MariaDB) utilizando Docker,
 implementando mapeo de puertos y aislamiento de procesos.

Fase 5: DevSecOps & Automation: Creación de Bash Scripts para la automatización de backups críticos con 
compresión .tar.gz y transferencia de datos segura vía SCP