# ProyectoFinal
Proyecto creado por Dairy Pernillo -  UMG Programacion III
┌─────────────────────────────────────────────────────────┐
│                      MANUAL DE USUARIO                 					    │
│         Gestión de Equipos de Fútbol (Windows Forms)    						│
└─────────────────────────────────────────────────────────┘

╔═════════════════════════════════════════════════════════╗
║ 1. Introducción                                         
╚═════════════════════════════════════════════════════════╝

Este manual te guiará en el uso de la aplicación "Gestión de Equipos de Fútbol". 
La aplicación permite agregar, buscar y gestionar equipos de fútbol de manera 
eficiente utilizando una interfaz de usuario amigable.

╔═════════════════════════════════════════════════════════╗
║ 2. Requisitos del Sistema                               ║
╚═════════════════════════════════════════════════════════╝

- Sistema Operativo: Windows 10 o superior.
- .NET Framework: Versión 4.7.2 o superior.
- Memoria RAM: Mínimo 2 GB.
- Espacio en Disco: 50 MB disponible para la instalación de la aplicación.

╔═════════════════════════════════════════════════════════╗
║ 3. Instalación                                          
╚═════════════════════════════════════════════════════════╝

1. **Descarga**:
   - Descarga el archivo de instalación (`GestionEquiposFutbolSetup.exe`) desde 
     el sitio web oficial o la ubicación proporcionada.

2. **Ejecutar Instalador**:
   - Haz doble clic en el archivo descargado.
   - Sigue las instrucciones del asistente de instalación.

3. **Finalizar Instalación**:
   - Una vez completada la instalación, encontrarás el acceso directo de la 
     aplicación en el menú de inicio o en el escritorio.

╔═════════════════════════════════════════════════════════╗
║ 4. Iniciar la Aplicación                                
╚═════════════════════════════════════════════════════════╝

1. **Abrir la Aplicación**:
   - Haz doble clic en el icono de la aplicación `Gestión de Equipos de Fútbol` 
     en tu escritorio o en el menú de inicio.

2. **Pantalla Principal**:
   - Al abrir la aplicación, verás la pantalla principal con las siguientes 
     secciones y controles:

   - Caja de texto: Para ingresar el nombre del equipo.
   - Botón "Agregar Equipo": Para agregar un nuevo equipo al sistema.
   - Botón "Buscar Equipo": Para buscar un equipo en el sistema.
   - Lista de Equipos: Muestra los equipos actualmente en el sistema.

╔═════════════════════════════════════════════════════════╗
║ 5. Uso de la Aplicación                                 
╚═════════════════════════════════════════════════════════╝

5.1 **Agregar un Equipo**

- **Paso 1**: Ingresa el nombre del equipo en el campo de texto `Nombre del equipo`.
- **Paso 2**: Haz clic en el botón `Agregar Equipo`.

**Resultado**:
- El equipo será añadido a la lista y se mostrará un mensaje de confirmación.
- La lista de equipos se actualizará automáticamente.

**Nota**:
- Si el campo de texto está vacío, la aplicación mostrará un mensaje solicitando 
  que ingreses un nombre de equipo.

5.2 **Buscar un Equipo**

- **Paso 1**: Ingresa el nombre del equipo que deseas buscar en el campo de texto 
  `Nombre del equipo`.
- **Paso 2**: Haz clic en el botón `Buscar Equipo`.

**Resultado**:
- Si el equipo existe, se mostrará un mensaje confirmando que el equipo fue 
  encontrado.
- Si el equipo no existe, se mostrará un mensaje indicando que el equipo no fue 
  encontrado.

5.3 **Visualizar la Lista de Equipos**

- La lista de equipos en el control `ListBox` se actualiza automáticamente después 
  de agregar o buscar equipos.
- Puedes ver todos los equipos almacenados actualmente en el sistema en esta lista.

╔═════════════════════════════════════════════════════════╗
║ 6. Funcionalidades Adicionales                          
╚═════════════════════════════════════════════════════════╝

6.1 **Actualización de la Lista de Equipos**

- La lista de equipos (`ListBox`) se actualizará cada vez que se añada un nuevo 
  equipo, mostrando todos los equipos ordenados alfabéticamente.

6.2 **Recorrido en Orden del Árbol AVL**

- La aplicación utiliza un árbol AVL para gestionar la lista de equipos, lo que 
  garantiza una búsqueda eficiente. La lista se actualiza mediante un recorrido 
  en orden de este árbol.

╔═════════════════════════════════════════════════════════╗
║ 7. Mantenimiento y Soporte                              
╚═════════════════════════════════════════════════════════╝

7.1 **Problemas Comunes**

- **El equipo no se agrega**:
  - Asegúrate de que el nombre del equipo no está vacío.
  - Verifica si el equipo ya existe en el sistema.
  
- **El equipo no se encuentra**:
  - Asegúrate de que el nombre ingresado es exactamente el mismo que el guardado 
    en el sistema.

7.2 **Contactar Soporte**

- Para asistencia técnica o reportar problemas:
  - **Email**: añlksdjfas
  - **Teléfono**: +502 2222 2222
  - **Sitio web**: DairyProyectoFinalsupport.com
╔═════════════════════════════════════════════════════════╗
║ 8. Actualización de la Aplicación                    						   
╚═════════════════════════════════════════════════════════╝

1. **Verificar Actualizaciones**:
   - Consulta la sección de "Actualizaciones" en el menú principal de la 
     aplicación.

2. **Instalar Actualizaciones**:
   - Sigue las instrucciones en pantalla para descargar e instalar la última 
     versión de la aplicación.

╔═════════════════════════════════════════════════════════╗
║ 9. Desinstalación                                       
╚═════════════════════════════════════════════════════════╝

1. **Acceder a Configuración**:
   - Abre el Panel de Control desde el menú de inicio.
   - Ve a `Programas y características`.

2. **Seleccionar la Aplicación**:
   - Encuentra `Gestión de Equipos de Fútbol` en la lista de programas instalados.

3. **Desinstalar**:
   - Haz clic en `Desinstalar` y sigue las instrucciones para completar la 
     desinstalación.

╔═════════════════════════════════════════════════════════╗
║ 10. Créditos                                            
╚═════════════════════════════════════════════════════════╝

- **Desarrollador**: Nombre del desarrollador o equipo.
- **Fecha de Creación**: Junio 2024.

╔═════════════════════════════════════════════════════════╗
║ 11. Apéndice                                            
╚═════════════════════════════════════════════════════════╝

11.1 **Terminología**

- **Arbol AVL**: Estructura de datos auto-balanceada que permite la inserción, 
  eliminación y búsqueda eficientes.
- **Nodo AVL**: Elemento del árbol AVL que contiene la información del equipo y 
  punteros a sus hijos izquierdo y derecho.

