# Modelo Canvas

Página web estática educativa que presenta el **Modelo Canvas** de forma interactiva: una imagen mapa con áreas clicables que permiten recorrer cada uno de los nueve bloques del modelo en páginas independientes.

## Contenido

El mapa enlaza a los nueve pasos del modelo:

- **Paso 1:** Segmentos de clientes
- **Paso 2:** Propuesta de valor
- **Paso 3:** Canales de distribución y comunicaciones
- **Paso 4:** Relación con el cliente
- **Paso 5:** Flujos de ingreso
- **Paso 6:** Recursos clave
- **Paso 7:** Actividades clave
- **Paso 8:** Red de partners
- **Paso 9:** Estructura de costos

## Estructura del proyecto

```
modelo_canvas/
├── index.html    # Portada con el mapa de imagen interactivo
├── paso_1.html   # Segmentos de clientes
├── paso_2.html   # Propuesta de valor
├── paso_3.html   # Canales de distribución y comunicaciones
├── paso_4.html   # Relación con el cliente
├── paso_5.html   # Flujos de ingreso
├── paso_6.html   # Recursos clave
├── paso_7.html   # Actividades clave
├── paso_8.html   # Red de partners
├── paso_9.html   # Estructura de costos
├── style.css     # Hoja de estilos
├── img/          # Lienzo del modelo e ilustraciones de cada bloque
└── iconos/       # Iconos (Bootstrap Icons)
```

## Uso

No requiere instalación ni servidor. Abre el archivo `index.html` directamente en cualquier navegador web y haz clic sobre las áreas del mapa:

```powershell
Start-Process "index.html"
```

## Estilos

Todo el sistema vive en `style.css`, organizado por secciones (variables, base, portada, ficha, pie, móvil). No usa fuentes ni librerías externas.

- **Paleta:** fondo cálido plano `#fbf4e6`, texto `#2b2620`, acento dorado `#b5810e` y acento vino `#6b2a2a`.
- **Tipografía:** pila del sistema (`system-ui, "Segoe UI", …`), escala modular y medida de lectura de 68 caracteres.
- **Bloques:** cada uno de los nueve bloques tiene su color tomado del propio gráfico (variables `--b1` … `--b9`), usado como guía en el índice y en la ficha de cada página.
- **Portada:** el lienzo (`img/modelo-canvas.png`) con su mapa de imagen accesible por áreas rectangulares y un índice de los nueve bloques.
- **Ficha:** cada `paso_N.html` comparte un mismo shell con barra de regreso, figura, texto y navegación anterior/siguiente.
- Respeta `prefers-reduced-motion` y mantiene el foco visible para navegación por teclado.

## Autor

Jhoam Sebastian Muñoz B, Gisela Rivera, Maria Camila Uribe, Cristian Camilo Muñoz B, Estefania Nieto y Christian Zambrano. Todos los derechos reservados.
