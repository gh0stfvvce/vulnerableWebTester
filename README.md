# vulnerableWebTester
Este script de Python escanea vulnerabilidades comunes en un sitio web y verifica la protección CSRF, la inyección SQL y el Cross-Site Scripting (XSS).


Este script de Python escanea vulnerabilidades comunes en un sitio web y verifica la protección CSRF, la inyección SQL y el Cross-Site Scripting (XSS).

## Requisitos

- Python 3.x
- Las bibliotecas `requests` y `lxml`. Puedes instalarlas ejecutando:
  ```bash
  pip install requests lxml

## Uso

    Clona el repositorio o descarga el archivo tester.py.
    Abre una terminal y navega al directorio que contiene tester.py.
    Ejecuta el script:

    bash

    ./tester.py

## Instalación (Opcional)

Puedes instalar el script en /usr/local/bin para que sea ejecutable desde cualquier ubicación sin necesidad de invocar Python directamente.

```bash
sudo cp tester.py /usr/local/bin/tester
sudo chmod +x /usr/local/bin/tester
```
Después de la instalación, puedes ejecutar el script simplemente escribiendo tester en la terminal.