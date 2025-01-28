# Asteroids

Este es un proyecto del clásico juego **Asteroids**, desarrollado en Python. A continuación, encontrarás los pasos necesarios para configurar y ejecutar el juego en tu máquina local.

## Requisitos
- Python 3.8 o superior instalado en tu sistema.

---

## Instrucciones de Instalación

### 1. Crear el entorno virtual
Primero, crea un entorno virtual para el proyecto. Ejecuta el siguiente comando:

```bash
python3 -m venv venv
```

### 2. Activar el entorno virtual
Activa el entorno virtual dependiendo de tu sistema operativo:

- **En Windows**:
  ```bash
  .\venv\Scripts\activate
  ```

- **En macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 3. Instalar las dependencias
Con el entorno activado, instala las dependencias necesarias desde el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Ejecutar el juego
Por último, ejecuta el archivo principal para iniciar el juego:

```bash
python main.py
```

---

## Estructura del Proyecto
```
Asteroids/
│
├── main.py              # Archivo principal del juego
├── requirements.txt     # Dependencias necesarias
├── assets/              # Recursos del juego (imágenes, sonidos, etc.)
├── src/                 # Código fuente adicional
└── README.md            # Documentación
```
