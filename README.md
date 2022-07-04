# Hướng dẫn train Pytorch_Retinaface trên Google Colab
### Bước 1: Tạo thư mục chứa source và backup weights
Download tệp từ https://drive.google.com/drive/folders/1jdh3K7i2BKjv0NJHlWEWdbMzUrLEQvn-

Từ thư mục gốc Drive
* Tạo thư mục ML và upload tệp vừa tải từ link trên
* Tạo thư mục ML/backup (thư mục backup trong ML vừa tạo)
### Bước 2: Thiết lập
Truy cập https://colab.research.google.com/

Huỷ -> Trợ giúp -> Xem bằng tiếng anh -> New notebook

Liên kết Google Colab với Google Drive
```
from google.colab import drive
drive.mount('/content/drive')
```

Chọn tài khoản vừa upload tệp ở trên

```
%cd /content
!unzip /content/drive/'My Drive'/ML/Pytorch_Retinaface.zip
```



