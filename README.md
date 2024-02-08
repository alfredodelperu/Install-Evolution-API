# Install-Evolution-API


#instalar nginx

#configurar el proxy

#generar certificado

#instalar mongodb y crear usuario y contraseña para admin

db.createUser({ user: "admin", pwd: "evapimongo", roles: [{ role: "userAdminAnyDatabase", db: "admin" }, "readWriteAnyDatabase"]});

#instalar evolution api segun pagina https://doc.evolution-api.com/docs/01-Get%20Started/Installation/nvm-installation

#editar archivo env.yml para configurar evolution-api

#ejecutar el servidor  

npm run start:prod
