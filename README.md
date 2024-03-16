# layoutHOI
![layout gennerated images for HOI](/pipline01.png)
layout generate（GLIGEN）
```
python ./layoutHOI/layout-generation-models/GLIGEN-master/image_scprits/generate_multi.py
```
images check（SOV-STG）
```
python ./layoutHOI/image-check-models/SOV-STG/scripts/SOV_multi.py
```
images check（groundingDINO）
```
python ./layoutHOI/image-check-models/GroundingDINO/scripts/DINO_multi.py
```
