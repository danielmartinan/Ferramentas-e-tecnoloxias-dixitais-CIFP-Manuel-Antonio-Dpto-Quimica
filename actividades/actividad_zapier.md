# Actividad: automatización con Zapier

## Escenario: Registrar en Google Sheets cada archivo nuevo añadido a Google Drive (con Zapier)

### ¿Qué necesitamos?

- Cuenta gratuita en [Zapier](https://zapier.com/)
- Cuenta de Google
- Carpeta en Google Drive para la automatización
- Hoja de cálculo de Google Sheets (puede crearse desde Zapier)

## Paso a paso: Automatización en Zapier

### 1. Entra en Zapier y crea un nuevo **Zap**

- Ve a [https://zapier.com/app/zaps](https://zapier.com/app/zaps)
- Haz clic en **“Create Zap”**

### 2. Configura el **disparador (Trigger)**

- En el paso **Trigger**, elige la app: **Google Drive**
- Elige el evento:
  **“New File in Folder”**
- Conecta tu cuenta de Google
- Configura la carpeta que deseas supervisar (igual que en IFTTT)

### 3. Añade un **filtro (opcional, pero muy útil)**

Zapier permite añadir filtros sin código. Por ejemplo:

- Solo registrar archivos `.pdf`
- Solo registrar archivos con nombres que contengan cierta palabra (ej. “practica”)

Esto no es posible con IFTTT de forma directa en su plan gratuito.

#### ¿Dónde y cómo configurar condiciones (filtros) en Zapier?

Requisitos:

- Debes estar usando el **Editor clásico** de Zapier.
- Es una función disponible incluso en el **plan gratuito** si usas solo 1 filtro por zap.

**Después del trigger**, haz clic en el botón con el símbolo **"+"** para añadir un nuevo paso. Se abrirá una ventana para elegir qué tipo de paso quieres añadir. Elige:

   ```
   Filter by Zapier
   ```

   Esta es la herramienta que permite configurar **condiciones lógicas**.

**Configura tu condición**:

- En el primer menú desplegable, selecciona el **campo** del trigger (por ejemplo: `File Name`)
- En el segundo, selecciona el operador lógico (por ejemplo: `Contains`)
- En el tercero, escribe el valor (por ejemplo: `informe`)

1. Luego de configurar el filtro, **añades la acción final** (por ejemplo: registrar en Google Sheets).

#### Alternativas más avanzadas (requieren plan de pago)

Si quieres condiciones más complejas (por ejemplo, múltiples filtros con `AND`/`OR`, lógica condicional encadenada…), Zapier lo permite, pero con herramientas como:

- **Paths by Zapier** (ramificaciones)
- **Code by Zapier** (scripts Python/JavaScript)
- **Formatter by Zapier** (para transformar datos antes del filtro)

### 4. Configura la **acción (Action)**

- Elige la app: **Google Sheets**
- Evento:
  **“Create Spreadsheet Row”**
- Selecciona tu hoja de cálculo existente o crea una desde Zapier

Configura las columnas con los siguientes valores extraídos del archivo:

| Columna en la hoja | Campo a insertar desde Zapier    |
| ------------------ | -------------------------------- |
| Nome do arquivo    | `File Name`                      |
| Data de subida     | `Modified Time` o `Created Time` |
| URL                | `Web View Link`                  |

> Zapier permite mapear cada campo a una celda específica de forma visual e intuitiva.

### 5. Testea y activa o Zap

- Sube un archivo de prueba a tu carpeta de Google Drive
- Comprueba que se añade correctamente a Google Sheets
- Activa el Zap

## 🔍 Diferencias clave respecto a IFTTT

| Característica                  | Zapier                                      | IFTTT                                           |
| ------------------------------- | ------------------------------------------- | ----------------------------------------------- |
| Nivel de personalización        | Alto (puede encadenar pasos, usar filtros…) | Básico (1 acción por Applet en la versión free) |
| Filtros y condiciones lógicas   | ✔️ (muy útil para docentes)                 | ❌ Solo en versión Pro (Webhooks)                |
| Interfaz                        | Más orientada a procesos empresariais       | Más visual e informal                           |
| N.º de pasos por automatización | Múltiples (con plan gratuito limitado a 2)  | 1 Trigger + 1 Action                            |
| Curva de aprendizaxe            | Lixeiramente maior                          | Máis rápida (ideal para comezos)                |

## Variante didáctica

**Propuesta para alumnado o docentes:**

- Crear un registro automatizado de entregas de prácticas ou actividades
- Filtrar entregas por tipo de fichero, o nombre.