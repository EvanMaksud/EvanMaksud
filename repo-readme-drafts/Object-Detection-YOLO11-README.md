# Vehicle Detection with YOLO11

Training and evaluating YOLO11 models for vehicle detection on a custom YOLO-format dataset.

The project focuses on detecting common vehicle classes in real-world images, including ambulances, buses, cars, motorcycles, and trucks. The notebook explores dataset structure, visualizes samples, trains YOLO11 models, and reviews validation outputs such as learning curves and confusion matrices.

## What It Covers

- Loads a custom vehicle detection dataset in YOLO format.
- Inspects image and label files before training.
- Visualizes sample annotations and prototype detections.
- Trains a YOLO11 model from scratch.
- Runs a transfer-learning experiment with pretrained YOLO11 weights.
- Reviews training curves for box, classification, and distribution focal loss.
- Loads the best model weights and validates against the validation split.

## Stack

- Python
- Ultralytics YOLO11
- PyTorch and TorchVision
- OpenCV
- supervision
- pandas and NumPy
- Matplotlib and Seaborn
- Kaggle Notebook

## Dataset

The notebook expects a Kaggle dataset at:

```text
/kaggle/input/vehicledetection/VehiclesDetectionDataset
```

Expected structure:

```text
VehiclesDetectionDataset/
  dataset.yaml
  train/
    images/
    labels/
  valid/
    images/
    labels/
```

## Classes

```text
Ambulance
Bus
Car
Motorcycle
Truck
```

## How To Run

1. Open the notebook in Kaggle or another GPU-enabled environment.
2. Attach the vehicle detection dataset.
3. Install the notebook dependencies when prompted.
4. Run the dataset inspection cells first.
5. Train either the from-scratch model or the transfer-learning model.
6. Review the generated training results and validation metrics.

## Notes

This is an experiment notebook. The next improvement is to export key metrics, add sample result images to the repository, and document the final best-performing model configuration.

