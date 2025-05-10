# License-Plate-Detector-with-YOLOv9-and-Mask-R-CNN
Both YOLOv9 and Mask R-CNN were used in order to be compared in License Plate Detection

Dataset used : https://universe.roboflow.com/denny-pmzkg/plat-nomor-kendaraan-wxalb (568 images of Indonesian License Plates)
<br/>
<br/>
-API key in PyNotebook is probably outdated since i changed the roboflow project 
<br/>
-Also you might want to change file names accordingly

# Summary
Both Models are trained using the dataset with 70% of them (398 images) used as training dataset, 20% (114 images) as validation dataset, and the rest 10% (56 images) as test dataset.
Models can also be used on a single image/video and using EasyOCR to detect characters found in the license plate.

# Demo Images
YOLOv9
<br/>
<img src="https://raw.githubusercontent.com/DennyPrayogaSetiawanHalim/License-Plate-Detector-with-YOLOv9-and-Mask-R-CNN/refs/heads/main/yolov9-images/pred10.jpg" width="400" height="400">
<br/>
<br/>
MaskR-CNN
<br/>
<img src="https://raw.githubusercontent.com/DennyPrayogaSetiawanHalim/License-Plate-Detector-with-YOLOv9-and-Mask-R-CNN/refs/heads/main/mask-rcnn-images/pred1.jpg" width="400" height="400">
