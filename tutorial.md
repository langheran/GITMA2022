# Taller en GCP BigQuery

## Introducción

[![NDS](https://github.com/langheran/GITMA2022/raw/main/images/nds.png)](https://ndscognitivelabs.com/) [![GITMA](https://github.com/langheran/GITMA2022/raw/main/images/gitma_logo400.webp)](https://www.gitma.ndscognitivelabs.com/)

Este tutorial ilustra los siguientes conceptos.

1. Crear un proyecto o usar una cuenta de servicio para conectarnos a BigQuery
2. Cargar en un `DataFrame` de `pandas` el resultado de un query en BigQuery hacia una base de datos pública 
3. Usar Aprendizaje Automático desde BigQuery
4. Hacer una predicción con un modelo creado con el lenguaje BQML
5. Incrementar la precisión de nuestro modelo con ingeniería de atributos

Cada objetivo corresponde a un #TODO en el notebook del participante. Trata de completar todo el ejercicio antes de ver la solución que se encuentra en `solution/taller.ipynb`.

Si cerraste por error el tutorial, es posible volverlo a abrir con el siguiente comando.

```sh
teachme tutorial.md
```

## Instala los requerimientos

```sh
pip3 install -r requirements.txt
```

**Tip**: Haz click en el botón `Copiar en Cloud Shell` que se encuentra en la esquina superior derecha de la sección de código y presiona `Enter` para ejecutar los comandos de este tutorial.

## Abre el laboratorio

A continuación, abre el laboratorio que se encuentra aquí <walkthrough-editor-open-file filePath="GITMA2022/taller.ipynb">taller.ipynb</walkthrough-editor-open-file>.

Al abrir te pregunta si deseas confiar en el notebook, haz click en `Trust`.

![trust](https://github.com/langheran/GITMA2022/raw/main/images/trust_notebook.png)

Hay que esperar a que termine de cargar las extensiones de Python en la barra de estatus e iniciar el kernel de Python en Jupyter.

![connecting_kernel](https://github.com/langheran/GITMA2022/raw/main/images/connecting_kernel.png)

![trusted](https://github.com/langheran/GITMA2022/raw/main/images/trusted.png)

Si el notebook no carga (se queda en blanco), entonces ciérralo y vuélvelo a abrir.

Una vez que termine de cargar la página y puedas ejecutar las primeras celdas con `Shift + Enter`, sigue las instrucciones del laboratorio hasta terminarlo.

Es posible que te aparezca esta pantalla al estar creando el proyecto, en dado caso, haz click en `AUTORIZAR`.

[![autorizar](https://github.com/langheran/GITMA2022/raw/main/images/autorizar_gcloud.png)](https://www.gitma.ndscognitivelabs.com/)

## Conclusión

Felicidades, haz concluido el laboratorio, por favor no olvides llenar tus datos para obtener tu certificado de participación otorgado por NDS Cognitive Labs.

[![Google](https://img.shields.io/badge/Google%20Forms-673AB7?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAD1BMVEVnOrdnOrdnOrdnOrf%2F%2F%2F94M%2BZmAAAAA3RSTlO7v8DLRKXoAAAAIklEQVR42mNgYkYBjAzMaIA4ARYWIAIDDIEB1EJYgBGNDwCyjgMvHnNRfgAAAABJRU5ErkJggg%3D%3D)](https://docs.google.com/forms/d/e/1FAIpQLScXXCzdELAw5IWhSE-h5ldySUWX0QmiHP7uhj2WdE9N2ZeKaQ/viewform?usp=sf_link)

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>
