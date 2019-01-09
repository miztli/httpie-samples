## administracion

## preferencias

### perfiles base
##### perfiles base (POST file)
Carga de perfiles con archivo excel
http -f POST :8090/api/v1/preferencias/perfiles-base/carga archivo@Human.xlsx

##### GET perfiles base
http :8090/api/v1/preferencias/perfiles-base paginado==true page==2 size==2
http :8090/api/v1/preferencias/perfiles-base catalogo==true perfil_asignable==true

##### POST perfiles base
http POST :8090/api/v1/preferencias/perfiles-base < new-profile.json

##### PUT perfiles bsae
http POST :8090/api/v1/preferencias/perfiles-base/18 < update-profile.json

##### DELETE perfiles base
http DELTE :8090/api/v1/preferencias/perfiles-base/18

### sucursales
http :8090/api/v1/preferencias/sucursales catalogo==true
http :8090/api/v1/preferencias/sucursales page==0 size==2

### competencias
http :8090/api/v1/preferencias/

### niveles
http :8090/api/v1/preferencias/

### nivel unidad organizacional
http :8090/api/v1/preferencias/nivel-unidad-organizacional catalogo==true
http :8090/api/v1/preferencias/nivel-unidad-organizacional page==1 size=5

### tipo persona
http :8090/api/v1/preferencias/

### area
http :8090/api/v1/preferencias/areas catalogo==true
