# Object-Detection

<img src="banner.png" align="middle" width="3000"/>

Hello! Here is my personal submission for an object detection task for Brainhack's [Today-I-Learn](https://www.dsta.gov.sg/brainhack) hackathon.

My implementation makes use of Faster R-CNN model with a ResNet50-FPN backbone. To understand the underlying code structure, you can read this [article](https://zhuanlan.zhihu.com/p/145842317) by translating to English.

Through robust augmentations and hyperparameter tuning, I was able to achieve a mean Average Precision of 58% on unseen photos.

# Use my implementation

### Downloading my Source Code
- Visit the [repository](https://github.com/raythx98/Object-Detection)
- Click on `Objection Detection.ipynb`
- Click on the download button
- 
### Upload the Jupyter Notebook
- Upload the Jupyter Notebook to your google drive
- Note: `/content/drive/MyDrive` is your google drive home directory
- Open the Jupyter Notebook
- Change your runtime by following these steps
    1. Click on `runtime`
    2. Click on `change runtime type`
    3. Change hardware accelerator to `GPU`

### Configure the Notebook
- Open the Jupyter Notebook
- Under `Importing dataset from Google Drive`, change `base_folder` to your desired path
- rename the zip file for `training_path` and `testing_path`, more on creating your dataset [below](#creating-your-datasets)

### Creating your datasets

Your datasets `training_dataset.zip` and `test_dataset.zip` should follow the following format:

```
training_dataset.zip
    training_dataset/
        images/
            00001.jpg
            00002.jpg
            00003.jpg
            ...
        train.json
        val.json
  
test_dataset.zip  
    test_dataset/
        images/
            00001.jpg
            00002.jpg
            00003.jpg
            ...
        test.json
```

`train.json`, `val.json` and `test.json` should follow the following format:

```

```

### Final Steps

1. Save the changes you have made till now

2. Upload `training_dataset.zip` and `test_dataset.zip` into `base_folder`

3. Click on `Runtime` then `Run All`
