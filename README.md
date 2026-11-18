# skills-ofimatica-documentos

Repertorio de Skills de Ofimática y Automatización Documental en Python/Node: PDF, Word (DOCX), Planillas Excel (XLSX con openpyxl) y Presentaciones (PPTX).

## Skills Incluidas (4)

| Skill (`SKILL.md`) | Descripción y Disparador | Comando Upstream (`npx skills`) |
| :--- | :--- | :--- |
| `pdf` | Read, create, merge, split, fill forms, extract tables, and OCR PDF files using Python libraries (pypdf, pdfplumber, reportlab, pypdfium2). | `npx skills add anthropics/skills --skill pdf` |
| `docx` | Create, read, edit, or manipulate Word documents (.docx) and templates (.dotx), including tables, headings, tracked changes, and OpenXML validation. | `npx skills add anthropics/skills --skill docx` |
| `xlsx` | Open, clean, build, and edit .xlsx, .csv, and .tsv spreadsheets with dynamic Excel formulas, openpyxl template preservation, and zero formula errors. | `npx skills add anthropics/skills --skill xlsx` |
| `pptx` | Build, read, and edit PowerPoint decks (.pptx) and templates (.potx) with python-pptx or pptxgenjs and visual slide validation. | `npx skills add anthropics/skills --skill pptx` |

## Cómo usar este repositorio en Cursor AI y Gemini CLI

1. **Instalación directa desde tu repositorio en cualquier proyecto nuevo:**
   ```bash
   npx skills add felipeponce926-max/skills-ofimatica-documentos --all
   ```
2. **Instalación global en tu equipo (disponible en todos tus proyectos de Cursor):**
   ```bash
   npx skills add -g felipeponce926-max/skills-ofimatica-documentos --all
   ```
3. **Estructura incluida:**
   - `skills/<skill>/SKILL.md`: Estructura estándar para distribución con `npx skills` y `gemini skills install`.
   - `.agents/skills/<skill>/SKILL.md` y `.cursor/skills/<skill>/SKILL.md`: Detección inmediata al abrir el repositorio en Cursor AI o Antigravity/Gemini CLI.
