# Amplificador de Potencia de Audio Clase AB

Proyecto de diseño, simulación, implementación de circuito impreso (PCB) y caracterización experimental de un amplificador de audio de potencia con topología Clase AB push-pull y su fuente de alimentacion, desarrollado en el marco de la cátedra **Electrónica I** de la **Universidad Nacional del Nordeste (UNNE)**.

## Integrantes:

* **Guerrero, Agustín Exequiel**
* **Rolón, Juan Daniel**

## Descripción General y Especificaciones Técnicas

El sistema consiste en un amplificador integrado de dos etapas: una etapa preamplificadora basada en un amplificador operacional **NE5532** (en configuracion no inversora) seguida de una etapa de salida complementaria en configuración **Clase AB push-pull** con red de compensación de estabilidad de Zobel. El sistema de alimentacion del amplificador esta dado por una fuente de punto medio basada en el circuito doblador de tension de onda completa y regulada por diodos zener, se hace uso de transistores de paso.

* **Potencia de salida nominal:** 6,5 W
* **Ganancia de potencia total:** 60 dB
* **Ancho de banda (NOMINAL):** 20 kHz
* **Alimentación:** Fuente partida simétrica (+Vcc = 16V; -Vcc = 16V)
* **Tecnología de montaje:** Componentes de inserción sobre placa de circuito impreso de capa simple.
* **Rendimiento:** 50%

## Estructura del Repositorio

```text
├── KiCad/          # Archivos de proyecto, esquemáticos y diseño de PCB (.kicad_pro, .kicad_sch, .kicad_pcb)
├── Proteus/        # Modelos de simulación circuital y análisis en frecuencia/transitorio (.asc, .pdsprj)
├── Varios/         # Informe técnico, memorias de cálculo y hojas de datos de componentes
└── .gitignore      # Exclusión de archivos temporales y respaldos automáticos de software
