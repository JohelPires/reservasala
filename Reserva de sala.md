# Reserva de sala

- Registrar
- Login (usuario, admin)
	- admin pode fazer o crud completo de salas
	- admin e usuario podem fazer o crud de reservas
	
- apos reserva, usuário recebe email com regras de utilização do espaço.


# Modelo Lógico

Tabela Usuario
- id
- nome
- cpf (login)
- email
- telefone
- endereço
- senha
- admin (boolean)

Tabela Sala
- id
- nome
- localidade
- n_lugares
- equipamentos [tabela a parte]

Tabela Reserva
- id
- id_usuario fk
- id_sala fk
- data
- hora
- duracao


# Fluxo da aplicação

fazer reserva

## Victor
- protótipo baixa resolução
- paletta de cores
- tipografia

## Samuel
- crud da reserva

## Johel
- iniciar o projeto no github
- login / registrar
