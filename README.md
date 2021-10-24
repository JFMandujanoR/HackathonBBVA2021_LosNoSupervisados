# Hackathon BBVA 2021 Los No Supervisados
Repositorio para el código y la solución del reto Buscador de Datos financieros

El siguiente enlace sirve para acceder a la solución final. Esta consta de un dashboard donde se visualiza y despliega la información contenida en los PDFs financieros. Se pueden apreciar visualizaciones por tipo de tabla y concepto importante para el banco así como las tablas con informacion cruda disponibles para descargar. El servicio es interactivo y el usuario puede utilizar distintos filtros en las tablas y graficas.
 
Para acceder al dashboard [da click aquí](https://iibwefjsn5.execute-api.us-east-1.amazonaws.com/test/embed-sample).

Al acceder al URL anterior se solicitará un usuario y una contraseña, para ello usa:

- Usuario: *HackathonUser*
- Password: *TestPass-1*

Al ingresar por primera vez tendrás se solicitará cambiar la contraseña y esa sera tu clave de acceso a partir de ahora. Esto anterior se realiza con el fin de mantener la información analítica segura.

_Nota_: Cuando accedas al sistema tendrás que elegir el dashboard correcto llamado "Datos Financieros". Es posible que al elegirlo veas un mensaje sobre no poder conectarse, si ocurre esto por favor cambia de dashboard a "test1" o "test-1" e inmediatamente regresa a dashboard "Datos Financieros". Ya debes poder ver nuestro visualizador... disfruta!

La carpeta [códigos de homologación de datos](https://github.com/JFMandujanoR/HackathonBBVA2021_LosNoSupervisados/tree/main/c%C3%B3digos%20de%20homologaci%C3%B3n%20de%20datos) contiene el código en Python usado para el procesamiento y homologación de datos mediante procesamiento de lenguaje natural y similitud de texto. Mayor detalle dentro de la carpeta.

Diagrama de solucion:

![diagrama](https://github.com/JFMandujanoR/HackathonBBVA2021_LosNoSupervisados/blob/main/Diagrama.png)

Para descargar los conjuntos de datos finales usa los siguientes enlaces:

- Balance general: [da click aquí](https://datosfinancieroshackathon.s3.amazonaws.com/Balance_join_completo.csv)
- Coeficientes de cobertura: [da click aquí](https://datosfinancieroshackathon.s3.amazonaws.com/Coeficientes_Cobertura_join_completo.csv)
- Cuentas de orden: [da click aquí](https://datosfinancieroshackathon.s3.amazonaws.com/Cuentas_de_Orden_join_completo.csv)
- Estado de resultados: [da click aquí](https://datosfinancieroshackathon.s3.amazonaws.com/Edo_Resultados_join_completo.csv)
- Estado de flujo: [da click aquí](https://datosfinancieroshackathon.s3.amazonaws.com/Estado_de_flujo_join_completo.csv)

De igual manera estos archivos se pueden descargar desde el dashboard.

________________________________________________________
Los No Supervisados
