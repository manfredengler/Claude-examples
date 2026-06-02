# Claude-examples

Página standalone con ejemplos reales de cada concepto clave del ecosistema Claude.

## 👁️ Ver la página

Abre **`index.html`** directamente en cualquier navegador (no requiere servidor).

## 📚 Conceptos cubiertos

| Concepto | Descripción |
|---|---|
| **Skills** | Capacidades reutilizables declaradas en el system prompt |
| **Tools** | Funciones externas que Claude puede invocar (JSON Schema) |
| **Commands** | Instrucciones `/slash` para activar comportamientos predefinidos |
| **Hooks** | Callbacks en puntos del ciclo de vida (PreToolUse, PostToolUse, Stop) |
| **Agents** | Claude en bucle autónomo percibe → razona → actúa |
| **Sub-Agents** | Agentes especializados orquestados en paralelo |
| **Harness** | Marco de pruebas con pytest y evaluación LLM-juez |
| **MCP** | Model Context Protocol – servidor y cliente con `FastMCP` |

## 🚀 Ejecutar los ejemplos de código

```bash
pip install anthropic mcp
python <nombre_del_archivo>.py
```

Necesitarás una `ANTHROPIC_API_KEY` exportada como variable de entorno.