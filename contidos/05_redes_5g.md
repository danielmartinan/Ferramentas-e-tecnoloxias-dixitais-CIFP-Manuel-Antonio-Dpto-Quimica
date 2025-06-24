# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## 5 Que é o 5G? Definición e principios básicos

A tecnoloxía **5G** (quinta xeración de redes móbiles) representa un salto cualitativo e cuantitativo fronte ás xeracións anteriores. Non se trata só de ofrecer conexións máis rápidas, senón de permitir unha transformación completa da maneira na que os dispositivos e sistemas se comunican entre si. O 5G constitúe unha **infraestrutura crítica** para o desenvolvemento da Industria 4.0, xa que posibilita a conexión masiva de dispositivos, a transmisión de datos case en tempo real e o despregamento de aplicacións avanzadas baseadas na intelixencia artificial, na robótica e na realidade aumentada.

### Evolución das redes móbiles: do 1G ao 5G

Ao longo das últimas décadas, as redes móbiles evolucionaron para dar resposta ás necesidades cambiantes da sociedade e da industria:

| Xeración | Época      | Características principais                  | Exemplos de uso                                                 |
| -------- | ---------- | ------------------------------------------- | --------------------------------------------------------------- |
| **1G**   | Anos 80    | Comunicación analóxica, voz só              | Teléfonos móbiles básicos                                       |
| **2G**   | Anos 90    | Dixitalización da voz, SMS                  | SMS, chamadas dixitais                                          |
| **3G**   | Anos 2000  | Internet móbil, datos                       | Navegación web, correo electrónico                              |
| **4G**   | Anos 2010  | Internet de alta velocidade, vídeo          | Streaming, videollamadas, apps avanzadas                        |
| **5G**   | Desde 2020 | Alta velocidade, baixa latencia, IoT masivo | Realidade aumentada, vehículos autónomos, fábricas intelixentes |

🔍 **Exemplo ilustrativo**:
Co 4G, unha videollamada grupal pode ter certo retardo ou interrupcións en zonas con mala cobertura. Co 5G, ese tipo de comunicacións poden realizarse con **calidade 4K e sen latencia perceptible**, o que resulta crucial, por exemplo, para o control remoto de maquinaria ou para a formación técnica en realidade virtual.

### Características técnicas do 5G

A principal novidade do 5G reside na súa capacidade para ofrecer un **conxunto de prestacións moi superiores ás das redes anteriores**, especialmente en tres dimensións clave:

1. **Velocidade de transmisión de datos**
   O 5G pode alcanzar velocidades de ata **10 Gbps**, o que supón multiplos da velocidade do 4G. Isto permite descargar e enviar grandes volumes de datos en segundos.

2. **Latencia ultra baixa**
   A latencia é o tempo que tarda un paquete de datos en ir desde o dispositivo ata o servidor e volver. Co 5G, esta latencia pode ser inferior a **1 milisegundo**, facendo posibles aplicacións en tempo real como a telecirurxía ou o control de drons industriais.

3. **Alta densidade de conexións**
   O 5G soporta ata **1 millón de dispositivos por quilómetro cadrado**, sendo ideal para contornas industriais con sensores, robots, sistemas de control e equipos portátiles conectados simultaneamente.

4. **Confiabilidade e eficiencia enerxética**
   Esta tecnoloxía mellora a eficiencia do uso da enerxía, prolongando a duración da batería de dispositivos IoT e garantindo unha conexión estable incluso en condicións adversas.

### O 5G como facilitador da dixitalización

O 5G actúa como **infraestrutura habilitadora doutras tecnoloxías dixitais**, como:

- **Internet das cousas (IoT)**: conexión masiva e simultánea de sensores, dispositivos e maquinaria.
- **Intelixencia artificial**: transmisión de datos a gran velocidade para análise en tempo real.
- **Cloud e edge computing**: facilita o acceso e procesamento descentralizado da información.
- **Realidade aumentada/virtual**: experiencia inmersiva sen cortes nin retardos.
- **Robótica colaborativa**: coordinación precisa de máquinas conectadas en tempo real.

**Aplicación no sector químico**:
Nunha planta química con cobertura 5G, poderían instalarse centos de sensores que rexistran variables como temperatura, presión ou caudal. Estes datos envíanse en tempo real a unha plataforma na nube que analiza posibles riscos ou anomalías. Ademais, técnicos especializados poderían supervisar ou intervir remotamente desde outro centro de control.

## 5.2. Arquitectura da rede 5G

A arquitectura da rede 5G está deseñada para ser máis flexible, escalable e eficiente que a das xeracións anteriores. Isto conséguese mediante unha combinación de novas tecnoloxías e un deseño baseado en software, que permite adaptar a rede a diferentes necesidades e escenarios, desde unha cidade intelixente ata unha fábrica automatizada.

### Elementos fundamentais da arquitectura 5G

A estrutura dunha rede 5G pode dividirse en tres grandes compoñentes:

#### 1. **Acceso por radio (RAN - Radio Access Network)**

É a parte da rede que conecta directamente os dispositivos (móbiles, sensores, vehículos, robots…) coa infraestrutura central. Inclúe as **estacións base 5G**, tamén chamadas **gNBs**.

- Soporta diferentes bandas de frecuencia: desde bandas baixas (<1 GHz) para cobertura ampla, ata bandas milimétricas (>24 GHz) para alta velocidade en distancias curtas.
- Permite a **conexión simultánea de miles de dispositivos** cunha latencia moi baixa.
- Utiliza técnicas avanzadas como **MIMO masivo** (Multiple Input, Multiple Output) para mellorar o rendemento.

#### 2. **Rede de transporte (backhaul e fronthaul)**

É a parte que leva os datos desde as estacións base ata o núcleo da rede e viceversa.

- Pode utilizar **fibra óptica, enlaces microondas ou mesmo 5G fixo**.
- É clave para garantir a velocidade e a latencia da conexión.

#### 3. **Núcleo da rede (5G Core ou 5GC)**

É a parte central que xestiona todo o tráfico de datos, a identidade dos usuarios, a seguridade e os servizos. É moi diferente ao núcleo 4G, xa que está **baseado en software e virtualización**.

As súas principais funcións son:

- **Control de sesións e mobilidade** dos usuarios.
- **Segmentación da rede** (*network slicing*).
- **Seguridade, autenticación e encriptación**.
- Integración con redes externas (Internet, cloud, redes privadas...).

### Características distintivas da arquitectura 5G

#### Virtualización de funcións de rede (NFV)

As funcións da rede (como o control de acceso ou a xestión do tráfico) xa non dependen de hardware específico, senón que se executan como **software en servidores virtuais**, o que permite:

- Escalar rapidamente.
- Adaptarse a diferentes necesidades.
- Reducir custos de infraestrutura.

#### Network slicing (segmentación de rede)

Permite crear **“anacos” virtuais da rede**, cada un optimizado para un uso concreto, sobre a mesma infraestrutura física.

**Exemplos de slices**:

- Un slice para comunicacións ultra fiables e de baixa latencia (vehículos autónomos).
- Outro para conexión masiva de sensores (IoT).
- Outro para uso de móbiles con gran ancho de banda (streaming, videoxogos...).

#### Edge computing integrado

A arquitectura 5G inclúe capacidades de **procesamento en el borde** (edge), é dicir, preto do lugar onde se xeran os datos, sen necesidade de enviar todo á nube.

Isto permite:

- Respostas máis rápidas.
- Menor tráfico de datos.
- Maior privacidade.

### Comparativa entre redes 4G e 5G

| Elemento             | 4G                                | 5G                                                   |
| -------------------- | --------------------------------- | ---------------------------------------------------- |
| Núcleo da rede       | Físico, limitado                  | Virtualizado, dinámico                               |
| Acceso por radio     | Limitado en velocidade e latencia | Alta capacidade, baixa latencia, MIMO masivo         |
| Segmentación da rede | Non existe                        | Network slicing para diferentes casos de uso         |
| Edge computing       | Non integrado                     | Integrado, con menor latencia                        |
| Soporte para IoT     | Limitado                          | Masivo, con soporte para millóns de dispositivos/km² |

### Aplicación práctica: sector industrial

Nunha fábrica automatizada, a arquitectura 5G permite:

- Que os **robots colaborativos** funcionen sen cables e con sincronización milimétrica.
- Que os datos dos sensores se procesen **no edge**, evitando retardos e reducindo o uso de datos.
- Que se creen redes específicas (slices) para procesos críticos, separados doutras redes.

**Exemplo real:**
Unha empresa automotriz alemá emprega redes 5G privadas para conectar vehículos guiados automaticamente (AGVs) que se coordinan con sensores e cámaras instaladas na planta. Grazas á baixa latencia, poden moverse sen accidentes nin retardos.

## 5.3. Aplicacións do 5G nos sectores produtivos

A tecnoloxía 5G non é só unha mellora técnica, senón unha **ferramenta estratéxica** que permite transformar os sectores produtivos. Grazas ás súas características —velocidade, baixa latencia, capacidade de conexión masiva e soporte para computación no bordo— o 5G facilita a implantación de solucións avanzadas que antes eran inviables.

A continuación explícanse as principais **aplicacións por ámbitos produtivos**, con exemplos adaptados a contextos reais e posibles usos na FP.

### 1. Industria manufactureira

O 5G permite que a industria tradicional evolucione cara a fábricas intelixentes ou *smart factories*, onde os sistemas están interconectados, automatizados e adaptables en tempo real.

**Aplicacións destacadas:**

- Control remoto e en tempo real de maquinaria industrial.
- Robótica colaborativa sen cables (cobots).
- Sistemas de mantemento predictivo con sensores conectados.
- Realidade aumentada para asistencia técnica e formación in situ.

**Exemplo**:
Nunha planta de ensamblaxe de compoñentes electrónicos, os operarios usan lentes de realidade aumentada conectadas vía 5G para recibir instrucións visuais e asistencia remota en tempo real, sen retardos.

### 2. Sector primario (agricultura, gandaría e pesca)

A cobertura e capacidades do 5G permiten levar a dixitalización a zonas rurais e costeiras, tradicionalmente con escasa conectividade.

**Aplicacións posibles:**

- Drones con conexión 5G para supervisión de cultivos ou viñedos.
- Sensores de humidade e temperatura que transmiten datos para rega intelixente.
- Rastrexo en tempo real de gando ou embarcacións.
- Análise de imaxes de cultivos con IA desde o bordo (edge computing).

**Exemplo**:
Un sistema de rega automatizado nunha plantación de tomates controla os sensores de solo vía 5G e axusta o caudal segundo as condicións climáticas en tempo real, aforrando auga e aumentando a produtividade.

### 3. Sector enerxético e medioambiental

O 5G facilita a monitorización en tempo real e a resposta automática ante cambios no entorno, moi útil en redes intelixentes e sistemas de xeración descentralizada.

**Aplicacións destacadas:**

- Supervisión de paneis solares ou turbinas eólicas remotas.
- Redes de sensores para control ambiental en parques naturais ou industrias.
- Resposta automática a cortes de subministración.
- Optimización de sistemas de almacenamento e distribución de enerxía.

🔍 **Exemplo**:
Nun parque eólico mariño, os sensores envían datos de vento, vibración e temperatura vía 5G a unha central na costa, que analiza as condicións en tempo real e programa mantemento preventivo.

### 4. Loxística e cadea de subministración

A baixa latencia e a capacidade de conectar miles de dispositivos simultaneamente fan do 5G unha ferramenta clave para mellorar a trazabilidade e automatizar almacéns e sistemas de transporte.

**Aplicacións posibles:**

- Vehículos autónomos en centros loxísticos.
- Detección de incidencias en tempo real en rutas de distribución.
- Xestión intelixente de inventarios mediante sensores conectados.
- Supervisión en directo de contedores, paquetes e condicións ambientais.

**Exemplo**:
Un sistema de transporte de produtos farmacéuticos usa sensores 5G para controlar a temperatura e humidade nos camións, alertando de inmediato se hai risco de rotura da cadea de frío.

### 5. Saúde e servizos sociais

O 5G tamén impacta positivamente no ámbito sociosanitario, cunha especial importancia en contornas rurais ou con falta de profesionais.

**Aplicacións destacadas:**

- Telemedicina en tempo real con vídeo de alta calidade.
- Monitorización remota de pacientes crónicos mediante dispositivos conectados.
- Vehículos de emerxencia conectados con hospitais.
- Formación en realidade virtual para persoal sanitario.

**Exemplo**:
Un centro de saúde nunha vila remota pode realizar consultas especializadas vía 5G cun hospital de referencia, enviando probas e vídeo de forma instantánea.

### Aplicación transversal: Formación profesional

Na FP, o 5G abre posibilidades para:

- Formación inmersiva con realidade virtual sen cables.
- Uso de simuladores remotos ou robotización conectada.
- Proxectos colaborativos entre centros a través de redes privadas.
- Acceso inmediato a contidos complexos en calquera contorno.

## 5.4. Vantaxes e limitacións do 5G

A tecnoloxía 5G representa un salto cualitativo nas capacidades das redes de comunicación, pero tamén supón retos e limitacións. É fundamental que o profesorado e o alumnado coñezan ambos os aspectos para unha análise crítica e realista da súa implantación nos sectores produtivos.

### Vantaxes do 5G

#### 1. Maior velocidade de transmisión

O 5G permite velocidades de ata **10 Gbps**, o que supón entre 10 e 100 veces máis que o 4G.

🔍 *Aplicación práctica:*
Permite transmitir vídeos en tempo real en resolución 4K ou mesmo 8K, útil para formación inmersiva ou inspección remota de procesos industriais.

#### 2. Latencia ultra baixa

A latencia redúcese a valores próximos a **1 milisegundo**, esencial para aplicacións en tempo real.

🔍 *Aplicación práctica:*
Robótica colaborativa ou control de vehículos autónomos, onde calquera retardo pode ter consecuencias críticas.

#### 3. Alta densidade de conexións

Capacidade para conectar **ata 1 millón de dispositivos por km²**, imprescindible para contornas con moitos sensores ou dispositivos IoT.

🔍 *Aplicación práctica:*
Nun invernadoiro intelixente, poden instalarse centos de sensores (temperatura, humidade, pH, CO₂...) conectados simultaneamente.

#### 4. Melloras en seguridade e fiabilidade

A arquitectura 5G inclúe medidas nativas de **encriptación, autenticación e illamento de datos**, así como **network slicing** que permite separar tráfico segundo o uso ou criticidade.

#### 5. 🧠 Integración co edge computing

O 5G permite que os datos se procesen preto da súa orixe, reducindo carga na rede e acelerando as respostas.

🔍 *Aplicación práctica:*
Procesamento local de imaxes captadas por drons en tempo real para recoñecemento de pragas en cultivos.

### Limitacións e desafíos do 5G

#### 1. Infraestrutura e cobertura limitada

As bandas de frecuencia máis rápidas (ondas milimétricas) teñen **alcance curto e menor penetración**, o que require instalar moitas antenas.

📉 *Implicación:*
Difícil implantación en zonas rurais ou dispersas sen fortes investimentos.

#### 2. Custos de implantación elevados

A renovación da infraestrutura (estacións base, núcleo de rede, dispositivos compatibles...) supón un investimento inicial moi alto, sobre todo en empresas pequenas.

#### 3. Consumo enerxético

A pesar de melloras na eficiencia por bit transmitido, o consumo total pode aumentar debido ao gran número de dispositivos conectados e a esixencia dos servizos.

#### 4. Complexidade tecnolóxica

Requírense **coñecementos avanzados en redes, seguridade e virtualización**, o que pode ser unha barreira para pequenas empresas ou centros sen persoal técnico especializado.

#### 5. Preocupacións sobre seguridade e privacidade

A conectividade masiva e o uso de datos en tempo real aumentan os riscos de:

- Ciberataques a infraestruturas críticas.
- Exfiltración de datos persoais ou industriais.
- Dependencia de provedores tecnolóxicos.

### Resumo: táboa comparativa

| Aspecto                     | Vantaxes                                     | Limitacións                                         |
| --------------------------- | -------------------------------------------- | --------------------------------------------------- |
| Velocidade                  | Ata 10 Gbps                                  | Necesita dispositivos e antenas compatibles         |
| Latencia                    | Inferior a 1 ms                              | Non se garante en redes saturadas ou con pouco edge |
| Conectividade masiva        | 1 millón de dispositivos/km²                 | Pode saturar sen unha xestión eficaz                |
| Fiabilidade e seguridade    | Mellorada grazas a estándares e segmentación | Novos riscos, máis superficie de ataque             |
| Custo e infraestrutura      | Escalable e flexible a longo prazo           | Elevado custo inicial de implantación               |
| Compatibilidade tecnolóxica | Integra cloud, IoT, edge, IA, etc.           | Require coñecementos técnicos avanzados             |

### Reflexión para a aula

> **¿Todos os sectores poden beneficiarse por igual do 5G?**
>
> O docente pode propoñer un debate ou traballo en grupo para analizar:
>
> - En que sectores da contorna ten sentido investir en 5G?
> - Que limitacións deben superar primeiro?
> - Que perfís profesionais se van demandar?

Por suposto. Aquí tes unha pequena reflexión para inserir como epígrafe ou caixa destacada no módulo, tratando con rigor e sentido crítico o tema do **5G e a saúde**, así como a proliferación de **desinformación** asociada.

### 🧠 5G e saúde: entre o rigor científico e os bulos

Desde a súa aparición, as redes 5G foron obxecto de **preocupacións sociais** relacionadas coa saúde humana, especialmente en relación co uso de **frecuencias máis altas** (como as ondas milimétricas) e a densidade de antenas necesarias para a súa implantación.

#### Que di a ciencia?

Os organismos internacionais especializados (como a **Organización Mundial da Saúde**, a **Unión Internacional de Telecomunicacións** ou a **Comisión Internacional de Protección contra a Radiación Non Ionizante**) coinciden en que:

- As emisións do 5G están **moi por debaixo dos límites considerados perigosos** para a saúde.
- Non existe evidencia científica sólida que relacione o 5G con efectos adversos como o cancro, infertilidade, fatiga crónica ou outros síntomas frecuentemente asociados a teorías sen base científica.
- As radiacións usadas son **non ionizantes**, polo que non alteran o ADN nin producen efectos similares aos da radiación ultravioleta, raios X ou gamma.

#### Entón... de onde veñen os bulos?

A chegada do 5G coincidiu no tempo coa pandemia de COVID-19, o que favoreceu a aparición de **teorías conspirativas** a través de redes sociais, como:

- Que o 5G debilitaba o sistema inmunitario.
- Que as antenas propagaban o virus.
- Que se usaba para controlar á poboación.

**Realidade:** Non existe relación causal entre o 5G e a COVID-19. Son dúas cousas completamente independentes. De feito, moitos dos países con máis antenas 5G tiveron menos casos por millón de habitantes.

#### Por que é importante tratar este tema na FP?

Nun módulo como este, orientado á dixitalización produtiva, é fundamental:

- **Fomentar o pensamento crítico** e a análise baseada en fontes fiables.
- Preparar ao alumnado para **responder con argumentos técnicos e científicos** ante posibles reticencias en contornas laborais ou sociais.
- Entender que a **aceptación tecnolóxica require confianza pública**, polo que a transparencia e a comunicación clara son claves.

📘 **Proposta didáctica:**
Organizar unha pequena dinámica na aula:

1. Dividir o alumnado en grupos e repartir noticias (reais ou inventadas) sobre 5G e saúde.
2. Pedir que identifiquen se se trata de información ou desinformación, e que xustifiquen por que.
3. Comparar conclusións e extraer boas prácticas para avaliar a fiabilidade dunha fonte.

## 5.5. Ferramentas, dispositivos e recursos educativos sobre 5G

A pesar de que o 5G é unha tecnoloxía de infraestrutura avanzada, existen ferramentas e recursos didácticos que permiten **traballar conceptos clave na aula**, comprender o seu funcionamento e analizar o seu impacto real nos sectores produtivos. A continuación preséntanse diferentes categorías de recursos, acompañadas de exemplos e propostas de uso.

### 1. Plataformas e simuladores educativos

Estas ferramentas permiten visualizar como funciona unha rede 5G, as diferenzas coas redes anteriores ou simular casos de uso en contornos industriais.

- **NetSim 5G** (Boson o GNS3 + Módulos): simulador de redes que permite montar unha infraestrutura virtual onde se poden comparar arquitecturas 4G vs 5G.
- **5G Playground** (Fraunhofer FOKUS): plataforma online que permite experimentar con redes 5G mediante acceso remoto a unha infraestrutura real.
- **Cisco Packet Tracer (con módulos de IoT)**: aínda que non traballa directamente con 5G, permite visualizar comunicacións entre dispositivos e conceptos relacionados con Edge Computing e transmisión de datos.

🧪 **Aplicación didáctica**: Analizar un escenario de fábrica intelixente, identificar onde se require latencia ultrabaixa e como o 5G o permite fronte ao WiFi ou 4G.

### 2. Dispositivos e kits de aprendizaxe

O acceso a tecnoloxía 5G real require dispoñer de terminais e conexión, pero tamén se poden utilizar:

- **Routers 5G portátiles (MiFi)**: permiten crear redes locais baseadas en 5G para experimentar con velocidades e latencia.
- **Dispositivos IoT con conectividade 5G (demo kits)**: algúns fabricantes como **Quectel**, **Sierra Wireless** ou **Arduino MKR NB** ofrecen kits compatibles con redes de nova xeración.
- **Módems USB 5G**: permiten conectar un portátil a unha rede 5G e realizar medicións de velocidade ou latencia.

🔍 **Exemplo práctico**: Medir e comparar a velocidade de carga/descarga en 4G vs 5G nun mesmo punto xeográfico.

### 3. Aplicacións sectoriais reais

É posible analizar aplicacións xa existentes en sectores produtivos similares aos que se estudan na FP:

- **Sector químico**: control remoto de sensores en entornos perigosos mediante 5G (evita cablaxe e reduce tempo de resposta).
- **Sector sanitario**: cirurxía remota ou control de dispositivos biomédicos conectados.
- **Sector agroalimentario**: uso de drons con conectividade 5G para inspección e recolecta de datos.

🎯 **Actividade proposta**: Pedir ao alumnado que deseñe unha aplicación realista de 5G no sector ao que se orienta o ciclo formativo, considerando beneficios e retos.

### 4. Ferramentas de medición e visualización

A nivel educativo, tamén é útil incorporar ferramentas que permitan ver o estado da rede ou comprobar se un dispositivo está conectado a 5G.

- **SpeedTest** ou **Net Analyzer**: para comprobar a velocidade de conexión e a calidade da rede.
- **[CellMapper](https://www.cellmapper.net/map)**: aplicación que mostra a cobertura 5G real segundo operadores.
- **OpenSignal**: permite analizar en tempo real a experiencia do usuario en redes móbiles.

### 6. Actividades para a aula

**Actividades suxeridas para traballar o 5G con alumnado:**

| Actividade                           | Descrición                                                                            | Obxectivo                                                        |
| ------------------------------------ | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **Comparativa de redes**             | Medir latencia, velocidade e cobertura en diferentes tipos de conexión (WiFi, 4G, 5G) | Comprender vantaxes técnicas do 5G                               |
| **Análise de bulos sobre 5G**        | Avaliar a veracidade de noticias sobre o impacto do 5G                                | Fomentar pensamento crítico e alfabetización mediática           |
| **Deseño dun servizo baseado en 5G** | Propoñer unha aplicación industrial, sanitaria ou loxística usando capacidades do 5G  | Desenvolver competencias de innovación e resolución de problemas |
| **Estudo de caso real**              | Analizar un proxecto piloto de implantación de 5G en España ou Europa                 | Relacionar teoría con realidade do sector                        |
