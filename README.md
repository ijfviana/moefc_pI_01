moefc_pI_01
========

Transparencias correspondientes al tema de *Preparación del entorno de laboratorio* de la asignatura *Programación I* en el *Máster Oficial en Economía, Finanzas y Computación* de la Universidad de Huelva.

Instalación
===========

Para instalarlo en Ubuntu 14.04, se siguen los siguientes pasos:

* Instale [nodejs](https://nodejs.org/)

```
sudo apt-get install nodejs nodejs-legacy
```

* Instale [npm](https://www.npmjs.com/)

```
sudo apt-get install npm
```

* Instale [grunt](https://www.npmjs.com/package/grunt)

```
sudo npm install -g grunt-cli
```

* Instale [bower](http://bower.io/)

```
sudo npm install -g bower
```

* Clone el repositorio

```
git clone https://github.com/ijfviana/moefc_pI_01.git
```

* Accedemos al directorio `moefc_pI_01`

```
cd moefc_pI_01
```

* Instale las dependencias mediante [bower](http://bower.io/)

```
bower install
```

* Instale las dependencias del proyecto usando  [npm](https://www.npmjs.com/)
```
npm install
```

* Ejecute la presentación
```
grunt server
```
