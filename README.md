# COCO Annotation to MOT17 for Custom MOT Dataset

## 1. Get MOT17 format annotations

For the first part, we need to create det/gt/img1 and seqinfo.ini for every video sequence.


## 2. Get COCO format annotations(train.json and val.json)

Given that ByteTrack and some Tracking methoding convert MOT17 format to COCO format, based on the `convert_mot17_to_coco.py`, we can convert MOT17 format to COCO format with some changes.

# Acknowledgement:
 Thanks [convert_mot17_coco.py](https://github.com/ifzhang/ByteTrack/blob/main/tools/convert_mot17_to_coco.py) from [ByteTrack](https://github.com/ifzhang/ByteTrack) and  [coco2mot](https://github.com/eplatero97/coco2mot) for the  help.