# DataCube AI Demo

## 1. Setup Envrionment

### 1.1 Install Python

- Operate Ststem: Windows 11
- Download [Python 3.12 (x64)](https://www.python.org/ftp/python/3.12.7/python-3.12.7-amd64.exe) or get [other version](https://www.python.org/downloads/).
- Open exe file and install it.
![Install Python](docs/pic/install_python.png)

- Create python venv

    ```bash
    >> python -m venv .
    >> ./Scripts/activate
    >> pip install -r requirements.txt
    ```

### 1.2 Download Data

- Download [Demo Data](https://thinktronltdcorp-my.sharepoint.com/:f:/g/personal/willie_wu_thinktronltd_com/ErtvtU-mdBRPhKH9fM4D-W4BEv7xU7iZajrWC3bT-n7X6w?e=P9iNiq).
- Put data into data folder, your folder should be look like:

```tree
datacube-ai-demo
├─data
│  ├─sentinel-2
|  |    └─XXX.zip
│  ├─shapefile
|  |    └─label.shp
│  └─weights
|       └─model.txt
...
```

## 2. Start

[Tutorial1 - Data Visualize](./Tutorial1_Data_Visualize.ipynb)
[Tutorial2 - Machine Learning](./Tutorial2_Machine_Learning.ipynb)
