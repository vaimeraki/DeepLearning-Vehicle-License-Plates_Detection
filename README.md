# Vehicle License Plate Detection (YOLO11)

Detects vehicle license plates in images with a YOLOv8n model fine-tuned on European plates (DSTI Deep Learning project).

**Dataset:** [N] images of European license plates (`eu.zip`), labels converted to YOLO format with `convert_labels.py` and split into train/val/test with `split_data.py`.

**Run:** `pip install -r requirements.txt` → `python split_data.py` → `python train_yolo.py`

**Result:** mAP@0.5 = [X] on the validation set after [E] epochs; example detection in `output_annotated_image.jpg`.

● Project reproducibility (requirements file with necessary packages, README file for
running the project, environment, model code) [1 point]

● Project hosting and deployment (Github, Docker, AWS, Hugging Face Hub or any
other method) [1 point]
