
<h1 align="center">Laravel Base core ui Infyom</h1>
<p>pasos para instalar </p>
<ul>
    <li>git clone</li>
    <li>composer install</li>
    <li>cp .env.example .env</li>
    <ul>
        <li>cambiar datos de conexion a la base de datos</li>
    </ul>
    <li>php artisan key:generate</li>
    <li>php artisan storage:link</li>
    <li>php artisan passport:keys</li>
</ul>

<p>Instalaciones ya configuradas</p>

<ul>
        <li>"spatie/laravel-permission": "^3.17", <b> manejo de roles de usuario </b></li>
    <li>"yajra/laravel-datatables-buttons": "*", <b>datatables</b>  </li>
        <li>"yajra/laravel-datatables-html": "*", <b>  datatables </b> </li>
        <li>"yajra/laravel-datatables-oracle": "~9.0",  <b>datatables</b> </li>
        <li>"laravel/passport": "^9.3",     <b> para accesos apis </b></li>
        <li>"laravel/telescope": "*",        <b> monitoreo de acciones en el sistema errore, tiempos de consultas, X </b></li>
    </ul>
    
    
    <p>Comandos Basicos para hacer scaffold</p>
    <ul>
   <li> php artisan infyom:scaffold <Nombre Modelo> --fromTable --tableName=<nombre tabla></li>
    <li>php artisan   infyom:api_scaffold si se quiere conn api tambien</li>
   <li>php artisan infyom:api   solo el api</li>
    </ul>
    
