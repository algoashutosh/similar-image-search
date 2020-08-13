# This repo contains the code for similar-image-search
- Run similar image search.ipynb file
- images are cluster into k cluster using k-mean.
- Vgg19 model is used for transfer learning.
- Convert image database into feature vectors using our dissected VGG model. 
- If the output layer of the dissected model are convolutional filters then flatten the filters and append them make a single vector.
- computed similarities between our image feature vectors using an inner-product such as cosine similarity or euclidean distance.
-  For each image, selected the images with the top-k similarity scores to show similar images.
