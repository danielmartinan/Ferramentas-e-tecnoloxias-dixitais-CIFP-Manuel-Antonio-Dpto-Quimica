# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## Ciberseguridade nos sectores produtivos

## 1. Introdución

A medida que as empresas incorporan tecnoloxías dixitais, tamén aumentan os riscos de sufrir ciberataques que poden comprometer datos, procesos e infraestruturas críticas. A ciberseguridade non é só unha cuestión técnica, senón tamén organizativa e formativa. O módulo de *Digitalización* debe introducir ao alumnado nos principios básicos da seguridade dixital, tanto no contexto de sistemas IT como OT (tecnoloxías operativas).

## 2. Principios fundamentais da ciberseguridade

- **Confidencialidade:** os datos só deben estar dispoñibles para quen teña permiso.
- **Integridade:** os datos e sistemas non deben ser alterados de forma non autorizada.
- **Dispoñibilidade:** os sistemas e servizos deben estar accesibles cando se precisan.
- **Autenticación:** verificar a identidade do usuario ou dispositivo.
- **Trazabilidade:** rexistrar quen fixo que acción e cando (logs e auditoría).

## 3. Tipos de ameazas e riscos

A ciberseguridade implica protexer sistemas, redes e datos contra unha ampla gama de ameazas. Aquí tes unha táboa con algúns tipos comúns de ameazas e exemplos asociados:

| Tipo de ameaza                    | Exemplo                                                           |
| --------------------------------- | ----------------------------------------------------------------- |
| Malware (vírus, ransomware, etc.) | Encriptación de datos para pedir rescate                          |
| Phishing                          | Correo fraudulento para roubar credenciais                        |
| Ataques de forza bruta            | Intento masivo de adiviñar contrasinais                           |
| Ataques DDoS                      | Colapsar un servizo saturándoo con solicitudes                    |
| Erros humanos                     | Contrasinais febles, perda de dispositivos, enlaces maliciosos    |
| Fallos nos sistemas               | Software sen actualizar, portas abertas, configuracións inseguras |

## 4. Seguridade en contornas IT e OT

A ciberseguridade aplica tanto a contornas IT como OT, pero cada unha ten características e retos específicos:

- **IT (Information Technology):** protección de redes, servidores, ordenadores, datos persoais e corporativos.
- **OT (Operational Technology):** sistemas industriais como SCADA, PLCs, sensores; máis vulnerables por estar deseñados sen seguridade de rede nativa.

👉 **Reto actual:** converxencia IT/OT → máis exposición e necesidade de medidas de protección específicas.

## 5. Boas prácticas e medidas de protección

A ciberseguridade require un enfoque en capas, onde cada nivel aporta unha protección adicional. Aquí tes unha táboa con medidas recomendadas segundo o nivel de responsabilidade:

| Nivel                | Medidas recomendadas                                                                 |
| -------------------- | ------------------------------------------------------------------------------------ |
| Usuario              | Formación, contrasinais robustos, autenticación dúas fases, desconfianza por defecto |
| Sistemas e redes     | Antivirus, firewall, segmentación de redes, actualización de sistemas                |
| Aplicacións          | Xestión de permisos, cifrado, rexistros de acceso, backups regulares                 |
| Empresa/organización | Políticas de seguridade, plans de continxencia e recuperación, auditorías            |

## Contrasinais e autenticación

As contrasinais son unha das primeiras liñas de defensa contra accesos non autorizados. Aquí tes algúns conceptos clave.

### Boas prácticas

Algunhas boas prácticas para a xestión de contrasinais son:

- Contraseña compleja:
    - Longa (mínimo 12 caracteres)
    - Combinación de maiúsculas, minúsculas, números e símbolos
- Contraseña diferente:
    - Non reutilizar contrasinais en diferentes servizos
    - Non usar información persoal facilmente adiviñable
- Contraseña aséptica:
    - No vinculadas a datas ou eventos persoais
    - Non usar palabras comúns ou patróns predecibles
- Contraseña intransferible:
    - Non enviar contrasinais por correo electrónico ou mensaxería
    - Non escribir contrasinais en lugares visibles
- Contraseña a buen recaudo
    - Uso de xestores de contrasinais para almacenar e xestionar contrasinais complexos

### Autenticación multifactor

A autenticación multifactor (MFA) engade unha capa adicional de seguridade ao requirir máis dunha forma de verificación. Aquí tes algúns tipos:

- Autenticacion en dous pasos (2FA)
    - Combinación de algo que sabes (contrasinal) e algo que tes (código enviado ao móbil)
- Autenticación en tres pasos (3FA)
    - Combinación de algo que sabes, algo que tes e algo que es (biometría)
- Autenticación en cuatro pasos (4FA)
    - Combinación de algo que sabes, algo que tes, algo que es e un comportamento (como a xeolocalización). Utilizado en contornas de alta seguridade.

### Protección de la información crítica

- Política de mesas limpias
- Bloqueo de sesión
- Software de protección
- Actualizaciones periódicas de SW
- Cifrado de datos
- Copias de seguridad
- Uso de dispositivos externos

## 6. Normativa e estándares relevantes

A ciberseguridade tamén está regulada por normativas e estándares que establecen requisitos mínimos de protección. Algúns dos máis relevantes son:

- **Regulamento Xeral de Protección de Datos (RGPD):** protexe os datos persoais dos cidadáns da UE.
- **Esquema Nacional de Seguridade (ENS):** marco de referencia para organismos públicos.
- **ISO 27001:** norma internacional para sistemas de xestión da seguridade da información.
- **NIST Cybersecurity Framework:** marco para mellorar a xestión do risco de ciberseguridade.

Hai que ter en conta que a ciberseguridade é un campo en constante evolución, polo que é importante manterse actualizado sobre novas ameazas e medidas de protección, así coma actualizacións da normativa vixente.

## 7. Ferramentas e recursos para traballar na aula

A ciberseguridade require ferramentas específicas para a formación práctica e a simulación de escenarios reais. Aquí tes unha selección de recursos útiles:

### 7.1 Formación e simulación

- **Cybersecurity Lab (NOVA PBS):** simulador interactivo de ataques e defensa (en inglés).
- **CyberRange / Hack The Box / TryHackMe:** laboratorios virtuais para aprender seguridade ofensiva e defensiva.
- **PhishSim:** simulación de correos de phishing para sensibilización.

### 7.2 Auditoría e detección

- **Wireshark:** análise de tráfico de rede.
- **Kali Linux:** distribución con ferramentas de análise e pentesting (uso controlado e ético).
- **OpenVAS / Nessus:** escáneres de vulnerabilidades.

### 7.3 Xestión e concienciación

- **Have I Been Pwned:** comprobar se un correo foi filtrado en ataques pasados.
- **Bitwarden / KeePass:** xestores de contrasinais para promover bos hábitos.
- **Security Awareness Trainings (Google, Cisco, ESET):** cursos gratuítos para usuarios.
- [Kit de concienciación de Incibe](https://www.incibe.es/empresas/formacion/kit-concienciacion): recursos para sensibilizar sobre ciberseguridade.

## 8. Propostas de actividades para alumnado

| Actividade                              | Obxectivo pedagóxico                                                           |
| --------------------------------------- | ------------------------------------------------------------------------------ |
| Crear un protocolo de seguridade básico | Comprender as políticas e procedementos dunha empresa                          |
| Análise dun caso real de ciberataque    | Desenvolver pensamento crítico e capacidade de análise                         |
| Taller de phishing (simulado)           | Identificar sinais de correos fraudulentos                                     |
| Instalar un xestor de contrasinais      | Promover hábitos seguros no uso das TIC                                        |
| Mapear os dispositivos dunha rede local | Introducir ferramentas de escaneo e concienciación sobre exposición            |
| Simulación de resposta ante incidente   | Traballar en equipo e coñecer procesos de detección, contención e recuperación |

## 9. Recomendacións para a docencia

- **Non alarmar**, pero si **concienciar**: a seguridade debe ser transversal e práctica.
- Adaptar o nivel ao contexto do ciclo: non é necesario profundar en hacking ético, pero si en seguridade aplicada.
- Fomentar a **responsabilidade dixital**, tamén nas redes sociais e no uso da nube.
- Enfatizar a importancia de **avaliar riscos antes de dixitalizar procesos produtivos**.
