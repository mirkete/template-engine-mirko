# Mi *Template Engine*!
Construí este *template engine* para entender el funcionamiento de algunos *template engines* como [Handlebars]("https://handlebarsjs.com/"), [EJS](https://ejs.co/), etc.

## Uso
Para usar este template-engine, se debe contar con un **template** en formato **HTML**. Las variables deben especificarse de la siguiente manera:

```
<h1>Mi variable: **variable_name**</h1>
```
> variable_name: Nombre de la variable

Luego, para compilar el template con un valor, se debe llamar a **compile**:

```
import { compile } from ("./utils/template-engine-mirko") //in ES modules

compile(template, objWithValues)
```
- **template**: Debera contener el template en formato HTML
- **objWithValues**: Objeto con el formato *{varName: varValue}*. Debera contener el nombre de la variable y su valor.

## Playground
Este repositorio esta preparado para probar el funcionamiento del *template engine*. Para hacerlo, solo se debe clonar y reemplazar con los valores deseados los archivos `template.html` e `index.js`


- Para ponerlo en funcionamiento se debe ejecutar el siguiente comando:
```
npm start
```
> No es necesario `npm install` ya que el proyecto no tiene dependencias externas.