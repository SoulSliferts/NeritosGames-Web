# NeritosGames-Web
![Estado](https://img.shields.io/badge/Estado-Desplegado-green)
![Web](https://img.shields.io/badge/Web-Django-darkgreen)
![Diseño](https://img.shields.io/badge/Dise%C3%B1o-Figma-purple)
![Editor](https://img.shields.io/badge/Editor-VisualStudioCode-blue)
![Host](https://img.shields.io/badge/Host-Render-red)
![App](https://img.shields.io/badge/App-Web-white)
![Version](https://img.shields.io/badge/Versi%C3%B3n-1.0-black)

## Tabla de Contenidos
- [Descripción](#descripción)
- [Info Rapida](#info-rapida)
- [Características Principales](#características-principales)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Hoja de Bugs](#hoja-de-bugs)
- [Diseño](#diseño)
- [Contacto](#contacto)


# Descripción

🎮 ¡El portal digital oficial de NeritosGames! Descubre eventos, explora nuestro catálogo de juegos, consulta horarios y mantente conectado con nuestra comunidad. Visítanos en [neritosweb.onrender.com](https://neritosweb.onrender.com).

## Info Rapida

* Fecha de Inicio del proyecto: 4 abril
* Fecha de Finalizacion del proyecto: 25 abril

**Esta tabla ofrece una estimación general del tipo de tareas comunes en el desarrollo y mantenimiento de NeritosGames-Web, basado en un tiempo total de desarrollo aproximado de 504 horas:**
<table>
    <thead>
        <tr>
            <td>Tipo De Accion</td>
            <td>Tiempo Aproximado(Horas)</td>
            <td>Dificultad</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Desarrollo Frontend</strong></td>
            <td>10 - 16 hrs</td>
            <td>Media / Alta</td>
        </tr>
        <tr>
            <td><strong>Desarrollo Backend</strong></td>
            <td>12 - 24 hrs</td>
            <td>Media / Alta</td>
        </tr>
        <tr>
            <td><strong>Diseño UI/UX</strong></td>
            <td>11 - 30 hrs</td>
            <td>Media / Alta</td>
        </tr>
        <tr>
            <td><strong>Base De Datos</strong></td>
            <td>1 - 3 hrs</td>
            <td>Baja / Media</td>
        </tr>
        <tr>
            <td><strong>Configuracion / Despliegue</strong></td>
            <td>0.5 - 2 hrs</td>
            <td>Baja / Media</td>
        </tr>
        <tr>
            <td><strong>Resolucion de Bugs</strong></td>
            <td>1 - 8 hrs</td>
            <td>Variable (Baja a Alta)</td>
        </tr>
        <tr>
            <td><strong>Añadir Caracteristicas o Rediseñar</strong></td>
            <td>4 - 10 hrs</td>
            <td>Media / Alta</td>
        </tr>
</table>

> **Nota:** Los tiempos y dificultades son estimaciones del esfuerzo requerido para tareas individuales representativas dentro del proyecto. La complejidad específica de cada tarea puede variar

## Características Principales
*   📅 Malla de Turnos en Tiempo Real: Consulta los turnos disponibles para juegos como In The Groove, Pump It Up, Dance Dance Revolution, JustDance, Taiko y Wii, con filtros por semanas y meses para planificación a largo plazo.
*   🏆 Tabla de Clasificación de Usuarios: Visualiza el ranking de usuarios basado en su cantidad de visitas, diferenciando entre clientes Neritos y Premium.
*   💵 Precios y Beneficios: Accede a tablas de precios actualizadas para cada tipo de turno, incluyendo los beneficios exclusivos para usuarios Premium en todos los juegos disponibles.
*   🎯 Zona de Retos Semanales: Participa en desafíos de In The Groove y Pump It Up, completa hasta 5 retos por semana y sigue tu progreso en la tabla de clasificación de puntos acumulados.

## Tecnologías Utilizadas
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>&nbsp;
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>&nbsp;
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>&nbsp;
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>&nbsp;
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>&nbsp;
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render"/>&nbsp;
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>&nbsp;
</p>

## Hoja de Bugs

Ruta de Bugs que surgieron mientras se desarrollaba el proyecto, cada color representa la dificultad(rojo dificil y verde facil):

**Turnos**
- 🔴 Bug 1: Dias y Semanas en ingles
- 🟢 Bug 2: Horas disponibles rotas de horario nocturno
- 🟢 Bug 3: Selects Dias y Semanas intercalados(semanas y meses desordenas o textos rotos)
- 🟢 Bug 4: Pestañas intercambiables rotas para la malla de turnos
- 🟢 Bug 5: Fondo de pestaña no aparece o no intercala
- 🔴 Bug 6: Turnos no correctos o fuera del rango

**Tabal de clasificacion de usuarios**

- 🔴 Bug 1: No hay resultados disponibles aun cuando en la base de datos si existen datos
- 🟢 Bug 2: Los usuarios no estan ordenados
- 🟢 Bug 3: Iconos rotos


**Precios y Beneficios**

- 🟢 Bug 1: Fondo no cambiante entre tablas
- 🔴 Bug 2: Imagenes y svgs rotos
- 🟢 Bug 3: Footer con display mas pequeño de los esperado
- 🟢 Bug 4: Cards no responsive

**Retos**

- 🟢 Bug 1: Cards rotas
- 🔴 Bug 2: Sumatoria Itg no funcional(Calculo no correcto entre Total x y Total y)
- 🟢 Bug 3: Orden de usuarios mal hecho
- 🟢 Bug 4: Iconos rotos
- 🔴 Bug 5: Sumatoria Pump no funcional(Calculo no correcto entre Total x y Total custom)
- 🟢 Bug 6: Puntajes subidos no correctos


## Diseño