# video-transformer-pytorch
Using pytorch to implement video transformer according to https://keras.io/examples/vision/video_transformers/ which uses keras to implement video transformer

## Data preparation
### Video data collection
```bash
!wget -q https://git.io/JGc31 -O ucf101_top5.tar.gz
!tar xf ucf101_top5.tar.gz
```

### Annotation collection
train data and respective labels, validation data and respective labels, test data and respective labels can be collected from this link: https://drive.google.com/drive/folders/1HV7XaFN9YYcDn1kBwFusGHQo_0fVXZLP?usp=sharing
