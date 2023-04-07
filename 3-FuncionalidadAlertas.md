<!---![LogoKabyle-Sinfondo-palabraKabYle](https://github.com/kabyleuy/kabyle2/blob/main/resources/LogoKabyle-Sinfondo-palabraKabYle.png?raw=true)--->
<!---![PalabraKabyle](resources/LogoKabyle-Sinfondo-palabraKabYle.png)--->

<img
  width="80"
  src="resources/LogoKabyle-Sinfondo-palabraKabYle.png"
  alt="Alt text"
  title="Kabyle SAS"
  style="display: inline-block; margin: 0 auto; max-width: 300px"
  align=right>
<img
  width="120"
  src="resources/Logo1-paska-CHCH.jpg"
  alt="Alt text"
  title="Paska by Kabyle"
  style="display: inline-block; margin: 0 auto; max-width: 300px"
  align=left>
  
<!---![Logo1-paska-CHCH](https://user-images.githubusercontent.com/111294790/187100277-dbd68fe2-9f6e-4175-b8bc-5bff73e4aed4.jpg)--->
# PASKA by Kabyle
## Funcionalidad de alertas

Esta funcionalidad brinda información en tiempo real sobre los diferentes procesos que gestiona el sistema, permitiendo optimizar los tiempos de gestión y minimizar los tiempos de corrección de errores.  \
\
Las alertas se generan por una acción o inacción de alguno de los operadores, así como también en forma automática en función de determinados procesos que el sistema controla permanentemente generando información sobre el estado de los mismos, muchas de ellas en función de las configuraciones personalizadas que se hicieron.  \
\
Se dividen en dos tipos:  
* Alertas Informativas  
* Alertas Operativas  
\
Una misma alerta puede tener ambas características en función de sus destinatarios, pero solo una característica específica para cada destinatario.  \

### Alertas Informativas 
El objetivo de estas alertas es mantener informado al usuario, en tiempo real, sobre los distintos eventos que hacen a su rol en la gestión de obra.  \
Son archivables, no se pueden borrar, se pueden cerrar implicando que se dió por enterado y generan un registro histórico de toda la obra, que se visualiza en el correspondiente informe de cada módulo.  

### Alertas Operativas  
El objetivo de estas alertas es mantener informado al usuario receptor, en tiempo real, que es necesaria su intervención en determinado proceso de la cadena de gestión de la obra. Estas alertas no pueden cerrarse hasta tanto no esté resuelto el evento al que fue convocado a través del alerta.   \
Generan un registro histórico de toda la obra, que se visualiza en el correspondiente informe de cada módulo.  

### Funcionamiento  
Ambas alertas se anuncian en simultáneo a través del ícono **NOTA: (poner el icono una vez definido)** que aparece en el ángulo superior derecho de la pantalla del usuario, como se muestra en la siguiente imagen.  \
**NOTA: (Poner imagen de pantalla)**
En el icono se indican la cantidad de alertas informativas y operativas que el usuario tiene activas.  \
**NOTA: (Insertar imagen agrandada del icono de alerta con descripción de cada elemento)**  \
\
Al tocar sobre el ícono de pantalla se despliega en cascada las distintas alertas activas al momento.  \
Ordenadas por fecha de emisión de las mismas independientemente si es operativa o informativa.  \
Se diferencian por el color del fondo, amarillo para las informativas y rojo para las operativas.  \
**NOTA: (Poner imagen con indicaciones)**  \
\
Seleccionando cualquiera de las ventanas en cascada, la misma pasa al frente y puede gestionarse.  \
**NOTA: (Poner imagen)**  \
Presionando el ángulo superior derecho de la ventana activa se cierran todas   \
**NOTA: (poner imagen)**  \
Si hay alertas por gestionar el ícono que indica alertas activas se mantiene en el ángulo superior derecho de la pantalla **NOTA: (imagen)**, en caso que no existan alertas activas el icono desaparece.  

#### Alertas Informativas  
Aporta la siguiente información : **NOTA: (imagen con indicaciones)**  
* Número de alerta, el dígito de la izquierda indica el módulo a que corresponde, los dígitos de la derecha el número específico de alerta dentro del módulo 
* Nombre del alerta, según corresponda 
* Fecha, indica la fecha de emisión del alerta y establece el criterio con que se muestran, por orden de emisión. 
* Tipo del alerta según corresponda, Informativa  
* Cuadro de validación, al tocar sobre el mismo las alertas informativas se archivan y desaparecen. 
* Datos del alerta, aporta información adicional sobre el alerta en función de la misma 
* Nombre de la obra, indica el nombre de la obra a la que pertenece el alerta.  

#### Alertas Operativas  
Aporta la siguiente información : **NOTA: (imagen con indicaciones)** 
* Numero de alerta, el dígito de la izquierda indica el módulo a que corresponde, los dígitos de la derecha el número específico de alerta dentro del módulo
* Nombre del alerta, según corresponda
* Fecha, indica la fecha de emisión del alerta y establece el criterio con que se muestran, por orden de emisión.
* Tipo del alerta según corresponda, Operativa
* Cuadro de validación, al tocar sobre el mismo las alertas operativas re direccionan al formulario donde es requerida la acción, solo se archivan y desaparecen una vez resuelta la acción solicitada.
* Datos del alerta, aporta información adicional sobre el alerta en función de la misma
* Nombre de la obra, indica en nombre de la obra a la que pertenece el alerta.  
  
#### Cuadro de Alertas del sistema  
**NOTA: Una vez terminado el diseño incorporar planilla con las alertas por modulo**
##### [Siguiente](./4-AreasYPerfiles.md) 
##### [Anterior](./2-IndiceDeModulos.md)
##### [Indice de contenido](./0-IndicePpal.md) 

##### [Inicio](./README.md)  

<!---#### [Contacto](./Contacto.md)--->
 
