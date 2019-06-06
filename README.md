![alt text]( https://www.captivateonhold.com/wp-content/uploads/2016/03/BroadWorks.jpg "Broadsoft")

[![PyPI pyversions](https://img.shields.io/pypi/status/BroadworksOCIP.svg)](https://pypi.org/project/BroadworksOCIP/)
[![PyPI version shields.io](https://img.shields.io/pypi/v/BroadworksOCIP.svg)](https://pypi.python.org/pypi/BroadworksOCIP/)
[![PyPI license](https://img.shields.io/pypi/l/BroadworksOCIP.svg)](https://pypi.python.org/pypi/BroadworksOCIP/)
#  Broadworks OCI-P (Open Client Interface Provisioning) Client


Broadworks Version: 20sp1

## Installing

```bash

pip install BroadworksOCIP

```
## How to Use

```python
from BroadworksOCIP import Client
from BroadworksOCIP.broadworks.schema.request.system import SystemRoutingGetRequest

client = Client(username="user@broadsoft.com", password="supersecret", address="https://api.broadsoft.com/webservice/services/ProvisioningService")

client.login() 

response = client.send(SystemRoutingGetRequest())

response.is_route_round_robin()

```


 



