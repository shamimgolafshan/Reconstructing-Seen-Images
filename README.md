# Reconstructing seen images from visually evoked fMRI using a promoted shape-semantic GAN
In this project, we tried to increase the quality of Images that people saw during an experiment. Our base article was: 
## Data
We used preprocessed data from "Reconstructing Perceptive Images from Brain Activity by Shape-Semantic GAN"[1]
You can download the Preprocessed fMRI data from here[2]:
(https://figshare.com/articles/dataset/Deep_Image_Reconstruction/7033577)

## Method
We used an Convolutional Auto Encoder to decode the best features of naturalistic Images and then trained Base decoders using these features.
this is the overview of our framework:

<img width="338" alt="image" src="https://github.com/shamimgolafshan/Reconstructing-Seen-Images/assets/35660420/bead69b5-08d4-4310-904c-9c7f829d5b99">


## Result 
as a result, we have:
<br> <img width="474" alt="image" src="https://github.com/shamimgolafshan/Reconstructing-Seen-Images/assets/35660420/8dd881fc-3638-4624-8e24-82ba06e08017">

<br>For evaluate the similarity we used SSIM("structural Similarity Index Measure") and MSE which you can see below:
<br> <img width="409" alt="image" src="https://github.com/shamimgolafshan/Reconstructing-Seen-Images/assets/35660420/6c6869d7-a63c-4653-899c-1dfe7f6d788c">








[1]Fang, Tao, Yu Qi, and Gang Pan. "Reconstructing perceptive images from brain activity by shape-semantic gan." Advances in Neural Information Processing Systems 33 (2020): 13038-13048.
<br>[2]Shen, Horikawa, Majima, and Kamitani (2019) Deep image reconstruction from human brain activity. PLoS Comput. Biol. http://dx.doi.org/10.1371/journal.pcbi.1006633.
