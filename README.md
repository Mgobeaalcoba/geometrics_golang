## Geometrics golang

### Pasos para la instalación: 

_Si aún no tienes un archivo go.mod en tu proyecto golang entonces pon:_

```
$ go mod init paquetes
```

_Una vez con el archivo go.mod creado entonces debes proceder a importar este modulo de la siguiente forma:_

```
$ go get github.com/Mgobeaalcoba/geometrics_golang
```

_Este ultimo comando debió haber editado tu archivo go.mod y haber creado un archivo go.sum con un summary de modulos descargados_

_Verificado lo anterior ya puedes importar este modulo en tu archivo main.go, debajo de la mención del package, de la siguiente forma:_

```
import (
    "github.com/Mgobeaalcoba/geometrics_golang"
)
```

___Listo! ya puedes crear circulos y cuadradas, y calcular sus areas y perimetros de forma directa o desde las interfaces creadas para tales fines. Que lo disfruten!!!___

### Developer: Mgobeaalcoba <gobeamariano@gmail.com>