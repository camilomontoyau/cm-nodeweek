# taller serverless node-week

# https://github.com/camilomontoyau/cm-nodeweek

## paso0: tener nodejs instalado

## paso1:

```
npm install -g serverless
```

## paso2:

```serveless```

y escribir n, simplemente es para verificar que serverless haya sido creado

## paso 3

```serverless config credentials -o --provider aws --key xxxxxxxxxxx --secret xxxxxxxxxxxxxxxxxxxxxxxx```

## paso 3.1

```cat ~/.aws/credentials```
Para verificar la creación de las credenciales de aws

## paso 4

```serverless create --template aws-nodejs --name cm-nodeweek --path cm-nodeweek```
