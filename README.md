# keras_tta
Simple test time augmentation (TTA) for keras python library.

### Example:
```python
tta_model = TTA_ModelWrapper(model)
predictions = tta_model.predict(X_test)
```
