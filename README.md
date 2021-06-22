

## Custom Detectron which references original Detectron2 
### Changes made by Johan


Losses:
	IOU based losses : (with bounding boxes not with delta values as done in original code)
		DIOU : Done
		CIOU : Done
		
Evaluation
	1. Results as a dataframe for easier evaluation of bbox predictions : Done
	2. Saving coco prediction results in separate files for evaluation later : in progress

Reference for IOU losses which were used to construcut D2 version of it.
MMDET: https://github.com/open-mmlab/mmdetection/blob/master/mmdet/models/losses/iou_loss.py
GIOU Fvcore: https://github.com/facebookresearch/fvcore/blob/master/fvcore/nn/giou_loss.py


