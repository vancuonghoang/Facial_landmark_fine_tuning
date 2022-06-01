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
python train_shape_predictor.py
```
