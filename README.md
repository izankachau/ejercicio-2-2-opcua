# Comunicación OPC-UA Industrial

Sistema de simulación cliente-servidor OPC-UA para automatización industrial y comunicación de autómatas programables (PLCs).

## Características
- **Servidor OPC-UA**: Simulación de datos en tiempo real replicando el comportamiento de un PLC.
- **Cliente OPC-UA**: Conexión y lectura asíncrona de datos.
- **Protocolo Estándar**: Uso de `asyncua` para estandarización IEC.
- **Gestión de Errores**: Scripts de pruebas y control avanzado de excepciones.

## Requisitos
- Python 3.8+ (Nota: Recomendado evitar la preview 3.14 por compatibilidades asíncronas).

## Instalación y Uso
1. Navega a la carpeta principal del programa:
   ```bash
   cd Programa_OPCUA
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta primero el servidor:
   ```bash
   python server_opcua.py
   ```
4. En otra terminal secundaria, lanza el cliente para probar la lectura:
   ```bash
   python client_opcua.py
   ```

## Estructura
- `Programa_OPCUA/`: Cliente y servidor.
- `Documentacion/`: Investigación del estándar de comunicaciones.
