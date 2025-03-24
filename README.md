# ArtExtractTestTaskGSoC

## Trained models: [Link to the models](https://drive.google.com/drive/folders/1I6yZG_m__JqMvG4Ig3rRbYYquGXuNUKL?usp=sharing)

### Instructions for Task 1

1. The conv-recur_{type}.ipynb has the code for training model from scratch.

2. The effnet_rcnn_{type}.ipynb has the code for model with EfficientNetB0 as the convolutional backbone.

3. {type}_eval_effnet.ipynb has code for evaluation for model with EfficientNetB0 as the convolutional backbone and outlier detection.

4. {type}_eval.ipynb has code for evaluation of model trained from scratch and outlier detection.

**type can be one of genre, style, artist.**

### Instructions for Task 2

1. similarity.ipynb has the code for training, evaluation of siamese network with contrastive loss and model with triplet loss as the loss function.

PDFs for all the jupyter notebook files have been added as well as asked.

For running part 1, wikiart.zip must be extracted in the Task1 directory, wikiart_csv is also required in the same directory.

A report for each task is added involving the methodologies, results for that task.

**Note: Some outputs of the jupyter notebook may show kernel crashes, that is because a kill was sent to the process to clear the memory used by that process on the GPU. The code works as expected. In some training processes, the validation error showed no further decrease after 2-3 epochs as well. The training was stopped in such scenarios by keyboard interrupts.**

## Directory structure

```
.
├── README.md
├── Task1
│   ├── artist_class_eval_effnet.ipynb
│   ├── artist_class_eval_effnet.pdf
│   ├── artist_class_eval.ipynb
│   ├── artist_class_eval.pdf
│   ├── conv-recur_artist.ipynb
│   ├── conv-recur_artist.pdf
│   ├── conv-recur_genre.ipynb
│   ├── conv-recur_genre.pdf
│   ├── conv-recur_style.ipynb
│   ├── conv-recur_style.pdf
│   ├── effnet_rcnn_artist.ipynb
│   ├── effnet_rcnn_artist.pdf
│   ├── effnet_rcnn_genre.ipynb
│   ├── effnet_rcnn_genre.pdf
│   ├── effnet_rcnn_style.ipynb
│   ├── effnet_rcnn_style.pdf
│   ├── genre_class_eval_effnet.ipynb
│   ├── genre_class_eval_effnet.pdf
│   ├── genre_class_eval.ipynb
│   ├── genre_class_eval.pdf
│   ├── style_class_eval_effnet.ipynb
│   ├── style_class_eval_effnet.pdf
│   ├── style_class_eval.ipynb
│   ├── style_class_eval.pdf
│   └── Task1 Report.pdf
└── Task2
    ├── similarity.ipynb
    ├── similarity.pdf
    └── Task2 Report.pdf

```
