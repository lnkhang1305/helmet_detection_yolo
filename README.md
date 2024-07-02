# Helmet Dectection 
This project is using YOLOv10 to detect helmet in image. In this repo, you can train or test the model trained with COCO dataset.
## Test model
  Run this command in your bash:
   ```bash
   python test.py '<path to your image>'
   ```
  The result is in `result` file.
  Or you can test it with streamlit by runnning this command:
  ```bash
  streamlit run app.py
  ```
## Train model
  Run file train.py:
  ```bash
  python train.py
  ```
  The model is saved at yolov10/runs/detect/train/weights/best.pt
  
    
   
   
