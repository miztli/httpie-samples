## psicometria 

### tipos asignacion 
##### GET 
http :8096/api/v1/psicometria/tipos-asignacion 

### asignacion pruebas 
##### GET 
http :8096/api/v1/psicometria/asignacion-pruebas
http :8096/api/v1/psicometria/asignacion-pruebas onlyName==true
http :8096/api/v1/psicometria/asignacion-pruebas ids_usuarios==54 solo_nombre==true pruebas_terminadas==false

#### POST
http POST :8096/api/v1/psicometria/asignacion-pruebas < newAssignment.json

#### DELETE
http DELETE :8096/api/v1/psicometria/asignacion-pruebas/5c7ed9c348c4f6451aa56f52
