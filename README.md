# vasallo94 Claude Skills

Una colección de skills y comandos personalizados para **Claude Code**.

Estas skills están diseñadas siguiendo estándares de la industria (DevSecOps, Clean Code, Enterprise Architecture) para potenciar a Claude y estandarizar repositorios.

## Instalación rápida (One-Liner)

Para instalar una skill, usa el siguiente comando y pasa el nombre de la skill al final:

```bash
curl -sL https://raw.githubusercontent.com/Vasallo94/habilidades-especiales-ai/main/install.sh | bash -s -- <nombre_de_la_skill>
```

Se descargarán automáticamente en tu carpeta global de Claude (`~/.claude/commands/`) para que estén disponibles en todos tus proyectos.

## Catálogo de Skills

| Skill | Descripción | Instalación |
|---|---|---|
| **[mcp-builder](./skills/mcp-builder/README.md)** | Guía comprensiva y metodologías (4 Fases) para el desarrollo, revisión y evaluación de servidores de calidad para el Model Context Protocol (MCP). | `curl -sL https://raw.githubusercontent.com/Vasallo94/habilidades-especiales-ai/main/install.sh | bash -s -- mcp-builder` |

### 🔄 Actualización
Para mantener una skill actualizada con las últimas mejoras, simplemente **vuelve a ejecutar su comando de instalación**. El script descargará la versión más reciente de la rama `main` y sobrescribirá tu copia local.

> *Más skills portadas desde el vault de Obsidian próximamente.*

## Estructura del repositorio

- `/install.sh`: Script genérico de instalación.
- `/skills/`: Carpeta que contiene cada skill de forma individual y autocontenida.

## Contribución

Si creas nuevas skills útiles, ponlas en su propia carpeta bajo `/skills/` con su propio `README.md` (que explique qué hace y cómo se instala) y el archivo `SKILL.md`.
