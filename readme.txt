# Skin Lesion Classifier

A multiclass classifier that predicts different kinds of skin lesions from photographs.

The dataset used for training the model is "HAM10000"
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T

The model is created using the fastai library where transfer learning was used with a pretrained resnet34 model.
http://fast.ai

The resnet34 model was pretrained with the Imagenet dataset
http://www.image-net.org/