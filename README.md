# 2024-tienda-g9
IS2024 - Trabajo Final Integrador - Grupo N° 9 

## Integrantes
- [Lucas Dante Depetris](https://github.com/lucasdepetrisd)
- [Camila Rodríguez](https://github.com/rod-cami)

# Frontend

# Backend

## Tecnologías Utilizadas
- Desarrollamos una API en .NET Core 8 para el backend, la cual se comunica con una base de datos SQL Server para la persistencia de datos. Desplegamos a ambos en los servicios de Azure para garantizar su disponibilidad y escalabilidad.
- Construimos tests unitarios y de aceptación con Gherkin utilizando Specflow.
- Creamos un flujo automatizado en GitHub Actions para CI/CD.
  1. Realizamos la compilación del código (build) y ejecutamos pruebas automatizadas (test) en cada commit.
  2. Si las pruebas son exitosas, desplegamos la aplicación en Azure.
  3. Además, generamos documentación LivingDocs y la publicamos en GitHub Pages para visualizar los resultados de las pruebas de manera accesible.
  - Link a la última documentación: [LivingDocs - GitHub Pages](https://lucasdepetrisd.github.io/TiendaAPI/LivingDoc.html#/document/Standalone)
  - Link al último flujo de GH Actions: [Build test and deploy ASP.Net Core app to Azure Web App - GitHub Actions
](https://github.com/lucasdepetrisd/TiendaAPI/actions/runs/8335155080)

## Arquitectura
![Arquitectura](https://github.com/lucasdepetrisd/TiendaAPI/blob/main/docs/Arquitectura.png)

## Test Automatizados
![Resultados Tests](https://github.com/lucasdepetrisd/TiendaAPI/blob/main/docs/LivingDocs.png)



---

# Anexos

## Diagrama de Clases
![Diagrama de Clases](https://github.com/lucasdepetrisd/TiendaAPI/blob/main/docs/ClassDiagram.png)

## Diagrama de Base de Datos
![Diagrama de Base de Datos](https://github.com/lucasdepetrisd/TiendaAPI/blob/main/docs/DatabaseDiagram.png)
