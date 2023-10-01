# HIFI-GAN


## 스크립트
```bash

ln -s /mnt/g/dataset/vvc/SINGER_01 singer

ls singer/*.wav > train_file.txt

tail train_file.txt

python preprocess.py train_file.txt -o preprocess
```