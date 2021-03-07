# Acta 3

- Fecha: 7 de Marzo de 2021
- Hora: 10:00
- Lugar: Google Meet
- Asistentes:
  - Equipo

## Se habla

### Organización

- Se decide establecer la **reunión semanal** los Martes de 12 a 2 de la mañana
  - https://omnipointment.com/yfDDv0YDXpFCnwNo5eoO
- Se decide responsabilizar a cada uno individualmente de llevar las horas de trabajo y en la reunión semanal se actualizará en el form de Google
- Se decide el gestor del proyecto: Arturo
- Se contempla la posibilidad de penalizar a los que lleguen tarde a cualquier reunión propuesta por todo el equipo
- Se decide aumentar la funcionalidad del proyecto:
  - Para alcanzar el nivel 9, con la posibilidad de guardar ficheros, cifrados
  - Para alcanzar el nivel 10, con implementación de un plug-in (Chrome ?)
  - Más detalles sobre la funcionalidad en el plan de gestión y análisis de diseño (V1) a entregar próximamente.
  - No hace falta actualizarlo en la propuesta entregada
- Se decide entregar las actas semanalmente, incluyendo las de todas las reuniones en el periodo entre entregas.
- Se ha creado una cuenta de gmail para todos (barabarasoft@gmail.es)
- Se ha discutido la organización de los grupos de trabajo:
  - 2 equipos (2-4)
    - _Backend_:
      - Andoni
      - Arturo
    - _Frontend_:
      - Bellvis
      - Bernal
      - Borque
      - Vela

### Documentación

- Se decide documentar el proyecto
  - Carácter general, análisis, diseño de sistema: WIKI de GitHub de repositorio público de documentación
  - Específico al código, enlaces StackOverflow, descripciones de librerías: WIKI de GitHub de repositorio público de código

### Despliegue

- MongoDB: Utilizaremos Mongo Atlas, permite crear base de datos remota y conectar backend a ella mediante URL y credenciales de acceso
- Backend y frontend: VARIAS OPCIONES (CLOUD)
  - Monolítico: en una misma máquina
  - Varias máquinas virtuales (front end y backend)
- Se considera Kubernetes "matar moscas a cañonazos"
- Queremos utilizar Cloud : **Amazon AWS**, se decide por interés general de todos y ningún conocimiento previo por parte de todos.

![picture 2](images/3108e585fd348acfcae1fcd1505d76ed1f7a63ca79c2956ae775abd33b6dea9e.png)

#### Despliegue continuo - GitHub Actions

- Asegurar un despliegue sobre el que construir el sistema
- Cada vez que se vaya actualizando el repositorio ir actualizando con GitHub Actions

#### BBDD - Mongo - Atlas

- Se ha creado una cuenta en Atlas, se ha creado la base de datos, 3 réplicas y se a verificado su conexión desde Compass.

#### Amazon AWS

Se crea una cuenta de Amazon AWS (barbarosoft)

### Análisis, Diseño

#### Mockups interfaz

- Utilizar Adobe XD para realizar prototipos de interfaz

### Primer despliegue

- Se ha decidido tener para la siguiente tutoría un despliegue inicial básico sin funcionalidad para comporbar el correcto funcionamiento e interacción entre BD, BE y FE.

## Siguiente reunión

Martes 9 a las 12 de la mañana
