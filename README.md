## INTEGRATING DETECTION AND CLASSIFYING SKIN LESIONS:
A COMPREHENSIVE APPROACH BY INTEGRATING IMAGE PROCESSING AND PREDICTIVE MODELLING FOR EARLY DIAGNOSIS AND PROGNOSIS.

## Team Members:
1. Akash R 
2. Mohamed Anwardheen M
3. Vignesh S

## ABSTRACT : 
Skin cancer, particularly malignant skin lesions, poses a significant threat, emphasizing
the crucial need for early detection and treatment. Using HAM10000 dermatoscopic image dataset to
identify and classify the various types of skin lesions. Initial pre-processing involves the application of
an adaptive median filter for effective denoising, ensuring the quality of subsequent analysis. Particle
Swarm Optimization (PSO) coupled with K-Means for initial segmentation. And the processed images
are then subjected to a U-net architecture, a proven encoder-decoder structure widely employed in
medical image segmentation. Subsequently, a deep convolutional neural network (DCNN) is utilized to
classify distinct classes of skin lesions based on the segmented image. In addition to the prior model,
incorporating GPT-2 Language Model, Fine-Tuned on Dermatology Question-Answer Dataset. This
model enabled the development of Chatbot capable of extracting symptoms and providing potential
causes and treatments. Using extracted User-symptoms, TF-IDF vectorizer and a naive Bayes classifier
into the system enhances the prediction of skin lesions. Eventually, integrating both image classification
and Chatbot using Django Web Framework. This sophisticated approach of combining advanced image
processing techniques with LLM, aims to enhance the accuracy and efficiency of skin lesion diagnosis
and prognosis. The accuracy obtained for image classification is 96.75 % for HAM10000 Dataset and
for LLM is 47.33%


 ### ARCHITECTURE DESIGN

 ![PHOTO-2024-04-26-16-57-44](https://github.com/AkashR0712/INTEGRATING-DETECTION-AND-CLASSIFYING-SKIN-LESIONS/assets/122616990/ace10be0-d8da-4d6b-9fb1-1f3f7b887036)


 # DJANGO OUTPUT 
 ![image](https://github.com/AkashR0712/INTEGRATING-DETECTION-AND-CLASSIFYING-SKIN-LESIONS/assets/122616990/bce1e55b-609f-43f6-8ead-7c1362065541) 

  ![image](https://github.com/AkashR0712/INTEGRATING-DETECTION-AND-CLASSIFYING-SKIN-LESIONS/assets/122616990/ff698730-16a6-4960-a497-f7ca86865124)

