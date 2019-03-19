## psicometria 

### tipos asignacion 
##### GET 
http :8096/api/v1/psicometria/tipos-asignacion 

### asignacion pruebas
##### PUT - terminar una prueba 
http PUT :8096/api/v1/psicometria/asignacion-pruebas/{id_prueba}/terminar 

### secciones
##### GET 
http :8096/api/v1/psicometria/secciones 
http :8096/api/v1/psicometria/secciones/5aabe6b54606c6482cd3f034?scales=true 

### escalas
##### GET 
http :8096/api/v1/psicometria/escalas 
http :8096/api/v1/psicometria/escalas/5aa03b9730b29b0e2d50a376

### asignacion pruebas 
##### GET 
http :8096/api/v1/psicometria/asignacion-pruebas
http :8096/api/v1/psicometria/asignacion-pruebas onlyName==true
http :8096/api/v1/psicometria/asignacion-pruebas ids_usuarios==54 solo_nombre==true pruebas_terminadas==false

#### POST
http POST :8096/api/v1/psicometria/asignacion-pruebas < newAssignment.json

#### DELETE
http DELETE :8096/api/v1/psicometria/asignacion-pruebas/5c7ed9c348c4f6451aa56f52
