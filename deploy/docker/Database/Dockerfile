FROM mongo:3.4
COPY drop/* usr/local/data/db/
#es como Entrypoint, pero CMD se puede sobreescribir con otro comando alejecutar el contenedor
CMD ["mongod", "--smallfiles", "--rest"]
