# devops-test

Este repositorio fue creado para realizar el siguiente test: 

Prueba Técnica DevOps Jr. Gol-Ball
Crear una infraestructura con Terraform.

Conocimientos necesarios:
- terraform
- aws
- github

Necesitamos crear una infraestructura que contenga:
- bucket s3 para guardar el state de terraform tiene que estar tageado
```
Name=Gol-ball Owner=InfraTeam
```
- instancia ec2 que tiene que tener instalado `nginx` y levantar con la IP
publica la pantalla de nginx. Tiene que estar tageado 
```
Name=Gol-ball
Owner=InfraTeam (provisioner es un buen recurso)
```
- publicar tu código en un repositorio de github público y compartir el pull
request con el código, no mergear a master hasta que el PR esté aprobado.

Incluir documentación describiendo los pasos que se tomaron en
README.md.
