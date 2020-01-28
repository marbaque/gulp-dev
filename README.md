# gulp-dev

Este es un manejador de paquetes.

## Instrucciones:
1. Clonar el repositorio en la carpeta de temas de Wordpress.

2. Modificar las línea en el archivo Gulpfile.js con el nombre del tema que está editando: `var themename= 'pemscores';`

3. Modifical la dirección del wordpress en el servidor local en el archivo `Gulpfile.js`.

```javascript
browserSync.init({
		open: 'external',
		proxy: 'http://localhost:8888/instituto.dev/',
		port: 8888
	});
```



4. Modificar la línea en el archivo package.json con el nombre del tema que está editando: `"name": "pemscores",`

5. Opcionalmente, modificar las líneas en el archivo package.json correspondientes a la autoría y al repositorio en github.

6. Busque la carpeta *gulp-dev* en una ventana de la Terminal.

7. Instale los módulos mediante `npm install`.

8. Digite el comando `gulp`. Debería abrir el sitio con browsersync y vigilando cambios.
