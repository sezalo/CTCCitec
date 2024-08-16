
# CTCCitec

Prueba técnica para aspirar al rol de científico de datos de CTCCitec. La prueba busca evaluar habilidades en análisis de datos, limpieza de datos, modelado y manejo de control de versiones utilizando Git y GitHub. El objetivo final es la implementación de un modelo de predicción para identificar la probabilidad de que un cliente realice una nueva compra en los próximos 30 días a patir de un dataset de ventas al detalle. 
## Uso
- El análisis de datos, limpieza de datos y modelado se realiza en el archivo **Desarrollo.ipynb**. A continuación se describe su ejecución desde el directorio del proyecto.
Creación de ambiente virtual desde la consola con la versión de python y librerías necesarias para ejecutar el proyecto:
```bash
# Crea un nuevo ambiente virtual con Python 3.10.11 en la carpeta .venv
python3.10 -m venv .venv

# Activa el ambiente virtual
# En Windows
.venv\Scripts\activate
# En macOS/Linux
source .venv/bin/activate

# Instala los paquetes listados en requirements.txt
pip install -r requirements.txt
```

Ejecución del notebook desde la consola asegurando tener jupyter instalado:
```bash
jupyter nbconvert --to notebook --execute --inplace Desarrollo.ipynb
```
En caso de que no lo esté, ejecutar previamente: 
```bash
pip install jupyter
```

## Autores
Sebastián Z.L.
- [@sezalo](https://github.com/sezalo)


## Licencia

[None]


## Contacto
Sebastián Z.L. - suasimilco@gmail.com

Project Link: https://github.com/sezalo/CTCCitec