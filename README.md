# PNEUNOMIA-DETECTION-USING-CNN


An automated system using machine learning techniques to accurately and efficiently detect pneumonia and other lung diseases(Tuberculosiand Covid-19) from chest X-ray images, enabling faster and more reliable
diagnoses for timely medical intervention.

# METHODOLOGY
- Gather lung disease datasets and select the best available dataset for
  each class.
- The images of the gathered dataset are preprocessed, rescaled, and
  augmented as a part of preprocessing.
- The system is trained using the newly compiled dataset of labeled
  chest X-ray images, where each image is annotated into pneumonia,
  normal, tuberculosis, or COVID-19.
- Adjustments are made to the model based on the analysis
  post-training.
- After training, a CXR image image is fed into the network to
  generate a prediction indicating the likelihood of lung disease.
# RESULTS
- After training the model for 100 epochs, the model achieved a
  training loss of 0.0063 and a training accuracy of 99.90 percent.
- The validation loss at the end of the training was 0.0081, with a
  validation accuracy of 99.84 percentage.
- After evaluating the model on the test dataset, it achieved a test loss
  of 0.0241 and test accuracy of 99.36 percentage.
# CONCLUSION
- The developed model demonstrated promising accuracy in classifying chest X-ray
  images of Pneumonia, Normal, Tuberculosis, and Covid using Deep learning
  techniques, indicating its potential for accurate diagnosis of various chest
  conditions.
- Convolutional neural networks (CNNs) proved effective in extracting relevant
  features and patterns from the X-ray images, contributing to the model’s
  successful classification performance.
- Accurate classification of chest X-ray images has the potential to significantly
  assist in early detection and diagnosis, ultimately benefiting patient outcomes.
- This project highlights the valuable role of Deep learning in automating image
  analysis and aiding decision-making in the medical field. However, certain
  limitations, such as dataset constraints, and opportunities for further model
  enhancements should be considered for future research and development.

  

# Project v2 (PNCT) 
**1.** v2 Dataset 5.1 (TB replaced with Belarus) Link:
         https://drive.google.com/drive/folders/12eadNrEtuxmn6bkytmNitqG8-IAbePrL?usp=drive_link
         
**2.** v2 Dataset 5.0 (Imbalanced) Link:
         https://drive.google.com/drive/folders/1ARY8yYrXgVA1MKbKmQwXyG0KVgSPl9TY?usp=drive_link
         
**3.** v2 Dataset 5.1.1 (replaced with COVID-19 Radiography Dataset) Link:
         https://drive.google.com/drive/folders/1Xq-tITMcUxYRsEjxw939XPKeGRs-661e?usp=drive_link

**4.** Shenzen Dataset Link:
         https://drive.google.com/drive/folders/1HTaWkGav3cvYTn4ebUOD9ymlfcL1I3Su?usp=drive_link
         

# MODELS         
**1.** Model of Jv2.12 [99.51% acc] Dataset 5.1.1, Arch 1, 100 epoch, 16 batch size.h5: https://drive.google.com/file/d/10fZwFbmg-WL52h6_JxK6O25m0iDFw9Bw/view?usp=sharing
