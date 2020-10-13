# CV
Goals:
- Load image files (DICOM, PNG), resize to custom dimensions (e.g. (299, 299)), then write to numpy files.
- Combine breast density information with resized image files and write to numpyz files.
- Train a ResNet architecture on resized images to classify breast density as 0 (not dense: 1, 2) or 1 (dense: 3, 4).
- Test NN on test image dataset.
- Display 10 random mammogram images.
- Provide confusion matrix and ROC curve.
