# Xbox 360 BadUpdate 1.3 + XeUnshackle USB Setup

Proyecto creado para facilitar la preparación y comprensión del proceso de uso de **BadUpdate 1.3** junto con **XeUnshackle** en Xbox 360.

> [!IMPORTANT]
> Este repositorio **no es BadUpdate ni XeUnshackle**, no pretende atribuirse el trabajo de sus desarrolladores y no está afiliado con Microsoft o Xbox.  
> Todo el mérito de los exploits, parches y herramientas originales corresponde a sus respectivos autores y colaboradores.

✅ Enlace: https://thewizwikii.github.io/BadUpdateUSBSetup/

## ¿Qué es este proyecto?

La idea de este repositorio es ofrecer una interfaz sencilla y visual, con estética inspirada en Xbox, para ayudar a preparar un dispositivo USB y reunir en un mismo lugar la información necesaria para utilizar **BadUpdate** junto con **XeUnshackle**.

La web puede comprobar si en la carpeta seleccionada existe la estructura básica esperada, como:

```text
USB:/
├── BadUpdatePayload/
│   └── default.xex
└── Content/
```

También puede proporcionar un enlace a un paquete preparado por el responsable de este repositorio.

Por las restricciones de seguridad de los navegadores, la web **no puede formatear directamente un pendrive ni comprobar de forma fiable que su sistema de archivos sea FAT32**. El dispositivo debe prepararse manualmente cuando sea necesario.

## BadUpdate

**Xbox360BadUpdate**, creado por **grimdoomer**, es un exploit de hypervisor para Xbox 360 basado únicamente en software.

El proyecto oficial indica que:

- funciona sobre el dashboard **17559**;
- permite ejecutar código no firmado;
- utiliza **Rock Band Blitz** como uno de sus puntos de entrada;
- no requiere abrir la consola ni realizar soldaduras;
- **no es persistente**: al apagar o reiniciar la Xbox 360 hay que volver a ejecutar el exploit.

Este proyecto utiliza como referencia **BadUpdate v1.3**.

### Proyecto original

https://github.com/grimdoomer/Xbox360BadUpdate

### Release BadUpdate v1.3

https://github.com/grimdoomer/Xbox360BadUpdate/releases/tag/BadUpdate-v1.3

## XeUnshackle

**XeUnshackle**, desarrollado por **Byrom90**, es una aplicación para Xbox 360 creada específicamente para utilizarse junto con Xbox360BadUpdate.

Entre las funciones documentadas por su proyecto se encuentran la aplicación temporal de parches de HV y Kernel, soporte para ejecutables XEX Retail y Devkit y la carga de una versión modificada de **Dashlaunch**.

XeUnshackle tampoco convierte la modificación en permanente. Al apagar o reiniciar la consola, esta vuelve a su estado sin modificar.

> [!WARNING]
> XeUnshackle se distribuye tal cual y su desarrollador advierte expresamente de los riesgos de modificar la NAND/FLASH. Consulta siempre la documentación original antes de utilizarlo.

### Proyecto original

https://github.com/Byrom90/XeUnshackle

### Releases oficiales

https://github.com/Byrom90/XeUnshackle/releases

## Requisitos generales

Antes de seguir cualquier guía, consulta siempre los repositorios originales y sus notas más recientes.

Como referencia, BadUpdate requiere una Xbox 360 con dashboard **17559**, un dispositivo USB preparado correctamente y un método de entrada compatible como Rock Band Blitz.

Cualquier juego o contenido comercial necesario debe obtenerse legalmente.

## Advertencias

Este software y esta web se proporcionan con fines educativos y de homebrew.

El uso de exploits y aplicaciones no oficiales implica riesgos. Lee siempre la documentación original antes de continuar.

Especialmente:

- Haz una copia de seguridad de tu NAND cuando corresponda.
- **No flashees imágenes NAND modificadas utilizando XeUnshackle.**
- **No reemplaces archivos de FLASH.**
- Evita homebrew o plugins que modifiquen la NAND salvo que entiendas perfectamente sus consecuencias.
- Recuerda que BadUpdate y XeUnshackle trabajan de forma temporal y no equivalen a una modificación RGH permanente.
- Mantén la consola desconectada de Xbox Live cuando utilices este tipo de herramientas, siguiendo las advertencias de la documentación original.
- El responsable de este repositorio no se hace responsable de daños, pérdida de datos, bloqueos de consola o cualquier otra consecuencia derivada de su utilización.

## Créditos y agradecimientos

Este proyecto existe gracias al trabajo de la comunidad de Xbox 360.

### grimdoomer

Un agradecimiento enorme a **grimdoomer**, creador de **Xbox360BadUpdate**, por investigar y publicar el exploit que hace posible ejecutar código no firmado mediante software en Xbox 360.

Sin BadUpdate, este proyecto no tendría sentido.

Proyecto original:  
https://github.com/grimdoomer/Xbox360BadUpdate

### Byrom90

Muchísimas gracias a **Byrom90**, desarrollador de **XeUnshackle**, por adaptar y reunir los parches y herramientas necesarios para ampliar enormemente lo que podemos hacer después de ejecutar BadUpdate.

Proyecto original:  
https://github.com/Byrom90/XeUnshackle

### Comunidad y colaboradores

XeUnshackle reconoce además el trabajo de numerosos desarrolladores y miembros de la scene, incluyendo:

- **cOz** — xeBuild patches, Dashlaunch y otras contribuciones.
- **Visual Studio / Goobycorp**.
- **Diamond**.
- **InvoxiPlayGames / Emma** — FreeMyXe, parches Usbdsec, corrección del Ring of Light, DaTArrest y otras aportaciones.
- **ihatecompvir** — DaTArrest save exploit.
- **ikari** — freeBOOT.
- **Jeff Hamm** — Chain break video.
- **EatonZ** — Xbox 360 Bad Storage.
- **Xbox360Hub Discord #coding-corner**.
- Y todas las personas que durante años han contribuido a la scene de Xbox 360.

Para conocer los créditos completos y actualizados, consulta siempre el README oficial de XeUnshackle:

https://github.com/Byrom90/XeUnshackle#credits

## Respeta los proyectos originales

Si redistribuyes archivos procedentes de BadUpdate o XeUnshackle, **comprueba y respeta las licencias, avisos, condiciones y créditos de cada proyecto original**.

Este repositorio pretende facilitar el acceso a la información, no sustituir la documentación oficial ni apropiarse del trabajo de sus desarrolladores.

Si alguno de los proyectos originales recibe una actualización, la información de sus repositorios oficiales tiene siempre prioridad sobre este README.

## TheWizWiki

Proyecto preparado para la comunidad de **TheWizWiki**.

La intención es hacer que la scene y el homebrew sean más fáciles de entender, manteniendo siempre el reconocimiento a quienes realmente investigan, desarrollan y comparten estas herramientas.

**Gracias a grimdoomer, Byrom90 y a toda la comunidad de Xbox 360 por mantener viva esta consola tantos años después.**
