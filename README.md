# QRGen

Este proyecto es una aplicación desarrollada en **Visual Basic .NET** con **Windows Forms**, creada originalmente para la **impresión de etiquetas en diversas líneas de producción**.  
En esta nueva versión, se realizó una **actualización significativa** para **incluir la impresión de un nuevo tipo de etiquetas destinadas al área de preparación**, con el propósito de **facilitar el ingreso de materiales al almacén**.

<p align="center"><img width="500" height="477" alt="Copia de QRGen" src="https://github.com/user-attachments/assets/abbba3d9-e32a-4d6c-a9ed-a8d58fa3ed25" /></p>

## Descripción

El programa original permitía generar e imprimir etiquetas de identificación para productos de diferentes líneas de producción.  
Con esta actualización, el sistema ahora **gestiona la creación de órdenes de producción específicas para el área de preparación**, generando e imprimiendo etiquetas que reflejan la cantidad de piezas que serán almacenadas.

Cada solicitud de impresión genera automáticamente una **nueva orden de producción**, la cual se **registra en la base de datos** para mantener un historial completo de las etiquetas impresas y los lotes enviados a almacén.

## Nuevas funcionalidades implementadas

- **Impresión de nuevas etiquetas para el área de preparación.**  
- **Generación automática de órdenes de producción** al solicitar una impresión.  
- **Registro de cada orden en la base de datos**, permitiendo trazabilidad total.  
- **Control de cantidad de piezas por orden**, asociando cada etiqueta al número de piezas del lote.  
- **Cálculo automático del número de etiquetas a imprimir** según la cantidad del maso.  
- **Compatibilidad con las etiquetas existentes** sin alterar las funciones previas del sistema.  
- **Mejoras en la interfaz** para una selección más intuitiva del tipo de etiqueta y línea de producción.

## Tecnologías utilizadas

- **Visual Basic .NET (Windows Forms)**  
- **MySQL**  
- **.NET Framework**  
- **Controladores de impresora térmica** (para la generación de etiquetas)

## Objetivo

Extender las capacidades del sistema de impresión de etiquetas para cubrir las necesidades del área de preparación, **permitiendo la trazabilidad, control y registro automático de las órdenes de producción** destinadas a almacenaje.

## Notas importantes

Debido a la naturaleza privada de la información que se maneja dentro de este programa, no es posible revelar más detalles sobre el código ni ejemplos verdaderos de su uso. Por ello, la información mostrada en las imágenes es ficticia y no representa a nadie en particular. Este es un repositorio de muestra; los archivos aquí guardados no contienen mayor información y el proyecto original se encuentra alojado dentro de un repositorio privado.
