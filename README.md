# phonia
phonia (entynetproject)

Qué es phonia?

phonia es una de las herramientas más avanzadas para escanear números de teléfono utilizando solo recursos gratuitos. El objetivo es recopilar primero información estándar como país, área, operador y tipo de línea en cualquier número de teléfono internacional con muy buena precisión.

📱INSTALACIÓN DE phonia EN TERMUX (ANDROID)📱

$ apt update && apt upgrade -y

$ termux-setup-storage

$ pkg install -y git

$ pkg install -y python

$ pkg install -y python2

$ git clone https://github.com/Scorpio28-Oficial/phonia

$ cd phonia

$ ls

$ chmod 777 phonia.sh

$ ./phonia.sh

$ ls

$ chmod 777 requirements.txt

$ python -m pip install -r requirements.txt

Hasta aquí, ya hemos instalado correctamente la herramienta, para ejecutarla debemos usar el siguiente comando combinado con el número telefónico de la víctima sin el (+), Ejemplo:

$ python phonia -p 593999433835
