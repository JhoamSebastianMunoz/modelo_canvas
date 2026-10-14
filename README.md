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
├── img/          # Imágenes del mapa, fondos e ilustraciones
└── iconos/       # Iconos (Bootstrap Icons)
```

## Uso

No requiere instalación ni servidor. Abre el archivo `index.html` directamente en cualquier navegador web y haz clic sobre las áreas del mapa:

```powershell
Start-Process "index.html"
```

## Estilos

Los estilos se definen en `style.css` e incluyen:

- Fondo `wheat` con imagen fija (`img/fondo.jpg`) y tipografía `Arial, Helvetica, sans-serif`.
- Imagen del mapa al 70% del ancho con bordes redondeados (`.imgCanvas`).
- Bloques de contenido con sombra y bordes redondeados (`.bloquePaso7`, `.divimg`).
- Sombras de texto doradas en los títulos (`h1`, `h2`).

## Autor

Jhoam Sebastian Muñoz B, Gisela Rivera, Maria Camila Uribe, Cristian Camilo Muñoz B, Estefania Nieto y Christian Zambrano. Todos los derechos reservados.
