# Laboratorio Seguridad en GNU/Linux

Utilizando la maquina virtual 0wn3d brindada ejecute los siguientes ejercicios. Cada ejercicio se debe verificar con NMAP.

1. Identifique los puertos y servicios abiertos.
2. Configure el firewall para que el trafico entrante sea restrictivo.
3. Permita que el equipo responda pings.
4. Permita el acceso a todo la red a los servicios HTTP y HTTPS.
5. Permita el acceso SSH solo desde la IP de la maquina guest.
6. Configure el firewall para que el trafico saliente sea restrictivo.
7. Permita el ping desde la maquina hacia cualquier host de internet.

Utilizando los containers:
- [docker-vulnerable-dvwa](https://github.com/opsxcq/docker-vulnerable-dvwa) 
- [docker-vulnerable-dvwa con WAF](https://github.com/opsxcq/docker-vulnerable-dvwa) 

1. Acceda al servicio web del primer container.
2. Ataque el sistema con una inyección de SQL.
3. Acceda al hash de la password del usuario Gordon.
4. Descubra la password de Gordon a partir de su hash.
5. Corra el segundo container con WAF.
6. Ejecute el mismo ataque y revise los logs del mismo.
7. Evalúe las reglas.