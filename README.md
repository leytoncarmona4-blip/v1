# comandos
``git --version``
``node -v``
``npm -v``
## Inicializar un proyecto
``npm init -y``


## manejo de git
``git init``
``git add .``
``git commit -m "v1"`

``git branch -M master``

``git remote add origin https://github.com/leytoncarmona4-blip/v1.git``

``git push -u origin master``

# 📁Estructura profesionales de una API en NODE.js
api-node
  |-src **Aqui vive todo el codigo real del proyecto**
        |-config **Configuraciones globales**
        |-controllers **controla las peticiones HTTP**
        |-middlewares **Intermediarios de seguridad y validación**
        |-routes **Define las URLs de la API**
        |-services **Logica del negocio**
        |-utils **funciones reutilizables**
        |-models **Representa las tablas de la base de datos**
        |-app.js **configuración de la aplicación**
        |-server.js **Punto de arranque**
