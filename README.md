# Vedantu Internship Task
# Implemented Research paper- Show and Tell: A Neural Image Caption Generator (https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Vinyals_Show_and_Tell_2015_CVPR_paper.pdf)

# **I HAVE USED TWO METHODOLOGIES TO IMPLEMENT THE GIVEN RESEARCH PAPER**

- Everything can be run on Colab
- To run in Colab you need to add your kaggle's API token file for Approach 2.

## APPROACH 1

- Flickr8k dataset has been used.
- Features have been extracted from images using pretrained model - Resnet50
- Data pre-processing has been done for captions.
- I have used Stanford's glove6B word embeddings.
- Data preparation has been achieved using generator function.

## APPROACH 2

  - Dataset: MS-COCO
  - Encoder: InceptionV3
  - Attention: Bahdanau's Soft attention
  - Decoder: LSTM unit
  - Embeddings: Glove Embedding (glove6b300d)
