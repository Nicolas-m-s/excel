Sistema de Registro de Datos con Python y Excel

Aplicación de escritorio desarrollada en Python que permite registrar información de usuarios mediante una interfaz gráfica y almacenarla automáticamente en un archivo Excel.

El sistema implementa validación de datos, manejo de archivos y una interfaz visual intuitiva utilizando Tkinter.



Funcionalidades

- Registro de información mediante formulario gráfico
- Validación de campos obligatorios
- Validación numérica para edad y teléfono
- Verificación de formato de correo electrónico
- Almacenamiento automático en archivo Excel
- Limpieza automática de campos después de guardar
- Creación automática del archivo Excel


Tecnologías utilizadas

- Python
- Tkinter
- OpenPyXL
- Regex (Expresiones regulares)
- Manejo de archivos
- Programación orientada a eventos



Estructura del proyecto

```text
registro_datos.py
datos.xlsx
README.md
```


Funcionamiento del sistema

El programa realiza el siguiente flujo:

1. Verifica si existe el archivo Excel
2. Si no existe, lo crea automáticamente
3. Muestra un formulario gráfico
4. Valida la información ingresada
5. Guarda los datos en Excel
6. Muestra confirmación de éxito



Interfaz del formulario

El sistema permite registrar:

- Nombre
- Edad
- Correo electrónico
- Teléfono
- Dirección

Incluye un botón para guardar la información.



Instalación y ejecución

Instalar dependencia

```bash
pip install openpyxl
```

Ejecutar aplicación

```bash
python registro_datos.py
```



Validaciones implementadas

Campos obligatorios

Verifica que ningún campo esté vacío.



Validación numérica

Comprueba que:

- La edad sea un número
- El teléfono sea numérico



Validación de correo electrónico

Verifica que el correo tenga un formato válido mediante expresiones regulares.

Ejemplo válido:

```text
usuario@email.com
```



Conceptos aplicados

Este proyecto pone en práctica:

- Desarrollo de interfaces gráficas
- Manejo de eventos
- Validación de formularios
- Expresiones regulares
- Lectura y escritura en Excel
- Persistencia de información


Ejemplo de uso

```text
1. Abrir formulario
2. Ingresar datos
3. Validar información
4. Guardar
5. Confirmación de éxito
```

Objetivo del proyecto

Desarrollar una aplicación funcional de escritorio que combine interfaz gráfica, validación de datos y almacenamiento estructurado.


Aprendizajes obtenidos

Durante este proyecto se reforzaron conocimientos sobre:

- Tkinter
- OpenPyXL
- Validación de datos
- Manejo de archivos Excel
- Diseño de formularios interactivos


Autor

Nicolas
