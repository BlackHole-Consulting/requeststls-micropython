# requeststls-micropython
A TLS  request library for micropython . HTTP , TLS, Opensearch


## Usage

### Make a POST request

```Python

import requests

requests.post("block.blackhole.consulting",8888,"\ncontent-type: application/json",'{"signatures": ["'+r+'","'+v+'"],"compression": true,"packed_context_free_data": "'+memo+'","packed_trx": '+json.dumps(trx)+'}')


```
