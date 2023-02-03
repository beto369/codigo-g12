# Primer día con Git y GitHub

Lista de comando de Git

* Para poder la version de Git ejecutamos en nuestra terminal:

```bash
git --version
git -v
```
* Para configurar el correo y nombre (sólo la primera vez)



```bash
git config --global user.email "mi correo@gmail.com"
git config --global user.name "mi nombre"
```

* Para ver la configuración de Git
```bash
git config --list
```

* Para inicializar nuestro repositorio en Git utilizamos el comando:
```bash
git init
```

* Para ver el estado de nuestro cambios:
```bash
git status
```

* Para preparar nuestros archivos para la zona de stage (prepararlos para commit):
```bash
git add .
git add nombreDelArchivos.extension
```


