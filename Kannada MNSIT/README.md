# Kannada-MNSIT
# Discover structure in data using TSNE and UMAP

Download Kannada MNIST dataset from Kaggle [https://www.kaggle.com/c/Kannada-MNIST]. As is there in every Indian language, there are ten digits. Kannada digits were handwritten and then scanned. Each scanned image is 28 X 28 = 784 pixels. There are 60000 images with each digit hand-written by many different persons. The image-pixels were then flattened into a row and a label for the corresponding digit added. We, therefore, have a dataset of shape: 60000 X (784+1) . Label values are, of course, 0-9.  Elsewhere in the row, corresponding pixel intensity is entered. 

The images are gray scale. Pop out the label column from the dataset. And apply tsne and umap on the remaining dataset (60000 X 784).

Do tsne and umap display clear structure in the data? See if you can use umap output for digits classification also. Try to use different metric for distances in umap and see the effect. Please submit the URL of your github file in the folder below.
