# DERRE_hackods - Tablero Interactivo

## Equipo DERRE - Integrantes
| Emilio Axel Salas Palacios |

| Claudio Flores Guzmán |

| Angel Noel Pérez Martínez |

---

## ODS seleccionados

-**[ODS 14] - [Vida Submarina]**
  
Se eligió este ODS porque nuestro análisis se centra en evaluar la sostenibilidad del uso de los recursos marinos en Baja California. A partir de datos de actividad pesquera y biodiversidad, buscamos entender si la presión humana está afectando la salud del ecosistema y su capacidad de recuperación, lo cual es un objetivo central del ODS 14.

---

## Descripción del proyecto 

**¿Puede la biodiversidad marina recuperarse del crecimiento pesquero en Baja California, o los datos evidencian que se ha alcanzado un punto de no retorno ecológico?**

El Golfo de California es una de las regiones marinas más biodiversas del mundo, albergando cientos de especies de peces, mamíferos marinos como la Ballena gris, y miles de invertebrados.

Al mismo tiempo, es un pilar económico fundamental, ya que concentra una gran proporción de la producción pesquera nacional y genera sustento para decenas de municipios costeros, con cientos de miles de empleos directos e indirectos.

Esta dualidad lo convierte en un caso crítico donde coexisten la conservación de la biodiversidad y la explotación económica de los recursos marinos.

A partir de datos históricos (1980–2020), analizamos la relación entre la presión pesquera —medida a través de la producción y el número de embarcaciones— y la biodiversidad, representada por especies indicadoras como pelícanos y ballenas.

Esta relación permite observar cómo la actividad humana impacta distintos niveles del ecosistema, desde zonas costeras hasta el entorno oceánico.

Los patrones identificados en los datos sugieren fluctuaciones en la biodiversidad que podrían estar asociadas tanto a la intensidad de la actividad pesquera como a factores externos, lo que abre la posibilidad de identificar señales de deterioro progresivo o pérdida de equilibrio ecológico.

De esta manera, el análisis se vincula directamente con el ODS 14 (Vida submarina), al evaluar si el aprovechamiento de los recursos marinos ha sido sostenible en el tiempo.



---

## Selección y calidad de los datos 

La selección de estos datos responde a la necesidad de analizar el ecosistema marino desde una perspectiva integral, combinando variables de presión humana con indicadores biológicos.

Por un lado, la producción pesquera y el número de embarcaciones permiten cuantificar la intensidad de la actividad pesquera y su evolución en el tiempo, reflejando cambios en la capacidad extractiva, condiciones económicas y políticas del sector.

Por otro lado, las poblaciones de pelícanos y ballenas fueron seleccionadas por su valor como especies indicadoras. En particular, el pelícano pardo es considerado una especie centinela debido a su dependencia de peces pelágicos, lo que permite inferir cambios en la productividad del ecosistema.

De manera complementaria, la ballena gris refleja condiciones ecológicas a mayor escala, ya que su abundancia depende de factores como la disponibilidad de alimento, condiciones oceanográficas y presiones antropogénicas.

Con los datos de lobos marinos pasa algo distinto, ya que utilizaremos estos datos para dar una conclusión y utlizarlos como evidencia de que puede existir un cambio real, ya que dichos datos son de lobos marinos que habitan en una zona protegida.

En conjunto, estos datos permiten analizar la interacción entre actividad económica y biodiversidad, proporcionando evidencia para evaluar si el sistema se mantiene en equilibrio o si presenta señales de deterioro, en línea con los objetivos del ODS 14.

Todos nuestros datos fueron obtenidos a través de la plataforma oficial de la SEMARNAT (https://www.gob.mx/semarnat), la cual concentra información estadística ambiental generada en colaboración con instituciones como CONANP y CONAPESCA.

Esta plataforma garantiza la confiabilidad de los datos, ya que provienen de monitoreos sistemáticos, anuarios estadísticos y programas oficiales de seguimiento de biodiversidad y actividad pesquera en México, lo que permite su uso para análisis consistentes y alineados con el ODS 14.

Para más información revisar la carperta de datos para metadatos individuales.

---
## Instrucciones de Ejecución

Este repositorio contiene un dashboard desarrollado con Quarto. El proyecto está configurado para desplegarse automáticamente en GitHub Pages mediante un workflow, pero también puede ejecutarse localmente siguiendo los pasos a continuación.

Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

Python 3.12
Quarto (versión 1.6.0 o compatible)
uv

Ejecución en local
Clonar el repositorio:
git clone <URL-del-repositorio>
cd <nombre-del-repositorio>/dashboard
Instalar dependencias de Python:
pip uv install jupyter nbformat pandas matplotlib plotly
Renderizar el dashboard:
quarto render

Esto generará los archivos estáticos en la carpeta :  (puede tardar varios minutos)

dashboard/_site/
Visualización del dashboard

Puedes visualizar el dashboard de dos formas:

Opción 1

quarto preview

Opción 2

Abrir manualmente el archivo:

dashboard/_site/index.html

Notas importantes

El proyecto se renderiza dentro de la carpeta dashboard/, tal como está configurado en el workflow.
Todas las dependencias necesarias están especificadas explícitamente para asegurar reproducibilidad.
El resultado final es un sitio estático, compatible con GitHub Pages.
No se requieren configuraciones adicionales ni variables de ento
