gantt
    title Planificación del Proyecto
    dateFormat  YYYY-MM-DD
    axisFormat  %d-%b
    
    section Fase 1: Planificación
    Definición del alcance       :done,    des1, 2026-11-01, 2026-11-05
    Investigación y análisis     :active,  des2, 2026-11-04, 2026-11-10
    Aprobación del proyecto      :crit,    des3, 2026-11-11, 2d

    section Fase 2: Desarrollo
    Diseño de arquitectura       :         des4, 2026-11-13, 5d
    Desarrollo Frontend          :         des5, after des4, 10d
    Desarrollo Backend           :         des6, after des4, 12d

    section Fase 3: Pruebas y Entrega
    Pruebas de integración       :         des7, after des6, 5d
    Despliegue a producción     :crit,    des8, after des7, 2d
