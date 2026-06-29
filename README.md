# Duplicate File Detector - Python
Aplicación de escritorio para detectar y gestionar archivos duplicados mediante hashing.

## Tecnologías
- Python 3
- tkinter (interfaz gráfica)
- hashlib (MD5)

## Características
- Pipeline de 3 etapas: agrupación por tamaño → hash parcial FNV-1a → verificación MD5
- Interfaz gráfica con tkinter
- Optimizado para reducir lecturas innecesarias de disco

## Cómo ejecutar
1. Clona el repositorio
2. Instala dependencias: pip install -r requirements.txt
3. Ejecuta: python main.py

## Materia
Estructura de Datos y sus Aplicaciones — BUAP, Primavera 2026
