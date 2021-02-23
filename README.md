# Proyecto-Parcial1
En este Repositorio de GitHub se puede observar los elementos aprendidos durante el primer parcial de Tópicos de Física, En el cual como un proyecto Individual se creo un archivo en Unity que contiene la siguiente información:

- Shader Phong
- Rim Light
- Normal Map
- Normal Strength
- Ramp Texture
- Banded
- Modelo Lambert Wrap

Para lograr entender tanto el código y el proyecto en general hay que explicar ciertos aspecto:

1. Shader: Son pequeños guiones que contienen los cálculos matemáticos y algoritmos para calcular el color de cada pixel, el renderizado, basado en la entrada de Iluminación y configuración del material.


2. Albedo: Color Natural, no contiene ninguna alteración.


3. Modelo: Es un objeto 3D el cual está compuesto por triángulos o polímeros los cuales recrean a cierta escala o personalización un objeto en un plano superficial de (X,Y,Z), El modelo que se usa en este proyecto es un producto de [https://assetstore.unity.com/](https://assetstore.unity.com/).


4. Phong: Funciona para crear en una superficie un efecto de brillo, la cual determina un SpecularColor, SpecularPower, SpecularGloss y GlossSteps. Hace uso principalmente de la dirección de la luz, pero se puede crear una variable ReflectedLight para obtener un reflejo que entraría como una dirección de luz adicional.


5. Normal Map: Es un tipo de textura que nos permite agregar detalles en las superficies.


6. Ramp Texture: Es un tipo de textura 2D, que agrega una escala monocromatica de grises al objeto.
