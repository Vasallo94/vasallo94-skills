# mcp-builder

Guía comprensiva y herramientas para la creación de servidores MCP (Model Context Protocol) de alta calidad. 

## Instalación

```bash
curl -sL https://raw.githubusercontent.com/Vasallo94/vasallo94-skills/main/install.sh | bash -s -- mcp-builder
```

## Cuándo usar esta skill
- Cuando estés desarrollando un servidor MCP desde cero o manteniendo uno existente.
- Para integrar APIs externas o servicios (en Python con FastMCP o en Node/TypeScript con el SDK oficial).
- Para evaluar la efectividad y el diseño de tus herramientas y recursos MCP.

## Qué hace

Extraída directamente de la documentación interna, esta skill te proporciona el flujo de trabajo en 4 fases para crear servidores MCP excelentes:

1. **Fase 1: Investigación Profunda y Planificación**
   Ayuda a decidir entre herramientas de flujo de trabajo vs endpoints de API crudos, nombrar herramientas, manejar el contexto, y entender el protocolo.
2. **Fase 2: Implementación**
   Recomendaciones nativas de stack (TypeScript o Python), estructuración, schematización de I/O con Zod/Pydantic y manejo de errores accionables.
3. **Fase 3: Revisión y Pruebas**
   Criterios de calidad exhaustivos y comandos para el MCP Inspector.
4. **Fase 4: Evaluaciones**
   La metodología exacta para crear 10 preguntas de prueba (QA pairs) que validen que un LLM puede usar tu MCP exitosamente para resolver problemas complejos reales.

## Ejemplo de uso

Abre tu editor en la carpeta donde crearás el servidor MCP:
```bash
claude
# Y una vez dentro pide ayuda:
> Ayúdame a diseñar un servidor MCP para GitHub usando el mcp-builder. ¿Por dónde empezamos?
```
