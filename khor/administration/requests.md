## administracion

### usuarios
##### GET usuarios
http :8091/api/v1/administracion/usuarios nombre='miztlii melgoza' email=='dark' sucursal_id==1 perfil_base_id==1 tipo_persona_id==1 prefijo=='' digito==1 fecha_registro_desde=='' fecha_registro_hasta=='' page==1 size==5 fecha_registro_desde==1545525853000 fecha_registro_hasta==1545525853000

##### PATCH usuarios
http PATCH :8091/api/v1/administracion/usuarios < patch-user.json

##### POST login
http POST :8091/api/v1/administracion/login email=soporte@grupohuman.co password=

### roles
##### GET roles

http :8091/api/v1/administracion/roles permisos==tru
