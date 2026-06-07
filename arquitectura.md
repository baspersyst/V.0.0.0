# ARQUITECTURA MAESTRA Y CONTRATOS MODULARES

*Aquí se definen los contratos de cada módulo ANTES de escribir el código fuente.*

## 🗺️ Mapa del Ecosistema Minimalista

Actualmente el sistema mantiene una estructura fundacional que se expandirá a demanda. Se divide en Módulos Ejecutables y Recursos Estáticos.

---

### MÓDULOS EJECUTABLES

#### MÓDULO: M0_CORE
- **RESPONSABILIDAD ÚNICA:** [TBD: Proveer el esqueleto y punto de entrada unificado para la inicialización del sistema.]
- **RECIBE:** [TBD: parámetros de arranque]
- **PRODUCE:** [TBD: instancia de la aplicación ejecutándose]
- **ALMACENA:** nada
- **DEPENDE DE:** nada (en la versión actual)
- **NO DEBE:** contener lógica de negocio directa ni cálculos pesados.
- **VERSIÓN INICIAL:** v0.1.0

---

### RECURSOS ESTÁTICOS Y SKILLS

Los recursos son herramientas, prompts o configuraciones estáticas consumidas por el ecosistema (humanos o agentes).

#### [SKILL] Organizador
- **Función:** Escanear carpetas específicas en búsqueda del formato pedido por el usuario, validar su estructura y emitir un reporte o realizar acciones correctivas.
