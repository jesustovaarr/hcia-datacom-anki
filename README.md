# HCIA-Datacom Anki Flashcards

Colección de flashcards atómicas para la preparación de la certificación Huawei HCIA-Datacom mediante repetición espaciada en Anki.


## Filosofía de Atomicidad

Cada tarjeta está construida bajo el principio de **una sola idea y una sola respuesta**:

- **Sin definiciones genéricas:** Se evitan preguntas amplias (como "¿Qué es OSPF?") que fomentan respuestas vagas o memorización pasiva.

- **Enfoque examinable:** Cada tarjeta aborda un dato puntual y evaluable: estados de protocolos, tipos de paquetes, valores por defecto de Huawei (preferencias de ruta, temporizadores), formatos de cabeceras y comandos VRP.

- **Contexto autosuficiente:** Cada pregunta especifica claramente el protocolo o escenario para que no dependa de suposiciones ni pistas externas.

- **Evaluación binaria:** Si una pregunta requiere recordar dos conceptos independientes, se divide en dos tarjetas distintas. La respuesta debe ser inequívocamente correcta o incorrecta para que el algoritmo de repetición espaciada funcione con precisión.


## Estructura

- `temas/`: Tarjetas de estudio en formato TSV organizadas por tema para importación directa a Anki.
- `README.md`: Documentación general del proyecto.