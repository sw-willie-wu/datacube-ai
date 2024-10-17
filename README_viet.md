# DataCube AI Demo

Dịch sang các ngôn ngữ khác: [English](README.md)

## 1. Thiết lập môi trường

### 1.1 Cài đặt Python

- Hệ điều hành: Windows 11
- Tải xuống [Python 3.12 (x64)](https://www.python.org/ftp/python/3.12.7/python-3.12.7-amd64.exe) hoặc nhận [other version](https://www.python.org/downloads/).
- Mở tệp exe và cài đặt nó.
![Install Python](docs/pic/install_python.png)

### 1.2 Tạo python venv

```bash
>> python -m venv .venv
>> .venv/Scripts/activate
```

### 1.3 Cài đặt gói

- Qua tệp requirements.txt

```bash
>> pip install -r requirements.txt
```

- Cài đặt trực tiếp qua pip

```bash
>> pip install jupyter matplotlib scikit-learn geopandas rasterio lightgbm
```

## 2. Tải dữ liệu

- Tải xuống [Demo Data](https://thinktronltdcorp-my.sharepoint.com/:f:/g/personal/willie_wu_thinktronltd_com/ErtvtU-mdBRPhKH9fM4D-W4BEv7xU7iZajrWC3bT-n7X6w?e=P9iNiq).
- Đặt dữ liệu vào thư mục data, cấu trúc thư mục của bạn sẽ trông như sau:

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

## 3. Bắt đầu

```bash
>> jupyter notebook
```

Bạn sẽ thấy notebook hiển thị như sau:

![Start Jupyter](docs/pic/start_jupyter.png)

- [Hướng dẫn 1 - Hiển thị Dữ liệu](./Tutorial1_Data_Visualize.ipynb)
- [Hướng dẫn 2 - Máy học](./Tutorial2_Machine_Learning.ipynb)
