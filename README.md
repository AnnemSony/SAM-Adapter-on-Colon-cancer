
The research paper were published in SPIE conference:
https://spie.org/medical-imaging/presentation/Adapting-SAM-to-histopathology-images-for-tumor-bud-segmentation-in/12933-11?enableBackToBrowse=true#_=_
# Adapting SAM for Tumor Bud Segmentation in Histopathology Images

This project demonstrates how to adapt the Segment Anything Model (SAM) for tumor bud segmentation in histopathology images, as presented in the SPIE Medical Imaging Conference. The paper highlights a novel approach for segmenting tumor buds in medical images using SAM, which is fine-tuned to detect complex structures like tumor buds in histopathology slides.

The research paper, titled **"Adapting SAM to Histopathology Images for Tumor Bud Segmentation in Medical Imaging"**, was published at the SPIE Medical Imaging Conference. It discusses the challenges of segmenting tumor buds in histopathology images, a critical task in cancer diagnosis and prognosis. SAM was adapted to perform this task with high accuracy, demonstrating its potential in medical image segmentation tasks.

### Key Contributions:
- Adaptation of the SAM (Segment Anything Model) for histopathology image segmentation.
- Focus on tumor bud segmentation in cancerous tissues.
- Efficient fine-tuning and validation on histopathology datasets.
- Improved segmentation accuracy for better clinical decision-making.

## Setup Instructions

### Step 1: Download and Place SAM Models

1. Download the pre-trained SAM models from [SAM's official model repository](https://github.com/facebookresearch/segment-anything).
2. Place the downloaded models in the `models/` folder.

### Step 2: Place Your Dataset

1. Place your histopathology dataset in the `datasets/` folder.
   - Ensure the dataset consists of images and corresponding labels for tumor bud segmentation.
   - You can use publicly available datasets or provide your own.

### Step 3: Modify Configurations (Optional)

1. Modify any configurations in the `configs/` directory to match your dataset or desired model settings. Adjust paths, batch sizes, learning rates, etc., to suit your environment.

### Step 4: Train the Model

Once everything is set up, you can begin training the model by running the following script:

```bash
python train.py


