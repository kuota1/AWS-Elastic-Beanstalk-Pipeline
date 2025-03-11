# AWS-Elastic-Beanstalk-Pipeline

Este repositorio contiene la configuracion de un pipeline de CI/CD en AWS utilizando CodePipeline para desplegar una aplicacion en Elastic Beanstalk

Descripcion

EL pipeline fue configurado manualmente en la consola de AWS e incluye:
-Integracion con GitHUb como repositorio fuente
-un flujeo de despliegue automatico en Elastic Beanstalk
Aprobacion manual para validar cambios antes de su paso a produccion

Estructura del Pipeline

-Fuente codigo almacenado en GitHub
-Despliegue AWS CodePipeline envia los cambios a Elastic Beanstalk
- Aprobacion Manual: Se requiere aprobacion antes de que los cambios lleguen a produccion

  Como Usarlo
  Para replicar este pipeline en AWS:
  -Crear una aplicacion y entorno en Elastic Beanstalk
  -Configurar CodePipeline con GitHub como fuente
  -Agregar una etapa de despliegue apuntando a Elastic Beanstalk
  -Incluir una etapa de aprobacion manual antes de despliegue en produccion

  Proximos Pasos
  la proxima version de este proyecto sera automatizada con Terraform para mayor flexibilidad y repetibilidad.

  
inclu
