# Clean Code

## Proyecto para practicar

Este es un proyecto de Vanilla TypeScript en Vite, para trabajar los ejercicios del curso sobre Principios SOLID y CleanCode.

Clonar o descargar el proyecto y luego:

```
yarn install
ó
npm install
```

Para ejecutar el proyecto, simplemente ejecuten:

```
yarn dev
ó
npm run dev
```

## Conceptos Claves

- Deuda técnica.
- Clean Code.
- Los nombres de las clases preferiblemente deben ser cortos y no genéricos.
- En una función limitar los parámetros posicionales a 3 como máximo.
- Evitar redundancias, por ejemplo si una función se llama *getMovieById* no es necesario que el parámetro sea *movieId*, podría llamarse sólo *id*.
- Organizar las propiedas de una clase o interface en orden alfabético (ascendente).
- Las funciones sólo deben hacer un único trabajo o tarea conforme al nombre especificado.
- Principio KISS.
- Balance entre simplicidad y legibilidad para las funciones.
- Producrar que cada función no sobrepase las 20 líneas.
- Evitar el uso de else.
- Priorizar el uso de la condicional ternaria en lo posible.
- Menos indentación es mejor.
- Principio DRY (Don't Repeat Yourself).
- Principio de responsabilidad única.
- Las propiedades se organizan en el siguiente orden: 1. statics 2. publics 3. privates
- Estructura Recomendada de Clases:

![1.png](./src/img/1.png)

- Recomendación para los comentarios:

![2.png](./src/img/2.png)

- Uniformidad en el proyecto. Problemas similares, soluciones similares.