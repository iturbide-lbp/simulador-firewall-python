# 🔒 Práctica de Firewall: Simulador de Filtrado de IP en Python

Este repositorio contiene un script básico en Python que simula la lógica de un Firewall, evaluando direcciones IP de origen mediante una lista negra para autorizar o denegar el tráfico de red.

## 🚀 Instrucciones de Ejecución

1. Descarga el archivo `simulador_firewall.py`.
2. Ejecuta el programa con Python:

```bash
python simulador_firewall.py
```

## 📋 Funcionamiento

El programa compara la dirección IP de origen con una lista de IPs bloqueadas.

- Si la IP está en la lista negra, el acceso es denegado.
- Si la IP no está en la lista, la conexión es permitida.

## 📂 Archivo incluido

- simulador_firewall.py
