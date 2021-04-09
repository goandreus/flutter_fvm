# fvmtest

Configuracion inicial FVM

## Instalar Dart

```
 brew tap dart-lang/dart

 brew install dart

```

## Iniciamos FVM

```
 pub global activate fvm

```

## Instalamos versiones del SDK

```
 fvm install <version>

 fvm install 1.22.6 (Ultimo soporte, la mayoria de proyectos la utiliza)

 fvm install 2.0.0  (No-null safety, aqui ya la mayoria de Widgets son deprecados)

 fvm install 2.0.3  (actual - null safety)

```

## Ver nuestra lista de versiones

```
 fvm list 

```

## Elegimos la version que deseemos usar

```
 fvm use <version>

 fvm use 1.22.6

 fvm use 2.0.0

```

## Configuracion para VS CODE

```
 En el apartado de "view" seleccionar "command palette" escribir y seleccionar "Open Setting(JSON)"
 

 Agregamos 
 
  "dart.flutterSdkPaths": [".fvm/flutter_sdk"]
 

```