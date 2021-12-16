# Homework 3: Nuclei Instance Segmentation

## How to Train

1. Install the packages in `requirements.txt`  by the command `pip install -r requirements.txt`
4. Run all cells in the `Traincode.ipynb` notebook in order to generate the annotation files and train the model.
5. The final weight file will be generated as `output/model_final.pth`.

## How to Test

1. Install the packages in `requirements.txt`  by the command `pip install -r requirements.txt`
2. Run all cells in the `inference.ipynb` notebook in order to download the trained weights and generate the `answer.json` annotation file.
   * If a model was trained above, change the `cfg.MODEL.WEIGHTS` from `model_final.pth` to `output/model_final.pth`.
6. Zip the file into `answer.zip` and upload to CodaLab.
