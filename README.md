# SegmentationManager

This is the README for the SegmentationManager repository, a library that pretends to simplify as much as possible the construction and training for image segmentation models.

The content of this repository files are described below:
- `utils`: some general functionality used in the other components.
- `dataset.zip` and `dataset_with_errors.zip`: two dataset used in the demonstration of use of the library.
- `DatasetManager`: the interface that manages the dataset structure and its data.
- `TransformManager`: the interface that manages the transformations applied to the data.
- `ValidationManager`: the interface that manages the validation strategy for the models (such as train-test splits or kfold validation).
- `DataLoaderManager`: for those libraries that use _fastai_, the component that manages the `DataBlock`s and `DataLoader`s definitions.
- `ModelManager`: the interface that manages the models construction, training, saving and loading.
- `SegmentationManager`: the facade to all the other components, the visible part for the library.

Authors: Jónathan Heras (joheras@unirioja.es) and Rubén Escobedo (ruescog@unirioja.es).

![Creative commons: BY-NC-SA](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)
