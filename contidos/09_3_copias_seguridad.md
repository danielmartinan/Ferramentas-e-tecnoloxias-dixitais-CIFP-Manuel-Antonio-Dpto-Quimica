# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## ¿Qué es una copia de seguridad y por qué es necesaria?

Una **copia de seguridad** (o *backup*) es una **réplica de los datos originales** que se guarda con el propósito de **recuperarlos** en caso de pérdida, corrupción, robo o ataque. No se trata simplemente de guardar un archivo: consiste en disponer de una estrategia para asegurar la **disponibilidad, integridad y confidencialidad** de la información crítica, especialmente cuando esta información es sensible (como datos personales, resultados de proyectos, documentación técnica o registros administrativos).

En entornos industriales o educativos digitalizados, la pérdida de datos puede suponer:

- Paradas de producción.
- Pérdida de trazabilidad.
- Vulneración de derechos de protección de datos.
- Pérdida de evaluaciones y documentación del alumnado.
- Dificultades legales o administrativas.

### Ejemplos típicos de pérdida de datos

- Un equipo docente borra accidentalmente la carpeta con los informes de prácticas del trimestre.
- Un laboratorio industrial sufre un ataque de ransomware y todos los registros digitales quedan cifrados.
- Un portátil con documentación crítica es robado durante una salida técnica.

En todos estos casos, disponer de una **copia actualizada y accesible** de los datos puede marcar la diferencia entre una recuperación rápida y una pérdida irreversible.

## Tipos de copia de seguridad

Existen diferentes tipos de copias de seguridad según el volumen de datos que se respalden, la frecuencia con la que se realicen y la forma en que se almacenen. Conocer estos tipos permite elegir la estrategia más adecuada según las necesidades del entorno educativo o productivo.

### Copia completa (*full backup*)

- Se respalda **todo el conjunto de datos seleccionado**, sin importar si ha cambiado o no.
- Es el método más **fiable** pero también el más **lento** y que más **espacio** consume.
- Ideal para puntos de control semanales o mensuales, o para archivos críticos.

**Ejemplo:** una vez por semana se copia todo el directorio con las evidencias de aprendizaje del alumnado a un disco duro externo.

### Copia incremental

- Solo copia los **archivos modificados o nuevos** desde la **última copia (completa o incremental)**.
- Es **más rápida y eficiente** en uso de espacio, pero necesita reconstruir los datos a partir de varias copias si se quiere restaurar todo.
- Es la más usada en **sistemas automatizados** o backups frecuentes.

**Ejemplo:** cada noche se guardan únicamente los documentos modificados ese día, para no repetir copias completas innecesarias.

### Copia diferencial

- Copia los archivos modificados desde la **última copia completa**.
- Es un punto intermedio entre la copia completa y la incremental: **más rápida que la completa**, pero **más lenta que la incremental**.
- A la hora de restaurar, solo se necesitan la copia completa y la última diferencial.

**Ejemplo:** si la copia completa fue el lunes, la diferencial del miércoles incluye todos los cambios desde el lunes, no solo los del martes.

### Copia espejo (*mirror*)

- Mantiene una **réplica exacta** del sistema en tiempo real.
- Es útil para **disponibilidad inmediata**, pero también **replica los errores**: si se borra un archivo original, se borra en el espejo.
- No se recomienda como única forma de respaldo.

**Ejemplo:** un disco NAS en red que clona constantemente el contenido de la carpeta de materiales del módulo.

### Comparativa rápida

| Tipo de copia | Velocidad de respaldo | Espacio requerido | Tiempo de restauración | Complejidad |
| ------------- | --------------------- | ----------------- | ---------------------- | ----------- |
| Completa      | Lenta                 | Alto              | Rápido                 | Baja        |
| Incremental   | Rápida                | Bajo              | Lento (si hay muchas)  | Alta        |
| Diferencial   | Media                 | Medio             | Media                  | Media       |
| Espejo        | Muy rápida            | Alto              | Inmediata              | Media       |

## ¿Dónde guardar las copias? Almacenamiento local vs nube

Una de las decisiones más importantes al diseñar una estrategia de copias de seguridad es **dónde almacenar los datos respaldados**. En términos generales, existen dos grandes tipos de almacenamiento:

### Almacenamiento local

Implica guardar las copias de seguridad **en dispositivos físicos** situados cerca del equipo original o dentro de la misma red local.

#### Ejemplos

- Discos duros externos (USB 3.0, SSD).
- Servidores NAS (almacenamiento conectado en red).
- Pendrives (para copias muy pequeñas o rápidas).
- Sistemas RAID locales.

#### Ventajas

- Acceso rápido y sin necesidad de conexión a internet.
- Control directo sobre los datos y su ubicación física.
- Coste bajo una vez adquirido el hardware.

#### Inconvenientes

- Vulnerables a incendios, robos, accidentes físicos o malware local.
- Inversión inicial alta en hardware.
- Requiere disciplina para su mantenimiento y revisión.
- Riesgo de fallo de hardware si no se usan sistemas redundantes.

#### Aplicación educativa

En un taller de FP, es común hacer una copia semanal de todos los informes de prácticas en un disco duro externo que se guarda en una caja de seguridad.

### Almacenamiento en la nube (*cloud backup*)

Consiste en subir las copias a **servidores remotos** gestionados por proveedores externos a través de internet.

#### Ejemplos

- **Google Drive**, **Microsoft OneDrive**, **Dropbox** (uso personal y educativo).
- **iCloud**, **pCloud**, **Mega** (con capacidades cifradas).
- Soluciones empresariales: **Amazon S3**, **Azure Backup**, **Backblaze**, **Wasabi**.

#### Ventajas

- Accesibilidad desde cualquier lugar con conexión.
- Escalabilidad: puedes aumentar capacidad fácilmente.
- Seguridad avanzada (cifrado, control de accesos, redundancia geográfica).
- Automatización y restauración rápida desde múltiples dispositivos.

#### Inconvenientes

- Dependencia de la conexión a internet.
- Coste mensual o anual según volumen de datos.
- Riesgo de mal uso si no se configuran bien los permisos o contraseñas.

#### Aplicación educativa

Una docente de FP puede automatizar la sincronización de todas las rúbricas y evidencias de aprendizaje en una carpeta de OneDrive, asegurando que incluso si pierde su equipo, podrá restaurar el contenido fácilmente.

### 🔁 Comparativa general

| Característica                | Almacenamiento local   | Almacenamiento en la nube     |
| ----------------------------- | ---------------------- | ----------------------------- |
| Accesibilidad remota          | ❌ No                   | ✅ Sí                          |
| Coste inicial                 | ✅ Bajo (tras compra)   | ❌ Suscripción o coste por uso |
| Protección frente a incendios | ❌ Limitada             | ✅ Redundancia geográfica      |
| Velocidad de recuperación     | ✅ Alta                 | ⚠️ Depende de conexión        |
| Cifrado y seguridad avanzada  | ⚠️ Depende del usuario | ✅ Suele estar incluido        |

## 4. Frecuencia y automatización

Uno de los errores más comunes en la gestión de backups es realizarlos **de forma esporádica o manual**, lo que incrementa el riesgo de que, cuando ocurre un fallo, la copia esté obsoleta o no exista.

### ¿Cada cuánto tiempo hacer una copia?

Depende de:

- La **frecuencia de cambio** de los datos.
- La **importancia o sensibilidad** de la información.
- Los **recursos disponibles**.

#### Recomendaciones orientativas

- **Documentos de trabajo diario**: copia diaria o continua (sincronización automática).
- **Archivos de proyecto o trimestrales**: copia semanal o mensual.
- **Datos críticos (contraseñas, bases de datos, evaluaciones)**: copia automática diaria, con versión histórica.

### Regla 3-2-1 de copias de seguridad

Una regla práctica y ampliamente recomendada:

> **3 copias** de los datos,
> en **2 formatos distintos**,
> con **1 copia fuera de la ubicación física**.

Ejemplo aplicado en un entorno educativo:

- Documentos originales en el equipo del profesor.
- Copia local automática en disco duro externo del centro.
- Copia en la nube en cuenta educativa de Google Drive.

### Automatización

Las herramientas modernas permiten **programar copias automáticas** con sincronización, alertas de error y versiones históricas.

#### Herramientas comunes para automatizar

- **Windows**: Historial de archivos, Copias de seguridad de Windows.
- **macOS**: Time Machine.
- **Linux**: rsync, Deja Dup.
- **Nube educativa**: Google Backup & Sync, OneDrive Sync Client.
- **Herramientas externas**: AOMEI Backupper, Cobian Backup, Duplicati (open source), Veeam (uso profesional).

#### Aplicación en el aula

Se puede enseñar al alumnado a configurar una copia semanal automática de sus proyectos en una carpeta de Dropbox sincronizada, lo que refuerza tanto la responsabilidad digital como la organización de su trabajo.

## Casos prácticos o simulaciones

La enseñanza del concepto de copia de seguridad resulta más eficaz cuando se **vincula a situaciones reales** o simuladas que permiten comprender el impacto de su ausencia o su buen uso. A continuación se presentan algunos casos prácticos adaptables al aula o entorno de prácticas.

### 🧪 Caso práctico 1: pérdida de una carpeta de prácticas

**Situación:**
Durante la evaluación trimestral, un docente de FP borra accidentalmente la carpeta donde se almacenaban los informes y evidencias del alumnado de los últimos dos meses.

**Resultado 1 (sin copia):**
Los datos no se pueden recuperar. Se deben repetir actividades, se pierden evidencias de aprendizaje y se genera malestar entre alumnado, familias y coordinación.

**Resultado 2 (con copia automática en la nube):**
El docente accede a la versión anterior guardada en Google Drive o OneDrive, y restaura la carpeta completa con solo unos clics.

**Objetivo didáctico:**
Concienciar de la importancia de automatizar copias y elegir bien su ubicación.

### 🧪 Caso práctico 2: ataque de ransomware en aula técnica

**Situación:**
En un aula con ordenadores compartidos, se abre por error un fichero adjunto malicioso. El ransomware cifra todos los datos de usuario y exige un rescate para liberarlos.

**Resultado 1 (sin backup):**
Todos los trabajos y documentos del trimestre se pierden. No hay posibilidad de restaurarlos.

**Resultado 2 (con backup externo + nube):**
Los equipos se formatean y los datos se restauran desde una copia completa hecha semanalmente en disco NAS y otra en nube cifrada.

**Objetivo didáctico:**
Relacionar la seguridad de los datos con los contenidos de ciberseguridad y respuesta ante incidentes.

### 🧪 Caso práctico 3: simulación de recuperación

**Situación:**
Se propone a los alumnos una simulación de “fallo total” en sus equipos. Deben:

- Comprobar si tienen copia.
- Restaurar los archivos importantes.
- Redactar un informe de lecciones aprendidas.

**Objetivo didáctico:**
Poner en práctica lo aprendido sobre frecuencia de copia, herramientas y criterios de restauración.

## Actividades didácticas en el aula de FP

A continuación, se proponen actividades que pueden integrarse en el desarrollo del módulo o en unidades relacionadas con seguridad, entornos IT/OT, datos o gestión digital.

### Actividad 1: diseña tu estrategia de backup

**Objetivo:** Que el alumnado diseñe una política de copia de seguridad para un caso real o simulado.

**Desarrollo:**

1. Presentar un escenario (por ejemplo: “Eres responsable digital de una empresa química con documentos técnicos, informes de calidad, y datos de personal”).
2. El alumnado debe decidir:
   - Qué datos se copian.
   - Con qué frecuencia.
   - Con qué herramientas.
   - Dónde se guardan.
   - Qué riesgos se cubren.

**Evaluación:** Se valorará la viabilidad, seguridad y cumplimiento normativo del plan.

### 🎯 Actividad 2: simulacro de restauración

**Objetivo:** Familiarizar al alumnado con la recuperación de datos tras una pérdida.

**Desarrollo:**

- El docente elimina deliberadamente una carpeta o archivo de prueba.
- El alumnado debe recuperarlo usando:
    - Versiones anteriores (historial).
    - Papelera.
    - Copia sincronizada en nube.
    - Disco externo si procede.

**Variantes:**

- Realizarlo en grupo.
- Cambiar el sistema operativo o herramienta.

### Actividad 3: revisión crítica de políticas de copia en servicios cloud

**Objetivo:** Analizar qué garantías ofrece cada plataforma en cuanto a copias de seguridad, versión histórica y recuperación.

**Desarrollo:**

1. Se dividen los estudiantes en grupos.
2. Cada grupo investiga un servicio (Google Drive, Dropbox, OneDrive...).
3. Deben responder a:

   - ¿Qué pasa si borras un archivo?
   - ¿Cuánto tiempo puedes restaurarlo?
   - ¿Cuántas versiones guarda?
   - ¿Qué pasa si cierras la cuenta?

**Evaluación:** Comparación argumentada de los servicios, presentación al grupo y conclusiones.

### Actividad 4: "Mi diario de backup"

**Objetivo:** Desarrollar hábitos digitales responsables.

**Desarrollo:**
Durante una semana, el alumnado:

- Registra qué datos genera.
- Identifica cuáles serían irrecuperables si su equipo fallara.
- Describe qué copias realiza (o no) y cómo podría mejorarlo.

**Evaluación:** Informe final con autorreflexión.

## Conclusión de la sección

La gestión correcta de copias de seguridad es **una competencia básica en la era digital**. No solo protege los datos, sino que:

- Garantiza la continuidad educativa y profesional.
- Cumple con la normativa legal vigente.
- Enseña responsabilidad y planificación tecnológica.