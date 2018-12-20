## administracion

#### login (POST json)
http POST :8091/api/v1/administracion/login email=soporte@grupohuman.co password=

---

## preferencias

#### perfil base (POST file)
Carga de perfiles con archivo excel
http -f POST :8090/api/v1/preferencias/perfil-base/carga archivo@Human.xlsx
