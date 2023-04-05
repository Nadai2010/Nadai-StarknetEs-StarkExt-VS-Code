Primero clonarmos 

gh repo clone 7finney/starkex

descargamos el archivo y leugo en ezxtensxciones tres puntos e instalmos el archuvo

luego refrescamos y procedemos control pshift p para paleta coamdnos y buscamos satrkent new account

create starkne new acoount 

https://testnet.starkscan.co/contract/0x32759c445eec154d5808d3bfd332260065b51803d61acc46b6a5e8618972f6

enviar 0.02 de eth para que se deploy tu cuenta de starkex, si te da erro que te falta un numero revisar y añdir 0x0XXXXX al confirmase la transacion podremos ir a vs code selecionar undeployer acocount y selecionar la cuenta que queremos desplegar.

ahora usaremos el deploy anew aocunt y deberia de verse

foto

y luego podemos revisar el hash y ver que ahora se ha deployado

https://testnet.starkscan.co/tx/0x078240a59019727f2e8fa4edb03578ff45ab37cd93282e1382f02af2655a5d4f

Veremos que el saldo se ha consumido y se ha deployado un contrato de cuenta de OZ en la que podra revisar su implemetación

## Interactuar con Smart

Compilamos un contrato en CAiro 0, en este caso un ens.cairo

starknet-compile ens.cairo --output ens.json

ahiora le daremos activar extenciom lo que creará una carpete a`starkex` 

Luego selecionamos Networ en este caso goerli alpha

foto

Ahora selecionamos el select starkex acount que nos dará el token ETH

foto 

Ahora selecionaremos el contrato de CAiro que queremos utilzar

foto

iremos al archivo ens_address.json y añadimos el class hash

foto

Luego iremos a deesplegsar el contrato recordar guardar el archivo antes de despelgar.

ftoo

doto





