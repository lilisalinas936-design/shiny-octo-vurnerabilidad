# Propósito del Proyecto

Este proyecto documenta una investigación sobre vulnerabilidades de seguridad cibernética, incluyendo ataques de malware avanzado, acceso no autorizado a cuentas de correo, y compromisos de sistemas bancarios.

## Investigación: Vulnerabilidades de Seguridad Cibernética

### Alcance
Investigación preventiva sobre seguridad de instaladores y gestión de paquetes.

### Metodología
Análisis de casos técnicos públicos (spec-kit) con control de versiones, verificación SHA-256 y revisión por pares.

### Hallazgos

#### Contexto técnico - DOC-20260910-WA0011.pdf
- 3 entradas en caché de `com.ezt.pdfreader.pdfviewer`
- Tiempos registrados: 01/12/2025 11:56 PY, 03/12/2025 21:38 PY, 19/12/2025 19:21 PY
- Campo `tiempo`: significado exacto pendiente de determinar
- No contiene contenido de los ZIP/JPG

#### Casos de estudio
- PR #4769: seguridad de instaladores (bloqueo concurrente, persistencia atómica, validación antes de modificar)
- Issue #4781: ejemplo de manifiesto con `verified:false` = no verificado en catálogo

### Referencias
- GitHub spec-kit PR #4769
- GitHub spec-kit Issue #4781