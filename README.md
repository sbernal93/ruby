# ruby
## Configuracion BD:

### Conectar con usuario postgres a la base de datos:
	`sudo su - postgres`
	`psql`

### Crear base de datos y usuario:

	`create database serviamigos;`
	`create user servdev with password 'serviamigos123';`
	`grant all privileges on database serviamigos to servdev;`
	
