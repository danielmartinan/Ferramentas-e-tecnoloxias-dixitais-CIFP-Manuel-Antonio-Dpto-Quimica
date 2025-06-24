# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## Ferramentas de produtividade e automatización

### Que entendemos por produtividade e automatización?

- **Ferramentas de produtividade**
  Aplicacións que axudan a planificar, organizar, documentar e compartir tarefas ou coñecemento. Buscan reducir tempo “administrativo” e mellorar a colaboración.
- **Ferramentas de automatización**
  Plataformas ou servizos que executan fluxos de traballo sen intervención humana (ou con mínima supervisión). Poden ser:
    - **No-code / low-code**: integran aplicacións na nube (ex. Make, Zapier).
    - **RPA / fluxo industrial**: automatizan accións en software ou controlan dispositivos físicos (ex. UiPath, Node-RED).

A combinación de ambas permite dedicar máis tempo á análise, á docencia e á mellora continua.

### Tipos de ferramentas de produtividade recomendadas

| Tipo                       | Ferramentas destacadas                 | Uso típico en FP e proxectos químicos                                         |
| -------------------------- | -------------------------------------- | ----------------------------------------------------------------------------- |
| Xestión de proxectos       | Trello, Microsoft Planner, Jira, Asana | Taboleiros Kanban para tarefas do laboratorio, control de prazos de prácticas |
| Xestión de coñecemento     | Notion, Obsidian, Confluence, GitBook  | Manual de operacións de equipos, guía de seguridade, apuntes compartidos      |
| Suite colaborativa na nube | Google Workspace, Microsoft 365, Zoho  | Redacción compartida de informes, follas de cálculo de resultados analíticos  |
| Documentación técnica      | Markdown + LaTeX ↔ VSCode, HackMD      | Informes con código, fórmulas químicas e gráficos exportados a PDF            |
| Control de versións        | GitHub, GitLab, Azure DevOps           | Historial de scripts de laboratorio, configuracións de PLC, contidos docentes |

> **Boas prácticas**
>
> - Empregar etiquetas ou estados (Por facer → En progreso → Feito).
> - Crear plantillas (ex. ficha de práctica) para homoxeneizar documentos.
> - Definir roles: responsable de proxecto, revisores, autores.

### Tipos de ferramentas de automatización recomendadas

| Categoría                         | Ferramentas exemplo                              | Aplicación didáctica / industrial                                                        |
| --------------------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| **Integración na nube** (no-code) | Make, Zapier, Power Automate, IFTTT              | Se un alumno entrega un formulario → gárdase en Notion + envíase correo de confirmación  |
| **Fluxos IoT / IIoT**             | Node-RED, ThingsBoard, Losant                    | Sensor de pH → Node-RED → gráfico en tempo real + alerta Telegram                        |
| **RPA**                           | UiPath, Automation Anywhere                      | Rexistro automático de datos en ERP dende PDFs de ensaio                                 |
| **Simulación industrial**         | Factory I/O, PLC-SIM (Siemens), OpenPLC, Codesys | Proba dunha secuencia de enchido de tanques sen parar a planta real                      |
| **Orquestración de datos**        | Apache NiFi, Airflow                             | Pipeline que colle datos de sensores, almacénaos en data lake, lanza notebook de análise |

### Casos de uso no ámbito químico

1. **Taboleiro Kanban de laboratorio**

   - Trello con columnas “Preparación”, “Ensaios”, “Resultados”, “Limpieza”.
   - Tarxetas con checklist de EPIs, volumes, reactivos.

2. **Dashboard en Notion para proxecto de dixitalización**

   - Base de datos de tarefas + galería de recursos (fichas de sensores, datasheets).
   - Ligazón a informes en PDF xerados con Markdown/LaTeX.

3. **Fluxo Make + Google Sheets**

   - Cando o PLC envía un correo coa lectura diaria → Make extrae datos → engádeos nunha folla de cálculo compartida para análise posterior.

4. **Node-RED en aula**

   - Simulación dun reactor: slider de temperatura → se > 80 °C dispara alarma e rexistra evento nunha base MongoDB.

### Metodoloxía para implantar estas ferramentas

1. **Mapear o proceso**

   - Identificar tarefas repetitivas, fontes de datos e puntos de dor (tempo, erros, duplicidades).

2. **Seleccionar a ferramenta axeitada**

   - Criterios: facilidade de uso, custo, compatibilidade con políticas de centro, privacidade.

3. **Prototipar en pequeno**

   - Crear un fluxo mínimo viable (ex. un gatillo + dúas accións).
   - Probar con datos ficticios antes de pasar a produción.

4. **Formar ao equipo**

   - Mini-guía paso a paso (vídeo curto ou captura de pantalla).
   - Sesión de dúbidas e melloras continuas.

5. **Medir e iterar**

   - Definir indicadores: tempo aforrado, erros reducidos, satisfacción do usuario.
   - Revisar trimestralmente e escalar se procede.

### Actividade práctica suxerida

**Título:** Automatiza a túa ficha de práctica química

1. **Escenario**

   - Google Form recolle resultados dun ensaio.
   - Obxectivo: gardar automaticamente cada resposta nunha base de datos de Notion e enviar resumo ao correo do profesor.

2. **Pasos**

   1. Crear o formulario (Google Forms).
   2. Configurar un *gatillo* en Make “New Response in Spreadsheet”.
   3. Acción 1 → Crear rexistro en Notion (base de datos “Ensaios 2025”).
   4. Acción 2 → Enviar correo con resumo e ligazón ao rexistro.

3. **Entrega**

   - Captura de pantalla do fluxo e demostración en directo.
   - Reflexión escrita: beneficios, posibles melloras, riscos de seguridade.

### Recursos e tutoriais recomendados

- **Make para educación:** [https://www.make.com/en/education](https://www.make.com/en/education)
- **Guía Node-RED oficial:** [https://nodered.org/docs/](https://nodered.org/docs/)
- **Trello Education Templates:** [https://trello.com/templates/education](https://trello.com/templates/education)
- **Notion para docentes:** [https://www.notion.so/pt-br/educators](https://www.notion.so/pt-br/educators)
- **UiPath Academic Alliance:** recursos gratuítos para FP
- **Vídeos Factory I/O – procesos químicos simulados:** canle YouTube oficial

### Conclusións clave

- As ferramentas de produtividade optimizan o tempo e melloran a colaboración; as de automatización liberan da execución manual de tarefas repetitivas.
- Escoller a solución adecuada require entender o *fluxo de valor* do proceso.
- Nun ciclo de FP de química, permiten integrar prácticas reais de dixitalización con custe reducido e alto impacto pedagóxico.
- A aprendizaxe destas ferramentas capacita ao alumnado para contornas industriais modernas, onde a eficiencia e a trazabilidade son esenciais.
