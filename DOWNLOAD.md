Dataset **Maize-Weed Image** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/D/I/EL/OsSk2zEimoqZ0GCy1jEzX1rv92iB28zq9ZqenZPQ1sOhqlc0bQRc7UIs5MFU3q4qtkQ5spyI1tZNiMh7ajIp5Elj1N9ny8UdvXQtItczcQZ4GYxXB0RbZkTa237H.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Maize-Weed Image', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://data.mendeley.com/datasets/jjbfcckrsp/2).