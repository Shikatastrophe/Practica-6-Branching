Shika Moriyama Angeles Castillo

## Lenguajes Interpretados 

Jonathan Mircha

Materia la cual nos está enseñando GitHub y el uso de repositorios.

## Principios de Composición Y Diseño

Roberto Melo

Materia en la cual estamos viendo los inicios de composición visual y su implementación funcional 

## Sistemas Operativos

Osiel Morales

Materia donde vemos ciberseguridad y el uso y mantenimiento de sistemas operativos

## Proyecto de App

Sebastian Mejia

Materia donde andamos diseñando una aplicación movil.

## Diseño de Videojuegos

Hector Guerrero

Materia donde andamos haciendo un jueguito cada semana


## Esta es la versión 1.0.0 de este repositorio

# Practica 2

¿Cómo se inicializa un repositorio en Git?

Primero, tenemos que, en la terminal, escribir 

```bash
git init
```

Generalmente hablando, lo que tambien deberiamos poner son el usuario y el correo, adentro del repositorio

```bash
git config --local user.name "USERNAME"
git config --local user.email email@email.com

```

¿Cómo creas un repositorio en GitHub?

Primero, vas a la página de github, y en tu cuenta le das en crear repositorio, despues le pones un nombre y lo ajustas a las necesidades de el repositorio 

¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

```bash
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin master
git push

```

¿Cuál es el flujo básico de trabajo en Git y GitHub?

Primero, guardas, luego, agregas, luego commiteas, y luego pusheas

```bash
git add .
git commit -m 
git push
```