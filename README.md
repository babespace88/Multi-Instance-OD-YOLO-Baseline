# Multi-Instance-OD-YOLO-Baseline


---> A Multi-Instance OD YOLO Baseline is a basic object detection system using the YOLO model, set up to find and label multiple objects of the same kind in an image.


Dataset link ---> https://www.kaggle.com/competitions/multi-instance-object-detection-challenge

-------------------------------------------------------------------------------------------------------------------------------


Why using .yaml data format?


---> Using data.yml keeps your data organized and tells YOLO exactly what you want it to do for multi-instance detection tasks.



------------------------------------------------------------------------------------------------------------------------------


Why model used metric map50?


---> mAP50 tells you, out of all the objects the model tries to detect, how many are “good enough”—where “good enough” means the model’s box overlaps at least halfway with the correct box. It’s a quick, common way to measure if your Multi-Instance OD YOLO model is working as expected . A mAP50 score over 0.9 (or 90%) is generally considered a very good result for object detection tasks, including those using the YOLO model.



--------------------------------------------------------------------------------------------------------------------------------
