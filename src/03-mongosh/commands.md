## Connect to container

'''sh
docker-compose exec mongodb bash
'''

## Connect with mongsh

'''sh
mongosh "mongodb://root:root123@192.168.111.134:27017/?authMechanism=DEFAULT&tls=false" 

mongosh "mongodb+srv://administrator:Jrql8AXIpSxsgDTa@mongodb101.oxo9csf.mongodb.net/"
'''

'''sh
show dbs
show collections
'''

'''sh
use("platzi_store")
db.products.find()
'''
