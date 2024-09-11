https://www.sciencedirect.com/science/article/pii/S2352340923010260
This is a study done wherein a computer vision model was developed to recognise chicken breeds. The breeds in the study are quite distinct from each other, making the classification easy.
I am intending to work using the same dataset and through compiling some of my own datasets in the same style so that I can gain practice in data preprocessing and data augmentation for
neural networks, making use of PILLOW, PyTorch, multiprocessing and pooling. The dataset in question is:
Himel, Galib Muhammad Shahriar; Islam, Md Masudul (2023), “GalliformeSpectra: A Hen Breed Dataset”, Mendeley Data, V1, doi: 10.17632/nk3zbvd5h8.1
=====> https://data.mendeley.com/datasets/nk3zbvd5h8/1

My potential project ideas are as follows:
- extend the original project by adding my bufforpington dataset (compiled using random images from Google Images) to the classes and seeing if a model similar to the one used can identify them
- develop a model to see if a breed is an orpington or not, regardless of colour --> original dataset uses blackorpington; by including my bufforpington, I can develop a wider orpington dataset and try to finetune the model to identify orpingtons by shape
- develop a model to identify distinct breeds which share the same colour variety,  i.e. identify a Buff Orpington from a Buff Plymouth Rock, or a Black Orpington from a Black Peking --> would require searching for more images and compiling another dataset
