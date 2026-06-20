🏛️ Monitor del Boletín Oficial - Argentina

📌 *Descripción del Proyecto*

Herramienta de recolección de datos (Web Scraper) diseñada para automatizar la lectura y extracción de normativas de la Primera Sección del Boletín Oficial de la República Argentina.

Este proyecto busca generar una alternativa agil y eficiente a la búsqueda manual de normativas, procesando el texto completo de los decretos y resoluciones para aislar y exportar únicamente aquellos que contienen designaciones de cargos públicos.

🛠️ *Tecnologías Utilizadas*
* **Lenguaje:** Python 3
* **Librerías de Extracción:** `requests`, `BeautifulSoup` (bs4)
* **Procesamiento de Datos:** `pandas`
* **Control de Flujo:** `time` (para manejo ético de peticiones al servidor)

🚀 Roadmap / Próximos Pasos
Este proyecto se encuentra en desarrollo. Las próximas actualizaciones buscarán incluír:
- [ ] Integración de expresiones regulares (`re`) para extraer números de DNI y niveles salariales.
- [ ] Implementación de `spaCy` (NLP) para el reconocimiento automático de los nombres propios de los funcionarios designados.
- [ ] Extracción de datos desde anexos en formato PDF (`PyPDF2`).
