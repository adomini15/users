# users
# Tarea VI - Aplicación ionic-react de usuarios con sqlite
### Configuración
###### NOTE: Los siguientes pasos se hacen tomando en cuenta las versiones de las herramientas y modos de ejecutar utilizados. 
- Gradle 7.3
- JDK 11
- Node 16
###### Si utilizara otros mecanismos podria saltar de los pasos debajo.

Instalar dependencias:
```sh
npm install
```

Generar build de la aplicación:

```sh
ionic build
```

Generar archivos de gradle (importante: antes del paso que le sigue):

```sh
gradle init
```

Generar aplicación nativa:

```sh
ionic cap add android
```
```sh
ionic cap add ios
```

Ejecutar aplicación nativa desde CLI y dispositivo físico:

```sh
ionic cap run android 
```

```sh
ionic cap run ios 
```
