# LAFtrack

## Code introduction and use(The tracking part of the code, LAF_track.py, will be provided after the paper is accepted.
)

### Code
Please download YOLOX weight and reid network weight before use.
The ownership weight is in  (https://pan.baidu.com/s/1H3LH7k2XLLcWiIRxks0DCg?pwd=ly83)

The yolox folder contains the relevant code under YOLOX target tracking, 
the exp file under yolox is the model related configuration, the weights
under yolox need to be placed in the relevant weight file, and the dataset
folder under yolox needs to be placed in the picture sequence or video to
be detected and tracked


# use
This code can be run once through the main.py file. The parameter configuration
of this code is defined in main.py and can be modified by yourself.

## result
### Results on MOT challenge test set
| Dataset    |  MOTA | IDF1 | HOTA | FP | FN | IDs | matching speed (FPS) |
|------------|-------|------|------|------|------|------|------|
|MOT17       | 79.9 | 76.3 | 63.6 | 32628 | 79086 | 2394 | 78.1 |
|MOT20       | 73.6 | 69.4 | 58.1 | 24087 | 110916 | 3193 | 26.1 |








