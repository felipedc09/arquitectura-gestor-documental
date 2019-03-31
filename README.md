# Arquitectura Gestor Documental

Propuesta sobre la arquitectura para sistema de gestión documental.

## Integrantes

- Felipe Duitama - 20112020005

## Definición de requerimientos (forma general)

- Gestión de documentos: ingreso de documentos, cambio de estados, almacenamiento(archivar)
- Gestión de dependencias (organizacionales)
- Gestión de procesos: flujos entre dependencias

## Propuesta de arquitura

Se debe emplear una arquitectura orientda a servicios que permita separar 3 factores principales para el funcionamiento de la solucón general: la gestión de documentos, gestión de procesos y gestion de dependencias. Estos tres componentes pueden mantenerse de forma independiente y así utilizar diferentes tecnologias en su implementación para que genere nua solución fiable y escalable.

## Diagrama de arquitectura

![Alt text](Propuesta%20arquitectura.png?raw=true "Arquitectura")
