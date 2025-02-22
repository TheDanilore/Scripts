# Script de Python para Automatizar Trabajos (Transformaciones, ETL, ETC)

Este repositorio contiene scripts en Python para la transformación de datos desde archivos Excel hacia un formato compatible con Odoo, SalesForce.

## 📂 Estructura del proyecto

```bash
Scripts/
│── ETL_Scripts_Odoo/
│   ├── transformar_odoo_productos.py  # Script para transformar productos
│   ├── productos_transformados.xlsx   # Salida del proceso
│   ├── Productos/                     # Carpeta con archivos de entrada
│       ├── Productos.xlsx             #Agrega tu archivo excel
│       ├── product_template.xlsx      #Plantilla de productos de Odoo
    ├── Contactos - Clientes/          # Carpeta con archivos de entrada
|       ├── Clientes.xlsx         #Agrega tu archivo excel
|       ├── plantilla_odoo.xlsx  #Plantilla de productos de Odoo
│── README.md
```

## 🚀 Requisitos
- Python 3.8+
- Pandas
- OpenPyXL (pip install pandas openpyxl)

## 📋 Funcionalidades
- ✅ Lee archivos Excel y extrae datos relevantes.
- ✅ Mapea los datos según el formato requerido por Odoo.
- ✅ Valida la presencia de campos obligatorios.
- ✅ Guarda la salida en un nuevo archivo Excel.
