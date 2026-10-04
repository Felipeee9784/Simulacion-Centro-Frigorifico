# Diseño y Simulación Térmica de Centro Frigorífico de Distribución

Este repositorio contiene la memoria de cálculo, los scripts de simulación y el informe técnico del diseño de un centro frigorífico para la distribución de quesos y mantequilla en la ciudad de Quillota, Chile. El proyecto fue desarrollado para la asignatura de Equipos y Máquinas Térmicas (Universidad Técnica Federico Santa María).

## Descripción del Proyecto
El objetivo principal fue diseñar un centro logístico basado en racks dinámicos (sistema FIFO) que garantizara la preservación de los alimentos, asegurando que su temperatura central no varíe en más de 0,5 °C durante los procesos de *packing*. 

El modelado térmico transiente considera las condiciones climáticas más extremas de Quillota (enero) y evalúa las cargas térmicas por enfriamiento de producto, ocupación, iluminación, maquinaria, infiltraciones y transmisión.

## Herramientas Utilizadas
* **Engineering Equation Solver (EES):** Desarrollo de la tabla paramétrica y modelado transiente hora a hora (168 horas semanales).
* **Transferencia de Calor:** Cálculo de conducción transiente en cilindros equivalentes (Números de Fourier, Biot y aproximación de Heisler).
* **Psicrometría:** Análisis de entalpía y densidad de mezclas aire-vapor de agua para el cálculo de infiltraciones.
* **Evaluación Financiera:** Estimación de OPEX y CAPEX para la selección del sistema frigorífico centralizado.

##  Autores y Responsabilidades
Este proyecto fue un esfuerzo colaborativo. Las responsabilidades se dividieron de la siguiente manera:
* **Felipe Campos Calderón:** Modelado matemático de conducción térmica transiente, determinación de la temperatura crítica de la sala de *packing* (-3,04 °C) y desarrollo completo del script en EES para la evaluación de las cargas térmicas hora a hora.
* **Melannie Gajardo:** Selección del equipamiento frigorífico (compresores semi-herméticos, evaporadores cúbicos y condensador remoto) y evaluación económica detallada (CAPEX/OPEX).

## 📂 Archivos del Repositorio
* `Memoria_de_Calculo_Quillota.EES`: Script principal con el balance térmico transiente.
* `Informe_Técnico_Quillota.pdf`: Reporte técnico final con justificaciones teóricas, gráficos de evolución térmica y selección de equipos.
