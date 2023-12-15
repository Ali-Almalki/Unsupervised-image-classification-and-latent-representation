# Unsupervised-image-classification-and-latent-representation
Data Availability:

The dataset associated with this project is accessible for download on Google Drive via the following link: [https://drive.google.com/drive/folders/1HUL5PAfhttugIuz4GaXFYRzjwaW_yPVE?usp=sharing](https://drive.google.com/drive/folders/1L0euqhkBRnNUHK4tk3R1tQdQEK7G2JZo?usp=share_link)https://drive.google.com/drive/folders/1L0euqhkBRnNUHK4tk3R1tQdQEK7G2JZo?usp=share_link

Please use the provided link to access the dataset.


A Case study for the research paper Unsupervised image classification and latent representation

Implemented [in this note book](ISIC_dense_net_clustering7.ipynb)

We applied the DenseNet image encoding and KMeans clustering to the ISIC HAM10000 dataset, a collection of diverse skin lesion images. The DenseNet201 model, pre-trained on ImageNet, was fine-tuned using a subset of the HAM10000 dataset. We employed KMeans to cluster the HAM10000 test dataset, aiming to explore natural groupings within the skin lesion images without the guidance of pre-labeled categories. Clustering performance was evaluated using metrics like Adjusted Rand Index (ARI), Normalized Mutual Information (NMI), and purity. We ran the KMeans algorithm repeatedly, selecting the iteration with the highest purity score as the optimal clustering solution. This methodical approach refined our clustering process, ensuring a more reliable and accurate classification of the skin lesion images.


To run this code you must download the ISIC image collection (11,000 images) and it's metadata. 
Both can be down loaded from here.

[HAM10000](https://api.isic-archive.com/collections/212/)

Alternately dowload the larger collection  (30,000 images) from here
[Challenge 2020: Training ](https://api.isic-archive.com/collections/70/)

In either case, unzip the files here
`project-dir/data/images/`
and set the path to the metadata file in the 2nd cell



