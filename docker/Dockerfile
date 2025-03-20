FROM cartagodocker/angular:v1.0.1

USER root

ARG PROJECT_FOLDER

# Configuración de inicio del contenedor
WORKDIR ${PROJECT_FOLDER}
# Realizamos la entrada al contenedor con el shell zsh
ENTRYPOINT ["zsh", "-ic"]
CMD ["tail -f /dev/null"]
