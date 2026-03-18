🧱 Estilo arquitetural
Monólito modular

Separação por domínio

Preparado para futura migração para microserviços

🧠 Domínios
Auth

User

Car

Booking

Payment

Review

🔗 Comunicação
interna via código (service → service)

externa via REST API

🗄️ Banco
PostgreSQL (principal)

Redis (cache / sessão)

🔐 Segurança
JWT

Senhas com hash (bcrypt)

Validação de entrada