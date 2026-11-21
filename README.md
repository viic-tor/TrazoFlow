# TrazoFlow

Manual operativo interactivo en estética **hacker monocromo (blanco y negro)** para la CLI y skill de agentes [**Trazo**](https://github.com/heidenber/trazo) (`@heidenber/trazo`).

## Qué incluye

- **Capacidades completas de Trazo y su Skill (`SKILL.md` / `AGENTS.md`)** y las 8 reglas del protocolo para agentes de IA.
- **Explorador de los 4 tipos de diagrama** (`architecture`, `workflow`, `erd`, `sequence`) con diagramas ASCII, reglas estrictas y ejemplos JSON validados con `trazo check`.
- **Guía paso a paso de instalación** para **Linux (Bash/Zsh)**, **Windows (PowerShell 5.1/7+)** y compilación desde fuente, incluyendo resolución de problemas reales (`ExecutionPolicy`, UTF-16 BOM, `EACCES`, `nvm`).
- **Generador interactivo de comandos CLI** y referencia de la API Node.js ESM (`check`, `make`).
- **Controles y atajos del visor HTML**, **tabla filtrable de errores y warnings geométricos**, **benchmarks**, **checklist interactivo de auditoría** y **playbook de prompts**.
- **100% estático y autocontenido** (`index.html`, cero dependencias externas), con barras de scroll monocromas personalizadas, riel de progreso, HUD flotante de desplazamiento y conmutador de tema `B/N ↔ N/B` + `SCANLINES`.

## Uso local

Abre `index.html` directamente en cualquier navegador o sirve la carpeta con cualquier servidor estático:

```sh
npx serve .
```
