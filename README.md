# Centro de Saltillo · Plataforma de Análisis Urbano

**Integración de información territorial para la comprensión y toma de decisiones urbanas**
Gestión y administración de proyectos territoriales de inversión · Grupo 601 · Tecnológico de Monterrey

## Recorrido

| Archivo | Contenido |
|---|---|
| `index.html` | Portada y menú |
| `00_generalidades_sitio.html` | Generalidades del sitio. Lectura guiada y exploración libre |
| `01_sintesis.html` | Síntesis. Coincidencias entre las conclusiones de los equipos, con seguridad, paradas, vivienda y DENUE como contexto |
| **Diagnóstico urbano** | |
| `02_equipo1_medio_natural.html` | Equipo 1 · Riesgo e hidrología |
| `02b_equipo1_relieve_topografia.html` | Equipo 1 · Relieve y topografía |
| `02c_equipo1_temperatura_superficial.html` | Equipo 1 · Temperatura superficial e islas de calor |
| `03_equipo3_medio_construido.html` | Equipo 3 · Medio construido |
| `04_equipo2_movilidad_accesibilidad.html` | Equipo 2 · Movilidad |
| `04b_equipo2_patrimonio.html` | Equipo 2 · Patrimonio histórico y cultural |
| `04c_equipo2_vivienda_mercado.html` | Equipo 2 · Vivienda y mercado inmobiliario |
| `05_equipo5_medio_socioeconomico.html` | Equipo 5 · Medio socio-económico |
| `06_equipo4_oferta_turistica.html` | Equipo 4 · Oferta turística |
| `06b_equipo4_seguridad_intervencion.html` | Equipo 4 · Seguridad e intervención preventiva |
| `07_gobernanza_actores.html` | Gobernanza · Mapa de actores (propuesta docente por validar) |

## Estructura para publicar

Subir la carpeta completa a GitHub Pages.

- `data/atlas_comun.js` contiene los datos compartidos por `00`, `01` y `04c` (manzanas, vivienda INEGI, proyectos y DENUE). Sin este archivo esas páginas no cargan.
- `assets/equipo1/hillshade_contexto.png` es el relieve de `02` y `02b`.

Los archivos de trabajo de los equipos no forman parte del sitio.

## Área de estudio

Todas las capas por manzana usan las mismas 343 manzanas. La capa original del Equipo 1 tenía 346 unidades, que correspondían a 343 manzanas, 2 unidades fuera del polígono (ID 715 y 7588) y una manzana partida en dos fragmentos (ID 1574 y 2668). Se depuró a las 343 manzanas oficiales; la manzana partida conserva los atributos de su fragmento mayor.

## Síntesis (01)

Cada equipo aporta las manzanas a las que apunta su conclusión y el mapa cuenta cuántas lecturas coinciden en cada manzana.

| Equipo | Fuente | Regla |
|---|---|---|
| 1 · Medio natural | Conclusión del equipo | Manzanas prioritarias del escenario entregado (P70) en la mitad norte |
| 3 · Medio construido | Conclusión del equipo | 12 manzanas del escenario entregado (internet ≤ 70%, 600 a 850 m a parada) |
| 2 · Movilidad, patrimonio y mercado | Conclusión del equipo (integrada de sus cuadernos) | 30 por ciento de manzanas con más vivienda deshabitada, con 10 o más viviendas |
| 5 · Socio-económico | Conclusión del equipo | Manzanas en o sobre P70 del índice con la ponderación del equipo |
| 4 · Turismo y seguridad | Conclusión del equipo | Manzanas con al menos la mitad de su superficie en la Zona prioritaria 1 |

Las manzanas pueden colorearse por coincidencias, isla de calor o temperatura superficial 2025 (malla hexagonal del Equipo 1 recortada a las 343 manzanas). El contexto (seguridad del Equipo 4 con sus íconos, paradas, rutas, ciclovías, proyectos con oferta vigente y con ventas concluidas con su ficha fotográfica, y DENUE) no entra al conteo. El módulo móvil de proximidad es una propuesta del Equipo 4, no una instalación existente.

## Mapa de actores (07)

32 actores en seis sectores, con rol, poder e interés estimados, equipos relacionados y sede. Las sedes provienen del DENUE o del mapa del Equipo 4; los actores sin sede localizada aparecen solo en la lista. Poder e interés son una estimación inicial para validar con el grupo y el socio formador.

## Criterios generales

- Todos los mapas ofrecen Base clara y Satélite, y un botón para regresar al menú.
- Los cinco equipos tienen conclusión. La del Equipo 2 se integró a partir de los resultados calculados en sus cuadernos.
- Equipos 1, 3 y 5. El tramado rojo conserva el escenario entregado por el equipo y el tramado gris aparece al modificar pesos o umbral.
- Equipo 4. La incidencia delictiva permanece a escala municipal y no se extrapola como delito observado por manzana.
- En pantallas angostas los paneles pasan a una hoja inferior plegable y el control de capas se abre con el botón Capas.

## Equipos

- Equipo 1 · Medio natural. Luis Patricio Amaya Leal, David Enrique Arizpe Núñez, Emiliano Baeza Lara.
- Equipo 3 · Medio construido. Lorena Flores Ramos, Geovanna Lizeth Mena González.
- Equipo 2 · Movilidad, patrimonio y mercado inmobiliario. Hasiel Contreras Lucio, Andrea Valdés José, Fernanda Villanueva Hernández.
- Equipo 5 · Medio socio-económico. José María Culebro Cabral, André Manjarrez Chaparro, Jorge Javier Rodelo Espinoza.
- Equipo 4 · Especialización económica, turismo y seguridad. Carlos Andrés Contreras Galiano, Diane Valeria De León González, Luis Salvador Infante Hernández.

Docencia y acompañamiento en análisis geoespacial y cartografía interactiva, Juana Isabel Méndez Garduño. Coordinación académica, Katia Cuevas Sánchez. Socio formador, CFC.
