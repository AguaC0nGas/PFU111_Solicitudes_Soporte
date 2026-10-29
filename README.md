# PFU-111 Semana 13: Registro de solicitudes de soporte

Aplicación de escritorio en Python con Tkinter para registrar, validar, guardar y consultar solicitudes de soporte técnico.

## Requisitos
- Python 3 instalado.
- Tkinter (incluido normalmente en las instalaciones de Python para Windows).

## Ejecución
1. Descarga `main.py` y `solicitudes.csv` en la misma carpeta.
2. Abre CMD o una terminal en esa carpeta.
3. Ejecuta: `python main.py`
4. Completa los campos y pulsa **Registrar solicitud**.
5. Usa **Consultar solicitudes** para leer los registros del CSV.

El programa crea `solicitudes.csv` junto a `main.py` si todavía no existe. El CSV incluido contiene datos ficticios de ejemplo; puedes borrarlo antes de realizar las pruebas desde cero.

## Validaciones
- Nombre, código y descripción no pueden estar vacíos ni contener solo espacios.
- El tipo debe ser equipo, software o conectividad.
- La prioridad debe ser bajo, medio o alto.
- Se muestran mensajes cuando hay errores de validación o de lectura/escritura.
"# PFU111_Solicitudes_Soporte" 
