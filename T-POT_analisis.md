#ANALISIS DETALLADO DE INFORMACIÓN RECOPILADA POR LA HERRAMIENTA T-POT

T-POT es un sistema que contiene un conjunto de honeypots y cada uno se especializa en una tarea en especifico asi como tambien contiene kibana y elasticsearch entre otras herramientas un mapa de ataques en tiempo real hacia nuestro sistema y un mapa de ataques en tiempo real en todas partes del mundo.<p><p><p><p>
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/MapaTiempoReal.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/MapaAtaques.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/RepresentacionTiempoReal.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/honeypotsK.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/UsuariosMasUsados.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/Contrase%C3%B1asMasUsadas.png)<p>
Es un listado dinámico que recopila y clasifica las contraseñas más comunes que los atacantes y bots automatizados utilizan al intentar acceder por fuerza bruta a servicios como SSH, Telnet, FTP, bases de datos, etc. Este dato se obtiene directamente de los comandos y paquetes maliciosos que capturan los honeypots.<p>
Fuente de datos: Proviene de los logs de honeypots como Cowrie, Dionaea o Hermes, que simulan ser servicios vulnerables.
Propósito principal: Servir como un termómetro de las tendencias de ataque, mostrando qué contraseñas débiles o predeterminadas son más probadas por los ciberdelincuentes.
Valor para la seguridad:
Educación: Es una herramienta visual poderosa para concienciar sobre la importancia de usar contraseñas fuertes y únicas.
Detección de tendencias: Permite ver en directo cómo los atacantes usan listas de contraseñas comunes (como "admin", "123456", "password") y cómo estas listas evolucionan.
Hardening: Refuerza la idea de que estas contraseñas nunca deben usarse en sistemas reales.
En resumen, es una ventana fascinante a la "caja de herramientas" del atacante, mostrando de forma empírica y contundente la crítica necesidad de una buena higiene de contraseñas.
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/HoneypotAttacksBar.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/AtaquesCountry.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/CountryYPort.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/p0f%20sistema%20operativo.png)<p>
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/Attacker%20SRC%20IP%20reputation.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/TOP10IPAtacantes.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/asntop10.png)
![image_Alt](https://github.com/NETD3VIL/HoneyPots/blob/4f5bbc809d98ea4274f7dead343c93321252233d/IMAGENES/CVESsuricata.png)
