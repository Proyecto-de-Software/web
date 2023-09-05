# Infraestructura del servidor la cátedra

Información de la infraestructura del servidor de la asignatura Proyecto de Software.

## Infraestructura

![infraestructura](images/infraestructura.png)

## Versiones a utilizar

- Lenguaje: <strong>Python 3.8.10</strong>.
- Servidor Web: <strong>nginx/1.18.0 (Ubuntu)</strong>.
- Dependencias Python: <strong>Poetry (1.6.1)</strong>.
<!--- - Servidor de Base de Datos: <strong>PostgreSQL 15</strong>. -->
<!--- - Node: <strong>v14.20.0 (npm 6.14.17)</strong>. -->

## Código en el server para cada grupo

<label for="number">
  <strong>Número</strong>

  <input type="number" min=0 step=1 value=0 class="md-input link" id="number" pattern="[0-9]+">
</label>

[:material-link: Admin - Grupo #00](https://admin-grupo00.proyecto2023.linti.unlp.edu.ar/){ .md-button .md-button--primary .link #admin-link }

[:material-link: Portal - Grupo #00](https://grupo00.proyecto2023.linti.unlp.edu.ar/){ .md-button .md-button--primary .link #portal-link }

## Logs

!!! Info
    Pronto se publicarán los enlaces para poder visualizar los logs.

## Detalles de la infraestructura

### En sus máquinas de desarrollo

- Par de claves SSH.
- Repositorio Git Clonado.
- Dependencias instaladas con Poetry.
- Uso de ambiente de development (<strong>FLASK_ENV=development</strong>).

### En Gitlab

- Repositorio Central de Git.
- El deploy de la aplicación se realizará automáticamente con cada push a main.
- Para que se pueda realizar correctamente tenga en cuenta las definiciones
  de la cátedra respecto a los requisitos que debe cumplir el proyecto.
