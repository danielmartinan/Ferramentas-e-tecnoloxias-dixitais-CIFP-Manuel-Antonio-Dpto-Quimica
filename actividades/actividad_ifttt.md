# Actividad IFTTT: Automatización con Google Drive y Google Sheets

## Escenario: Registrar automáticamente en Google Sheets cada archivo añadido a Google Drive

### ¿Qué necesitas?

- Cuenta en [IFTTT](https://ifttt.com/)
- Cuenta en Google
- Carpeta en Google Drive donde se añadirán archivos
- Acceso a Google Sheets

## Paso a paso en IFTTT

### 1. Accede a IFTTT y crea un nuevo Applet

- Ve a [https://ifttt.com/create](https://ifttt.com/create)
- Haz clic en **“If This”**

### 2. Configura el disparador (Trigger)

- Busca y selecciona **Google Drive**
- Elige la opción:
  **“New file in your folder”**
- Autoriza tu cuenta de Google si es necesario
- Selecciona o pega la ruta de la **carpeta específica** que quieres vigilar
  *(por ejemplo: `/Proxectos_Dixitalizacion/Practicas_Alumnado`)*

### 3. Configura la acción (Then That)

- Haz clic en **“Then That”**
- Busca y selecciona **Google Sheets**
- Elige:
  **“Add row to spreadsheet”**

### Configura los detalles

- **Spreadsheet name:** Puedes llamarla por ejemplo: `Rexistro_arquivos`

- **Formatted row:** Aquí defines qué datos se van a registrar. Ejemplo:

    ```
    {{FileName}}, {{CreatedAt}}, {{Url}}
    ```

    Esto añadirá una fila por archivo con:

    - Nombre del archivo
    - Fecha y hora de subida
    - URL del archivo en Drive

- **Drive folder path:** (opcional) Deja el valor por defecto o personalízalo (creará la hoja si no existe)

### 4. Guarda el Applet y prueba

- Guarda el Applet y actívalo
- Sube un archivo a la carpeta de Drive indicada
- Ve a tu Google Drive y abre la hoja de cálculo `Rexistro_arquivos`
- Deberías ver una nueva fila añadida automáticamente

## ¿Por qué es útil esta automatización?

- Permite a docentes **llevar control automático** de entregas, materiales o evidencias prácticas sin esfuerzo manual
- Se puede combinar con filtros o revisión posterior (ej. comprobar quién entrega a tiempo)
- Admite análisis posterior (por ejemplo, frecuencia de entregas, tipos de archivos, etc.)

## Variante didáctica

**Actividad para el aula:**
Plantear al alumnado que prepare una carpeta compartida para subir prácticas, y que la hoja de cálculo registre automáticamente sus entregas. Luego, trabajar con la hoja de cálculo para:

- Contar entregas por alumno
- Ordenar por fechas
- Detectar entregas fuera de plazo (con fórmulas)
