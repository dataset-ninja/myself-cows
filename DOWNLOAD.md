Please visit dataset [homepage](https://universe.roboflow.com/dataset-pmr66/myself-cow) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Myself Cows', dst_path='~/dtools/datasets/Myself Cows.tar')
```
