# Face landmark 
Fine turing model to marking only eyes and eyebrows
## Requirements:
```angular2html
pip install -r requirements.txt
```

## Repair dataset
- repair landmark points in parse_xml.py
- repair all dataset
```angular2html
python parse_xml.py
```
## Training and evaluation

```angular2html
python train_shape_predictor.py --training ibug_300W_large_face_landmark_dataset/labels_ibug_300W_train_eyes.xml --model eye_predictor.dat
```

## Using with your webcam
```angular2html
python predict_eyes.py --shape-predictor is_your_weith_path
```
