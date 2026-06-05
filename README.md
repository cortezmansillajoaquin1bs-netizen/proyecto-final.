# Simulador Web de Crisis Económica: Precios de Alimentos
**Proyecto Final - Programación Web I**

## 1. Descripción del Proyecto
Este proyecto es una aplicación web interactiva diseñada para simular problemas reales del contexto actual, específicamente el incremento de precios en los productos de la canasta familiar. La herramienta permite a los usuarios calcular el impacto financiero de la inflación y la pérdida del poder adquisitivo mediante modelos matemáticos sencillos.

## 2. Tecnologías Utilizadas
Para el desarrollo de este desafío se han aplicado las siguientes tecnologías:
* **HTML5 Semántico**: Uso de etiquetas claras para una estructura organizada.
* **CSS3 (Diseño Responsivo)**: Estilos ordenados por secciones y adaptabilidad a dispositivos móviles (celular y tablet) mediante Media Queries.
* **JavaScript (Manipulación del DOM)**: Lógica para capturar datos, validar entradas, realizar cálculos matemáticos y cambiar estilos dinámicamente según los resultados.
* **GitHub Pages**: Plataforma para la publicación en internet.

## 3. Escenario Simulado (Escenario B)
Se ha seleccionado el simulador de **precios de alimentos**, el cual permite ingresar:
* Nombre del producto.
* Precio anterior y precio actual.
* Cantidad consumida por semana y número de semanas.

El sistema devuelve el incremento por unidad, el porcentaje de aumento, el gasto adicional y una **clasificación de nivel de gasto** (Bajo, Medio o Alto) que altera visualmente la interfaz de resultados.

## 4. Estructura de Carpetas
```text
proyecto-web-crisis/
│
├── index.html          # Estructura principal
├── css/
│   └── estilos.css     # Estilos y media queries
├── js/
│   └── script.js       # Lógica y DOM
├── img/
│   └── contexto-mercado.jpg  # Imagen ilustrativa
└── README.md           # Documentación
```
5. Instrucciones para Pruebas
Casos de Estudio verificables directamente en la página web:

Producto: Arroz | Precio Anterior: 8 Bs | Precio Actual: 11 Bs | Cantidad: 10.

Resultado esperado: Gasto total anterior 80 Bs, Gasto actual 110 Bs, Diferencia +30 Bs.

