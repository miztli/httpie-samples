## administracion

### usuarios
##### GET usuarios
http :8091/api/v1/administracion/usuarios nombre='miztlii melgoza' email=='dark' sucursal_id==1 perfil_base_id==1 tipo_persona_id==1 prefijo=='' digito==1 fecha_registro_desde=='' fecha_registro_hasta=='' page==1 size==5 fecha_registro_desde==1545525853000 fecha_registro_hasta==1545525853000

##### GET usuarios with roles
http :8091/api/v1/administracion/usuarios/54 roles==true
http :8091/api/v1/administracion/usuarios ids==1,49,53,48

##### GET usuarios count by person type id 
http :8091/api/v1/administracion/usuarios/total-tipo-persona id==1

##### POST usuarios
http POST :8091/api/v1/administracion/usuarios < create-user.json

##### perfiles base (POST file)
Carga de usuarios con archivo excel
http -f POST :8091/api/v1/administracion/usuarios/carga archivo@plantilla_carga_expediente.xlsx

##### PATCH usuarios
http PATCH :8091/api/v1/administracion/usuarios < patch-user.json

##### PUT usuarios
http PUT :8091/api/v1/administracion/usuarios < update-user.json

##### POST login
http POST :8091/api/v1/administracion/login email=soporte@grupohuman.co password=

##### DELTE usuarios
http DELETE :8091/api/v1/administracion/usuarios/54 

### roles
##### GET roles

http :8091/api/v1/administracion/roles page==2 size==3 sort==id order==desc
http :8091/api/v1/administracion/roles permisos==true catalogo==true
http :8091/api/v1/administracion/roles catalogo==true
http :8091/api/v1/administracion/roles catalogo==true estatus==true
http :8091/api/v1/administracion/roles/1

##### PATCH roles
http PATCH :8091/api/v1/administracion/roles < patch-rol.json

##### POST roles
http POST :8091/api/v1/administracion/roles < create-rol.json

### permisos
##### GET permisos
http :8091/api/v1/administracion/permisos rol_id==1 permiso==ADMIN page==1 size==5
http :8091/api/v1/administracion/permisos/1

##### GET idiomas
http :8091/api/v1/administracion/idiomas catalogo==true

