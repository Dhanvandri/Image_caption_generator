# Image_caption_generator

Generating accurate and meaningful descriptions for images poses a significant challenge,
especially when traditional approaches focus solely on maximizing the likelihood of target
sentences, overlooking crucial elements like human-object interaction (HOI) and semantic
relationships within the image. This abstract introduces an innovative framework aimed at
addressing these challenges. The first phase leverages a hybrid deep learning approach,
introducing with interaction machine to hierarchically learn relational features of human-object
pairs. This transforms the image recognition problem into a labeling task. The framework hybrid
scheme integrated with a caption generator. The integration of NLP text to speech allows for
seamless interaction with the described images in an efficient way, it will also be helpful for
visually impaired person. The pretrained faster RCNN model extracts the features from the
dataset. The model has been incorporated to train the dataset with 8000 images. The data set will
be divided into training and test set. This model contains encoder and decoder part. Encoder part
converts the extracts feature into numerical values. Decoder part used that extracted feature
values and caption as sequence of numerical values to generate the corresponding caption.
Evaluation has been done with BLEU score.
The Captions should not only describe what is seen but also convey the essence of the image in
natural language. This requires generating fluent and diverse sentences that are both accurate and
engaging.
