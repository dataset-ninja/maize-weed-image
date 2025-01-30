Dataset **Maize-Weed Image** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI5MDJfTWFpemUtV2VlZCBJbWFnZS9tYWl6ZS13ZWVkLWltYWdlLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIk5MQzlNTmxwVmtmZ0xEb2UxWlp5Mm80SU5tTU5aZld5YmlqTFE2MGF4T0E9In0=)

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