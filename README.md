# Proyecto

# Diagrama ETL
### + Extracción: Obtendremos información de nuestros sensores, en nuestro caso, nos servirán los sensores de distancia y luminosidad, al igual que obtendremos del stream de la cámara la cara del usuario que funcionará como llave de acceso.
### + Transformación: Al obtener los datos de la luminosidad, la distancia y el rostro del usuario, estos son transformados en una señal, esta señal activara un LED de color verde si cumplen con los requisitos necesarios, permitiendole el acceso al usuario, si no, activará un LED rojo, dando a entender que nego el acceso.

### + Load (carga): Esta señal lo que hace es permitir o negar el acceso del usuario, abriendo o manteniendo cerrada la cerradura de la puerta, al igual que el dato de la luminosidad es enviada a una API en la cual se graficara para que el administrador de la página pueda llevar un control de ello, al igual que el usuario es guardado en la base de datos.

![image](https://user-images.githubusercontent.com/78035963/111945695-c1c0c000-8a9f-11eb-891e-24eda9f325de.png)

