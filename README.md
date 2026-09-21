# HCIA-Datacom Anki Flashcards

Colección de flashcards atómicas para la preparación de la certificación Huawei HCIA-Datacom mediante repetición espaciada en Anki.

## Filosofía de Atomicidad

Cada tarjeta está construida bajo el principio de **una sola idea y una sola respuesta**:

- **Sin definiciones genéricas:** Se evitan preguntas amplias (como "¿Qué es OSPF?") que fomentan respuestas vagas o memorización pasiva.
- **Enfoque examinable:** Cada tarjeta aborda un dato puntual y evaluable: estados de protocolos, tipos de paquetes, valores por defecto de Huawei (preferencias de ruta, temporizadores), formatos de cabeceras y comandos VRP.
- **Contexto autosuficiente:** Cada pregunta especifica claramente el protocolo o escenario para que no dependa de suposiciones ni pistas externas.
- **Evaluación binaria:** Si una pregunta requiere recordar dos conceptos independientes, se divide en dos tarjetas distintas. La respuesta debe ser inequívocamente correcta o incorrecta para que el algoritmo de repetición espaciada funcione con precisión.

## Criterios de Evaluación de Respuestas

Para que el algoritmo de repetición espaciada funcione con precisión, califica tus respuestas según estas pautas:

| Botón | Atajo | Criterio de uso |
| :--- | :---: | :--- |
| **Again** (Otra vez) | `1` | Respuesta incorrecta, no recordada o acertada por azar. |
| **Hard** (Difícil) | `2` | Respuesta correcta pero con esfuerzo mental considerable (>10 segundos o con duda). |
| **Good** (Bien) | `3` | Respuesta correcta con esfuerzo normal (2-5 segundos). Debe ser la opción en el 80% de los casos. |
| **Easy** (Fácil) | `4` | Respuesta inmediata, trivial y evidente. Usar con moderación (5-10% de los casos). |

### Reglas Fundamentales

- **No usar Hard tras un fallo:** Si la respuesta fue incorrecta, selecciona siempre Again. Usar Hard tras un fallo descalibra el intervalo del algoritmo.

- **Good es la opción predeterminada:** Si respondiste correctamente sin dificultad extrema, Good es la calificación correcta.

## Estructura

- `temas/`: Tarjetas de estudio en formato TSV organizadas por tema para importación directa a Anki.
- `README.md`: Documentación general del proyecto.