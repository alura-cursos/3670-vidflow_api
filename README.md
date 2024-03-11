# Instruções

## Iniciando o banco de dados

O banco de dados é um arquivo chamado `db.json`. Ele precisa ser criado com a seguinte estrutura dentro da pasta **db**:

```json
{
  "users": [],
  "videos": []
}
```

## Rodando a API

É importante que você tenha em sua máquina NodeJS e NPM nas seguintes versões:

- NodeJS: v20.5.0
- NPM: 10.4.0

Depois instale os pacotes utilizando o seguinte comando:

```shell
npm install
```

> Aviso importante
>
> Pode ser que você precise rodar o comando acima como super usuário (sudo)

Depois basta rodar o comando:

```shell
json-server ./db/db.json -m node_modules/json-server-auth
```

## Pronto!

Agora a API deve estar rodando na porta **3000**!
