# Human Activity Recognition

We tried to implement the following pre-processing techniques to extract person from each frame of video:
* Interactive Foreground Extraction using GrabCut Algorithm
* Background Subtraction
* Mask RCNN

## Structure of the project:
* The datasets are expected to be in the structure as shown.
* The models will be with their respective names.
```
projectbu
|
|-- dataset
|   |-- UCF101
|   |-- HMDB51
|
|-- dependencies
|   |-- Mask_RCNN
|
|-- scripts
|
|-- ALSTM
|   |-- autoencoders.py
|   |-- main_ae.py 
```
* To extract the frames, run the command below:
```
bash scripts/frames.sh     # To extract just the frames
bash scripts/framesbr.sh   # To extract frames with Background Reduction
```
