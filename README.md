<h1>Gestión de UA Projects S.L</h1>
    <h2>0. Componentes del equipo</h2>
    <ul>
    <li>Adrián Herrero Bernabéu</li>
    <li>Adrián Ruiz Garcia</li>
    <li>Iván Pérez Inchaurtieta</li>
    <li>Noel Martínez Pomares</li>
    </ul>
    <h2>1. Objetivos</h2>
<p>El objetivo del proyecto es desarrollar una aplicación web de gestión y seguimiento de
incidencias en UA Projects S.L</p>
<h3>Estado actual</h3>
<p>Actualmente la empresa UA Projects S.L está teniendo retrasos a la hora de entregar
proyectos a los clientes y ningún empleado asume la responsabilidad de dicho retraso, se
va pasando la culpa de uno a otro y los jefes de proyecto no saben de dónde vienen los
problemas para entregar los proyectos a tiempo.</p>
<h3>Alcance</h3>
<p>UA Projects S.L desea tener un mayor control sobre las incidencias que surgen en el
transcurso de los proyectos que llevan a cabo en todos los departamentos de la empresa,
es por ello que pretende tener un control total sobre los problemas que tienen los
empleados para desarrollar un proyecto en un periodo de tiempo y así conocer el tiempo
real que se ha utilizado para finalizar un proyecto o las razones por las cuales se ha
retrasado.
<br>
Con estas funcionalidades se pretende conocer en qué tareas o departamentos se genera
más desperdicio de tiempo y si hay problemas en común en los que se pueda aplicar una
solución general.</p>
<h2>2. Descripción</h2>
Usaremos una base de datos donde se almacenarán y gestionarán cinco entidades
diferentes.
<ul>
<li>Users almacenará los distintos empleados de la empresa.</li>
<li>Repositories almacenará los distintos repositorios de la empresa, donde se
encuentran las ramas, código y los problemas.</li>
<li>En los repositorios habrán Projects, donde podrán ocurrir los problemas de la
empresa.</li>
<li>En cada proyecto habrá distintas Branches; es decir, distintas ramas, para que cada
empleado o grupo de empleados pueda trabajar por separado de los demás.</li>
<li>Issues almacenará los distintos problemas que surjan en los proyectos o en las
ramas, dentro de los repositorios.</li>
</ul>
<h3>Aplicación de gestión (back-end)</h3>
La aplicación de gestión interna permitirá a los empleados de la empresa acceder mediante
su usuario y contraseña para poder registrar los diferentes problemas encontrados y
especificar en qué repositorio/proyecto/rama se encuentran. También podrán buscar
soluciones a sus problemas, así como ayudar en los problemas de los demás empleados
de la empresa.
Todas estas operaciones se realizarán mediante un interfaz web que permita realizar las
operaciones de altas, bajas, modificaciones y consultas de problemas (issues).
<h3>Aplicación pública (front-end)</h3>
El frontend consta de varias zonas de diferente nivel de acceso.
Si no has iniciado sesión solo podrás acceder al login y al formulario de registro.
Una vez iniciada la sesión existen dos tipos de usuarios.
<strong>Jefes de proyecto</strong>
Los jefes de proyecto son capaces de gestionar los proyectos de la empresa de tal
forma que pueden realizar las 4 acciones básicas sobre los mismos (crear, borrar,
ver los datos de un proyecto y editar los). Además de esto, son capaces de asignar
desarrolladores a dichos proyectos para que puedan realizar su trabajo
correctamente.
<strong>Desarrolladores</strong>
Son los que llevan a cabo los proyectos. En dichos proyectos pueden crear
incidencias y reportar los problemas de los mismos de tal forma que sean visibles a
todos los desarrolladores asignados a ese proyecto o incidencia.
El frontend debe ser sencillo de utilizar y no mostrar las zonas privadas a usuarios que no
consten de los permisos necesarios para visitar dichas rutas. Por ejemplo, la página de
crear proyectos no es accesible para los desarrolladores.
Además de esto se tendrá en consideración cosas como la paleta de colores y patrones de
experiencia de usuario para cumplir los objetivos mencionados y asegurar la calidad no solo
de la aplicación si no la experiencia de los trabajadores con la misma.
<h2>3. Público Objetivo</h2>
Toda nuestra aplicación está destinada a la empresa UA Projects S.L.
La aplicación de gestión interna estará dirigida a los jefes de proyecto que quieran visualizar
los distintos repositorios/proyectos de la empresa y a los desarrolladores que quieran
acceder a distintos repositorios/issues.
La web pública, pese a ser mostrada a desarrolladores de una empresa y no al público
general, deberá tener una interfaz fácil de usar y eficaz, ya que la visualización y el
mantenimiento de cada repositorio es clave para el desarrollo de los distintos proyectos que
pueda tener la empresa simultáneamente.
