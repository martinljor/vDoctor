# vDoctor

vDoctor for VBR v12/v13 by MJ.

Herramienta de solo lectura para Veeam Backup & Replication: RPO y recuperabilidad por workload,
restore points por job, workload y repositorio, y deep dive de bases SQL Server y Oracle.

**Descarga:** [última versión](https://github.com/martinljor/vDoctor/releases/latest)

**Permisos:** una cuenta de VBR con el rol Veeam Backup Administrator (la API REST de VBR v12 y v13 no acepta otros roles). vDoctor solo hace lecturas.

Se ejecuta y abre la consola en http://127.0.0.1:8001/. Solo lectura; las credenciales viven solo en memoria.
