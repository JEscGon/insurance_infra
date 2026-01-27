# insurance_infra
infrastructure files 

### Ubicar docker-compose en la raiz de insurance.

docker-compose up --build


Config INTELIj.
--------------------  
🔹 Crear configuración de debug
	Arriba a la derecha → Add Configuration…
	+ → Remote JVM Debug

Configura así:
--------------
insurance-users
Name: Debug insurance-users
Host: localhost
Port: 5005
Debugger mode: Attach

-------------------------------------
------------ || PUERTOS :: ----------
-------------------------------------
TEST PORTS:
	5005 → insurance-users
	5006 → insurance-policies
	5007 → insurance-middle
PORTS:
	8000 → insurance-users
	8001 → insurance-policies
	8002 → insurance-middle
