# ¿Footer?

Para poner el footer ha sido necesario cambiar el tema del proyecto, además de añadir las siguientes líneas indicando:

* Icono (lirbería de fontsawesome)
* Link al que acceder cuando se haga click
* Nombre del tag cuando el cursor haga hover

### mkdocs.yml:
```
# Tema
theme:
  name: material
  favicon: img/favicon.png

# Footer
extra:
  social:
    - icon: fontawesome/brands/instagram
      link: https://www.instagram.com/
      name: Instagram
    - icon: fontawesome/brands/github
      link: https://github.com/PabloGomezB/pelis
      name: GitHub
    - icon: fontawesome/brands/twitter
      link: https://twitter.com/
      name: Twitter
    - icon: fontawesome/brands/docker
      link: https://www.docker.com/
      name: Docker
    - icon: fontawesome/brands/linkedin
      link: https://www.linkedin.com/
      name: Linkedin

# Copyrigth
copyright: Copyright &copy; 2020 - 2020 Pablo Gomez
```

# HOLA