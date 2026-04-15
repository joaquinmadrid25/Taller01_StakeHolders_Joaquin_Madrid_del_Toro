# Materialidad para Consultora Web

## Fase 1: Investigación Rigurosa (10 min)

Este análisis se basa en el documento `BBDD_Academicas` y en la búsqueda de términos clave como "Green IT" y "Materiality in ICT". El objetivo fue identificar los grupos de interés y temas materiales más relevantes para una consultora web.

### Grupos de interés clave
- **Clientes**: usuarios finales interesados en la seguridad, rendimiento y accesibilidad de los productos digitales.
- **Empleados**: desarrolladores y consultores que necesitan prácticas laborales responsables y herramientas de trabajo sostenibles.
- **Comunidad y reguladores**: entes externos que demandan transparencia, cumplimiento normativo y reducción del impacto ambiental.

### Temas materiales seleccionados
- **Eficiencia energética del código** — ASG: Ambiental
- **Accesibilidad universal** — ASG: Social
- **Privacidad de datos** — ASG: Gobernanza

### Fuentes (IEEE)
[1] W3C, "Web Content Accessibility Guidelines (WCAG) 2.1," 2018.

[2] European Parliament, "Regulation (EU) 2016/679 (General Data Protection Regulation)," 2016.

[3] J. Koomey, "Estimating Total Power Consumption by Servers in the U.S. and the World," Stanford University, 2007.

## Fase 2: Estructuración en XML (20 min)

El archivo `materialidad.xml` contiene una estructura clara y bien formada:
- Raíz: `<empresa_sostenible>`
- Nodos `<stakeholder>` con atributos `importancia` y `nombre`
- Nodos `<tema_material>` con `descripcion` y `nivel_impacto`
- Atributo `nivel_asg` con valores ASG: `Ambiental`, `Social`, `Gobernanza`

Esto garantiza un modelo XML aplicable a consultoras web que quieren integrar criterios ASG en sus análisis de materialidad.

## Fase 3: Documentación y GitHub (20 min)

Este `README.md` explica la investigación, la estructura XML y la finalidad del entregable. El repositorio incluye `materialidad.xml` y su esquema de validación (`materialidad.xsd`).

## Uso
1. Abrir `materialidad.xml` en un editor XML.
2. Validar la estructura con `materialidad.xsd`.
3. Adaptar los stakeholders y temas materiales según el cliente o proyecto.

## Objetivo
Ofrecer un entregable profesional que documente los principales grupos de interés y temas materiales ASG para una consultora web.
