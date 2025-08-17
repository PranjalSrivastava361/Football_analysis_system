# Football_analysis_system
A computer vision project for football analytics – detecting and tracking players, referees, and the ball using YOLO, clustering teams by jersey colors, measuring ball possession, compensating camera motion with optical flow, applying perspective transformation for real-world measurements, and calculating player speed &amp; distance covered.

## Modules Used

The following modules are used in this project:

- **YOLO**: AI object detection model  
- **KMeans**: Pixel segmentation and clustering to detect t-shirt color  
- **Optical Flow**: Measure camera movement  
- **Perspective Transformation**: Represent scene depth and perspective  
- **Speed & Distance Calculation**: Estimate speed and distance per player  

---

## Trained Models

- [Trained YOLOv5](https://github.com/ultralytics/yolov5)  

---

## Sample Video

- [Sample Input Video]([Sample Input Video](https://drive.google.com/file/d/1TBGUeNA5QaGW5bWzzxo3WvjXElYML4y6/view?usp=sharing)
)
## Requirements  

To run this project, you need to have the following dependencies installed:  

- Python 3.x  
- ultralytics  
- supervision  
- OpenCV  
- NumPy  
- Matplotlib  
- Pandas  

You can install them using:  

```bash
pip install -r requirements.txt


