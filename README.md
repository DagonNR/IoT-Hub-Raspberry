# Uso de Azure IoT Hub, para hacer un Bot de preguntas y respuestas
En este repositorio tenemos una demostración del uso de Azure IoT Hub, conectándolo con un Raspberry.

![Microsoft-Azure-IoT-Hub](https://github.com/DagonNR/IoT-Hub-Raspberry/blob/main/images/Microsoft-Azure-IoT-Hub.png)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- Esta práctica utiliza una Raspberry, en este caso usaremos una simulación, que proporciona el mismo Azure, pero se puede realizar con una física sin problemas, solo se debe seguir ciertos pasos para conectarla. [Raspberry Pi Azure IoT Online Simulator](https://azure-samples.github.io/raspberry-pi-web-simulator/#GetStarted)
- Solo haremos la conexión, pero para visualizar la misma, se puede hacer desde el mismo Azure, por medio de App Service, o se puede hacer localmente, pero es mejor desde Azure.

---

## Pasos a seguir
- Lo primero es entrar en [Microsoft Azure](https://portal.azure.com).
- Ya dentro, buscaremos el recurso de "Centro de IoT", nos pedirá ciertas cosas, las configuramos, dependiendo de nuestras necesidades, y lo creamos.

![P1](https://github.com/DagonNR/IoT-Hub-Raspberry/blob/main/images/P1.PNG)

- Ya dentro del recurso, iremos al apartado de "Dispositivos", clicaremos en "+ Agregar dispositivo"

![P2](https://github.com/DagonNR/IoT-Hub-Raspberry/blob/main/images/P2.PNG)

- Nos pedirá una ID, y lo creamos.
- Ya creado, entramos en él y buscamos la "Cadena de conexión principal".
- Con esa cadena podemos enlazar nuestra Raspberry virtual.

![P2.1](https://github.com/DagonNR/IoT-Hub-Raspberry/blob/main/images/P2.1.PNG)
