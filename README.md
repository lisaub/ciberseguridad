# ciberseguridad
<img width="1027" height="686" alt="VirtualBox_Red" src="https://github.com/user-attachments/assets/8b649fd0-7fff-4863-bf49-06c609eca2e8" />
**Justificación técnica:**
He elegido el modo **"Red Interna"** para garantizar el aislamiento total de la máquina virtual. Para estas pruebas iniciales no necesito que el sistema tenga acceso a internet; este modo crea un entorno completamente cerrado (un "búnker" de red). 

A diferencia del modo **"Solo-Anfitrión" (Host-Only)**, que permite la comunicación entre la máquina virtual y mi computadora física (Host), la Red Interna bloquea incluso este tráfico, ofreciendo la máxima protección para mi equipo principal. Además, he evitado deliberadamente el modo **"Puente" (Bridged)**, ya que esto expondría el laboratorio directamente a mi red doméstica, lo cual es un error de seguridad grave para un entorno de pruebas aislado.
