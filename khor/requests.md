## administracion

#### filtra usuarios
http :8091/api/v1/administracion/usuarios nombre='miztlii melgoza' email=='dark' sucursal_id==1 perfil_base_id==1 tipo_persona_id==1 prefijo=='' digito==1 fecha_registro_desde=='' fecha_registro_hasta=='' page==1 size==5 fecha_registro_desde==1545525853000 fecha_registro_hasta==1545525853000

#### login (POST json)
http POST :8091/api/v1/administracion/login email=soporte@grupohuman.co password=

---

## preferencias

#### perfil base (POST file)
Carga de perfiles con archivo excel
http -f POST :8090/api/v1/preferencias/perfil-base/carga archivo@Human.xlsx
