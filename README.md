# OUCRAC
Muestra las notas del RAC en "Mi UOC"

**Pasos para agregar el visor al campus:**
1. Acceder al campus.
2. Pulsar sobre el botón 'añadir información'.
3. Seleccionar la pestaña 'Módulos externos'.
4. Presionar el botón 'pon un módulo propio'.
5. Cubrir el formulario con el siguiente contenido:
6. **Título:** RAC
7. **Código HTML:** El texto que contiene el archivo rac.html ([enlace](https://raw.githubusercontent.com/davidcmg/OUCRAC/master/rac.html "RAC")).


**Activar o desactivar comentarios**

Por defecto los comentarios aparecen activados, para desactivarlos hay que cambiar la línea
```javascript
var op_comentarios = true;
```
por
```javascript
var op_comentarios = false;
```
