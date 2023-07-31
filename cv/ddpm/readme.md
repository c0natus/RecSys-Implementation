Stanford Cars dataset 활용.

[Dataset][1], [devkit][2], [pre-trained parameter][3]

``` bash
├── stanford_cars
│   ├── cars_test/~.jpg # remove recursive directory structure
│   ├── cars_train/~.jpg # remove recursive directory structure
│   ├── devkit
│   ├── cars_annos.mat
│   └── cars_test_annos_withlabels.mat
│  
├── ddpm.py
├── diffusion.ipynb
├── main.py
├── utils.py 
├── final.pt
└── README.md
```

[1]: https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset
[2]: https://github.com/pytorch/vision/files/11644847/car_devkit.tgz
[3]: https://drive.google.com/drive/folders/1gZ-iREm7b4e1RTKUnvIxoeJhwalv-9CH?usp=sharing