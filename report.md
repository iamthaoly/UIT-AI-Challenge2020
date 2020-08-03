		
# NVIDIA AI CITY CHALLENGE REPORT
***For UIT AI Challenge Bootcamp 2020***

Rank 1: Everest
- Detecting: Faster R-CNN, Resnet50 with FPN as backbone network, use pretrained model on COCO
- Tracking: DeepSORT (online tracking) + Mahalanobis distance smoothness method
- Counting: Typical trajectories selection + shape-based movement assignment

Rank 2: CSAI
- Detecting: Faster R-CNN, use pretrained model on COCO
- Tracking: Tracktor

Rank 3: 
- Detecting: RetinaNet, not pretrained
- Tracking: DeepSORT

Rank 4: ENGIE
- Detecting: Faster R-CNN, Resnet 50 with FPN, use pretrained model on COCO

Rank 5: Carnegie Mellon University
- Detecting: Mask R-CNN, use pretrained model on COCO
- Tracking: JDE

Rank 6: HCMUS
- Detecting: CenterNet
- Tracking: IOU Tracker

## Conclusion
There is a tendency of using Faster-RCNN of the top teams in object detection stage, but the result is not easily predictable because it also depends on the last two stages.
