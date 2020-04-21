**Classifying Chest X-Ray images of Normal vs Pneumonia patients**

**Background and Problem**  
Pneumonia is an infection of the lungs that may be caused by bacteria, viruses or fungi. The infection causes the lung’s air sacs (alveoli) to become inflamed and fill up with fluid or pus. That can make it hard for the oxygen you breathe in to get into your bloodstream. The people most at risk are infants and young children, adults 65 or older and people who have other health problems.
According to the World health Organization (WHO), pneumonia kills about 2 million children under 5 years of age every year and is consistently estimated as the single leading cause of childhood mortality (Rudan et al., 2008), killing more children than HIV/AIDS, malaria and measles combined (Adegbola, 2012). The WHO reports that nearly all cases (95%) of new onset childhood clinical pneumonia occur in developing countries, particularly in Southeast Asia and Africa. Bacterial and viral pathogens are the two leading causes of pneumonia (Mcluckie, 2009) but require very different forms of management. Bacterial pneumonia requires urgent referral for immediate antibiotic treatment, while viral pneumonia is treated with supportive care. Therefore, accurate and timely diagnosis is imperative. One key element of diagnosis is radiographic data, since chest X-rays are routinely obtained as standard of care and can help differentiate between different types of pneumonia. However, rapid radiologic interpretation of images is not always available, particularly in the low-resource settings where childhood pneumonia has the highest incidence and highest rate of mortality.
Hence, a computational approach to classify the X-rays is very crucial for timely care of the patients.

**Data set**
Data Source: [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), [Mendeley](https://data.mendeley.com/datasets/rscbjbr9sj/3)
 
The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows). Lung consolidation occurs when the air that usually fills the small airways in your lungs is replaced with something else and is called lobar when it occurs on tone of the lobes of the lung. It infers alveolar spread of disease. Whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs - the connective tissue (interstitium) that forms the support structure of the alveoli (air sacs) of the lungs
The dataset contains X-Rays from children and is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

**Images**
![Chest X-Ray Images](https://i.imgur.com/jZqpV51.png)

**Solution and Client**
This is a binary classification problem – classifying the X-rays as normal or pneumonia and help getting urgent care for the patients. This will help healthcare professionals to speed up diagnosis and get treatment started for patients with pneumonia. Detection and treatment of such abnormalities at an early stage can help save lives.

**Relevant Papers**
http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
Chhikara P., Singh P., Gupta P., Bhatia T. (2020) Deep Convolutional Neural Network with Transfer Learning for Detecting Pneumonia on Chest X-Rays. In: Jain L., Virvou M., Piuri V., Balas V. (eds) Advances in Bioinformatics, Multimedia, and Electronics Circuits and Signals. Advances in Intelligent Systems and Computing, vol 1064. Springer, Singapore

**The Files uploaded for this project are:**
1) Capstone Proposal - Capstone 2 Project Proposal.docx
2) Capstone Milestone Report - Capstone 2 Milestone Report.docx
3) Capstone Final Report - Capstone 2 Final Report
4) Capstone code - xray.ipynb
5) Capstone slides - capstone2.pptx
