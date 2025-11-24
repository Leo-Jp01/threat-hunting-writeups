# Técnicas MITRE ATT&CK - Análisis con Atomic Red Team y Caldera MITRE

Laboratorio de análisis defensivo de técnicas ofensivas reales. Cada técnica sigue una metodología estructurada desde la simulación hasta la detección.

---

## Metodología de Análisis

Cada técnica documentada sigue este flujo:

1. **Preparación del entorno** (Lab setup con Atomic Red Team)
2. **Simulación controlada** (Ejecución de la técnica)
3. **Captura de telemetría** (Logs, eventos, tráfico)
4. **Análisis forense** (¿Qué pasó realmente?)
5. **Interpretación técnica** (¿Por qué dejó estos rastros?)
6. **Extracción de IoCs** (Indicadores de compromiso)
7. **Validación con herramientas** (Chainsaw, etc.)
8. **Desarrollo de detección** (Creación de reglas Wazuh)
9. **Testing & validación** (¿Funciona la regla?)
10. **Iteración y mejora** (Reducción de falsos positivos)

---

## Técnicas Analizadas

#### 01. Reconocimiento (Reconnaissance)

#### 02. Desarrollo de Recursos (Resource Development)

#### 03. Acceso Inicial (Initial Access)

#### 04. Ejecución (Execution)
- [T1059.001 - PowerShell](execution/t1059-001-powershell.md) [En Proceso]

#### 05. Persistencia (Persistence)

#### 06. Escalación de Privilegios (Privilege Escalation)

#### 07. Evasión de Defensas (Defense Evasion)

#### 08. Acceso a Credenciales (Credential Access)

#### 09. Descubrimiento (Discovery)

#### 10. Movimiento Lateral (Lateral Movement)

#### 11. Recolección (Collection)

#### 12. Comando y Control (Command and Control)

#### 13. Exfiltración (Exfiltration)

#### 14. Impacto (Impact)



---

## Herramientas Utilizadas

| Herramienta | Propósito |
|-------------|-----------|
| **Atomic Red Team** y **Caldera MITRE**| Simulación de técnicas ATT&CK |
| **Sysmon** | Telemetría avanzada de Windows |
| **Chainsaw** | Análisis rápido de event logs |
| **Wazuh** | SIEM y motor de detección |
| **Process Monitor** | Análisis en tiempo real de procesos |
| **Wireshark** | Captura y análisis de tráfico de red |

---

## Estadísticas del Laboratorio

- **Técnicas analizadas:** 1/12
- **Reglas Wazuh creadas:** 1
- **Reglas Sigma convertidas:** 1
- **Casos de uso documentados:** 0

---

## Recursos de Aprendizaje

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Atomic Red Team - Official Docs](https://github.com/redcanaryco/atomic-red-team)
- [Wazuh Detection Rules](https://documentation.wazuh.com/current/user-manual/ruleset/index.html)

---
[← Ver Técnicas Individuales](../techniques/index.md)\
[← Volver al inicio](../index.md)

---
**Última actualización:** 2025-11-22  
**Total de técnicas completados:** 0 / 8 planeados
