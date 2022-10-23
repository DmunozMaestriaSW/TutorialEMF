# Creación del modelo

Una vez instalado creado el proyecto, procedemos a crear el modelo, en la misma pantalla que nos abre el IDE. En la parte derecha tenemos disponible la paleta en donde se encuentran los diferemtes clasificadores, relaciones y demás.

![paleta](img/model/01.png)

Para el ejemplo, vamos a sar el clasificador "Class" y en relaciones "Composition".

## Agregar los clasificadores

Hacemos clic en el clasificador "Class" y luego en un área libre del diagrama para agregarlo.

## Cambiar nombre

Seleccionar un clasificador agregado y en la parte inferior se despliega las propiedades. En la parte del nombre ingresar según sea el caso.

## Agregar atributos

- Seleccionar un calsificador agregado y se desplegará un menú, del que se debe seleccionar el ícono [-].

    ![Paso 1](img/model/04.png)

- En las propiedades cambie el nombre del atributo

    ![Paso 1](img/model/05.png)

- En la propiedades, seleccione el botón [...] ubicado junto a EType.

    ![Paso 1](img/model/06.png)

- En el listado seleccione el tipo adecuado a al atributo, en este caso string.

    ![Paso 1](img/model/07.png)

- Luego para agregar un relación de composición desde estudiante hacia matrícula, cambiar el nombre a matrículas. De esta manera el digrama queda así:

    ![Paso 1](img/model/08.png)

## Generar del código del modelo

Primero abrimos el archivo .genmodel como se mestra a continuación:

![Paso 1](img/model/09.png)

Haciendo clic sobre el modelo (Sgamodel) se despliegan las opciones:

- Generate Model Code
- Generate Edit Code
- Generate Editor Code

![Paso 1](img/model/10.png)

Ejecutar una a una las opciones en el mismo orden, de tal manera que se crean los proyectos .edit y .editor

![Paso 1](img/model/11.png)