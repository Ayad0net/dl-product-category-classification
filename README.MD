# Deep Learning Model for Product Category `Classification`
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

> 💡 Note: the original repo is: 🔗 https://github.com/yang-zhang/product_category


## 📦 Installation 

### 1. clone the repo ... 
```
git clone https://github.com/Ayad0net/dl-product-category-classification.git
```

### 2. install packages ... 
Inside the repo directory ...
```
pip install -r requirements.txt --no-cache-dir
```

### 3. download pretrained model... 
Inside the repo directory ...
```
wget https://github.com/yang-zhang/product_category/releases/download/v0.0.1/transformer_20210307D3.ckpt -P data
```



## Example 
```
python3 predict.py -t "Lykmera Famous TikTok Leggings, High Waist Yoga Pants for Women, Booty Bubble Butt Lifting Workout Running Tights"
```

`output`
```
Sports & Outdoors: 0.997
Sports & Fitness: 0.994
Exercise & Fitness: 0.980
Clothing: 0.961
Yoga: 0.905
```
