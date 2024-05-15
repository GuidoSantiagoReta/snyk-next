
## Proyecto en nexts.js version  13.4.20 con vulnerabilidades

- pipeline CI con integración de snyk para detectar las vulnerabilidades de la versión.
- Las versiones de Next.js menores a la 13.4.20-canary.13 han sido marcadas como vulnerables al CVE-2023-46298 debido a una vulnerabilidad de alta severidad introducida en el sistema de seguridad. Esta vulnerabilidad fue identificada y discutida en el repositorio oficial de Next.js en GitHub, donde se menciona que el código afectado fue introducido alrededor de la versión 13.0.4, sugiriendo que al menos desde esa versión podría haberse presentado la vulnerabilidad. 
- Este pipeline verifica automáticamente las vulnerabilidades en tus dependencias cada vez que se realiza un push a la rama main o cuando se dispara manualmente, asegurando que tu proyecto está protegido contra vulnerabilidades conocidas. Además, mantiene actualizado ESLint y Next.js a versiones específicas para garantizar su compatibilidad y seguridad.
