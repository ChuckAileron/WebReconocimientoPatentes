# WebReconocimientoPatentes

<h2>Características</h2>
<h3>Version 1:</h3>
<ul>
  <li>Login y registro</li>
  <li>Mostrar patentes registradas y detalle</li>
  <li>Agregar nuevo vehículo</li>
</ul>
<h3>Errores Version 1:</h3>
<ul>
  <li>Update: No encuentra vehículo para modificar</li>
  <li>Delete: No encuentra vehículo para eliminar</li>
</ul>


<h3>Version 2:</h3>
<ul>
  <li>Login y registro</li>
  <li>Mostrar patentes registradas y detalle</li>
  <li>Agregar nuevo vehículo</li>
  <li>Buscar Vehículo</li>
  <li>Error Update solucionado</li>
  <li>Error Delete solucionado</li>  
</ul>

<h2>Ejecución:</h2>
<ul>
  <li>En consola/terminal ubicarse en carpeta proyecto (la primera)</li>
  <li>Si se está usando en Ubuntu ejecutar lo siguiente, de lo contrario continuar con el paso siguiente</li>
  <ul>
    <li>sudo lsof -t -i tcp:8000 | xargs kill -9</li>
  </ul>
  <li>Ejecutar</li>
  <ul>
    <li>python manage.py migrate</li>
    <li>python manage.py runserver</li>
  </ul>
</ul>
