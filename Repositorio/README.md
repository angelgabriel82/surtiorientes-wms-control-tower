# 📦 Subcarpeta Repositorio — WMS Surtiorientes

Este directorio contiene los archivos fuente modulares para la ejecución directa de la **Torre de Control WMS de Surtiorientes S.A.S.** mediante Streamlit y Python:

## 📄 Archivos Incluidos
- `app_jefatura.py`: Script principal de la Torre de Control WMS con soporte para catálogo real de 871 SKUs, cálculo de RSL por estrés térmico Q10, mapa de ocupación de racks P1-P8, gestión de colas Min-Heap FEFO y respaldos de base de datos SQLite.
- `requirements.txt`: Lista depurada y ligera de dependencias para el entorno virtual.
- `README.md`: Esta guía rápida de referencia.

## 🚀 Ejecución Rápida
```bash
# 1. Instalar dependencias
pip install -r requirements.txt

# 2. Ejecutar la Torre de Control
streamlit run app_jefatura.py
```
Acceso en navegador: `http://localhost:8501`.
