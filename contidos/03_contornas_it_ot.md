# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## Contornas IT e OT: integración e retos na dixitalización industrial

### Introdución: dous mundos, unha fronteira cada vez máis difusa

A dixitalización dos sectores produtivos implica a **converxencia de dúas contornas tradicionalmente separadas**:

* A contorna **IT (Information Technology)** ou tecnoloxías da información.
* A contorna **OT (Operational Technology)** ou tecnoloxías operativas.

Historicamente, estas áreas funcionaban de forma independente: IT centrada en sistemas de xestión e datos empresariais, e OT centrada no control de procesos industriais. Con Industria 4.0, ambas empezan a **integrarse**, xurdindo novos desafíos e oportunidades.

### Que é IT?

A contorna IT abrangue todas as tecnoloxías destinadas á **xestión da información**, como os sistemas de planificación empresarial, bases de datos, redes, servidores ou aplicacións corporativas.

#### Profesións no ámbito IT

* Administradores de sistemas e redes.
* Desenvolvedores de software.
* Analistas de datos.
* Especialistas en ciberseguridade.
* Xestores de proxectos IT.
* Administradores de bases de datos.
* Enxeñeiros de software.

#### Exemplos de solucións IT nunha empresa

* ERP (Enterprise Resource Planning) → SAP, Odoo, etc.
* CRM (Customer Relationship Management)
* Xestión documental
* Infraestrutura de redes e servidores
* Ciberseguridade, backups, xestión de usuarios

No ámbito educativo ou administrativo:
As aplicacións da Xunta de Galicia para xestión académica (XADE), correo institucional, ou plataformas como Moodle, tamén forman parte da contorna IT.

### Que é OT?

OT refírese ao conxunto de tecnoloxías que se usan para **medir, controlar e automatizar procesos físicos** nun entorno industrial, produtivo ou de infraestrutura.

#### Exemplos de solucións OT

* SCADA (Supervisory Control and Data Acquisition)
* PLCs (Programmable Logic Controllers)
* DCS (Distributed Control Systems)
* Instrumentación industrial (sensores, actuadores, válvulas)
* Sistemas MES (Manufacturing Execution Systems)

#### Profesions no ámbito OT

* Técnicos de mantemento de sistemas de control.
* Enxeñeiros de automatización ou electrónicos
* Especialistas en instrumentación.
* Técnicos de seguridade industrial.
* Progrmadores de PLCs ou robótica industrial.
* Operarios de fábrica con coñecementos en control de procesos.

No sector químico:
Un PLC que regula a temperatura dun reactor, un sensor de pH conectado a un SCADA ou un sistema de seguridade que detecta fugas forman parte da contorna OT.

### Principais diferenzas entre IT e OT

| Característica             | IT                                        | OT                                        |
| -------------------------- | ----------------------------------------- | ----------------------------------------- |
| Obxectivo principal        | Xestión da información empresarial        | Control e supervisión de procesos físicos |
| Entorno operativo          | Oficinas, centros de datos                | Fábricas, plantas, laboratorios           |
| Tecnoloxía                 | Servidores, PCs, redes, software          | PLCs, SCADA, sensores, actuadores         |
| Tempo de resposta          | Segundos/minutos                          | Milisegundos/tempo real                   |
| Criterio principal         | Confidencialidade e integridade dos datos | Disponibilidade e seguridade operativa    |
| Actualizacións             | Periódicas (frecuentes)                   | Escasas, coidadosamente planificadas      |
| Ciclo de vida dos sistemas | Curto (3-5 anos)                          | Longo (10-20 anos ou máis)                |

### A converxencia IT/OT: por que agora?

A dixitalización, a IoT industrial (IIoT), a análise de datos e a intelixencia artificial empurran cara á **converxencia IT/OT**. Esta unión permite:

* Obter **datos en tempo real** dos procesos industriais para analizalos.
* Integrar sistemas de control coa xestión empresarial.
* Aplicar **IA ou Big Data** ao mantemento preditivo ou á calidade do produto.
* Mellorar a eficiencia, a trazabilidade e a toma de decisións.

🎯 **Obxectivo clave:**
Crear unha cadea de valor dixital integrada, onde os datos flúan desde a máquina ata o ERP e viceversa.

#### Beneficios da converxencia IT/OT e desafíos

### Exemplos prácticos no sector químico

#### Exemplo 1: Integración SCADA – ERP

Nunha planta de produción de produtos químicos, o sistema SCADA recolle datos de temperatura e presión durante a produción. Estes datos envíanse automaticamente ao ERP para:

* Xerar informes de trazabilidade.
* Actualizar lotes e rexistros de calidade.
* Controlar inventarios de materias primas.

#### Exemplo 2: Mantemento preditivo con análise de datos

Unha bomba industrial equipada con sensores (temperatura, vibración, fluxo) envía datos ao sistema OT. Estes datos son analizados por un sistema IT na nube que:

* Detecta patróns anómalos.
* Predí un fallo inminente.
* Programa automaticamente unha intervención antes de que o equipo falle.

### Desafíos da integración IT/OT

A converxencia destes mundos presenta varios retos:

* **Ciberseguridade**: OT non estaba deseñado para estar conectado a internet → risco de ataques.
* **Incompatibilidades técnicas**: protocolos, sistemas e arquitecturas distintas.
* **Cambio cultural**: profesionais de IT e OT teñen formación, prioridades e linguaxes distintas.
* **Actualizacións delicadas**: os sistemas OT non poden deterse facilmente para aplicar parches ou cambios.

### Enfoques de integración: estratexias posibles

Hai diferentes estratexias para integrar IT e OT:

1. **Captura de datos desde OT cara IT** → mediante gateways, APIs, OPC-UA...
2. **Plataformas IIoT** → que unifican datos industriais nun entorno común (ex. Siemens MindSphere, Azure IoT, etc.)
3. **Edge computing** → procesamento na fronteira entre IT e OT, sen enviar todos os datos á nube.
4. **Data Lakes** → repositorios unificados de datos estruturados e non estruturados.

### Implicacións para a FP

Na docencia de módulos coma *Dixitalización aplicada aos sectores produtivos*, é fundamental:

* Explicar claramente estas contornas e a súa integración.
* Traballar con ferramentas de simulación de sistemas OT (ex. Factory I/O, Codesys, OpenPLC).
* Utilizar software de xestión de datos ou SCADA para mostrar exemplos reais.
* Potenciar o **traballo interdisciplinar**: programación, mantemento, seguridade, análise de datos...

### Conclusións clave

* A distinción IT/OT é esencial para comprender a estrutura tecnolóxica dunha empresa moderna.
* A dixitalización require superar a separación entre ambos mundos.
* A integración IT/OT aporta grandes beneficios, pero tamén require coidado, formación e cultura colaborativa.
* A FP debe preparar profesionais capaces de moverse nestes dous ámbitos, cada vez máis conectados.
