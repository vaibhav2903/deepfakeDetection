Deepfakes

This repo contains a literature survey on deepfake generation and detection. I explored the various techniques used to generate, detect and also the shortcomings of the literature. This gave me a very good understanding of the current research in the area and also introduced me to the world of deepfakes.

This repository also contains code used for Deepfake detection using the following methods. I have used google colab for developing the code.  

1. CNN
2. CNN + RNN

For our project, I utilized the deeperforensics dataset and FaceForensics++ datasets for fake images and the original images respectively. The codebase contains how we pre-processed the deepfake videos to be used for detection before we use them in the model. Our models had an accuracy of 93% and 94% respectvely.

In addition to this, I have also added the code to apply XAI techniques on the CNN models to check if we could find any explanation for the outputs. I have applied the following methods for this.

1. LIME
2. SHAP
3. SEDC
4. Saliency Maps

I have added code for using Jaccard index for comparing the masks generated for deepfake frames. This helps in determining the stability of the model as different masks implies that the image used for recognizing the model are different.
