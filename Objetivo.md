# Criar uma API com GraphQL

# Ter auth

    ** Duplo fator com email

# Ter autorização -> Algumas rotas protegidas

    ** Vou ter users
    ** Vou ter contatos
    ** Um user só pode ter acesso aos seus contatos

Schema User
id: uuid
email: string
passwordHash: string
isVerified: boolean

isVerified é alterado quando o usuário realiza a autentificação de 2 fatores
