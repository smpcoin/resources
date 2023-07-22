## resources


Mining APP https://ipfs.io/ipfs/QmQgobxe8pYV7Fi8u9h5JFnhyod51sXMZmQ58byaSaQ3F6?filename=smp.zip

## API 

# Display balance  

GET  http://localhost:1005/chequebook/balance

responses:{"totalBalance":101200000000000000000,"miningBalance":100000000000000000000}

# withdraw

POST http://localhost:1005/chequebook/withdraw

parameters： amount = 1 

responses: "transactionHash": "0x5b101b8624b302f5aa8f0b14a230245e970e80afd336d2a025c991de62790be5"
