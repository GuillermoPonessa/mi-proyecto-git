## Mi primer proyecto en git

## Mis objetivos de aprendizaje

- Aprender a configurar la computadora para trabajar con un repositorio de Git.
- Inicializar un repositorio local con `git init`.
- Configurar el usuario y el correo electrónico que Git utilizará en los commits:

	```bash
	git config --global user.name "Mi nombre"
	git config --global user.email "mi-correo@ejemplo.com"
	```

- Conocer los comandos básicos que utilizamos para revisar el estado del proyecto y guardar los cambios:

	```bash
	git status
	git add README.MD
	git commit -m "Primer commit"
	git log
	```

- Realizar el primer commit del repositorio. En ese momento, el archivo `README.MD` solo contenía el título **Mi primer proyecto en git**.
