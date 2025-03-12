#  **Image Captioning using Deep Learning**  

##  **Project Overview**  
This project focuses on **generating captions** for images using a **Deep Learning model** that combines:  
- 🔹 **CNN (Convolutional Neural Networks)** – For feature extraction from images.  
- 🔹 **RNN (Recurrent Neural Networks) with LSTM** – For caption generation.  

## 📂 **Dataset Used**  
 **Flickr8k Dataset** – Contains **8,000 images**, each paired with **5 different captions**.  

## 🔄 **Workflow**  
1 **Data Preprocessing** 🛠️  
   - Clean and tokenize captions.  
   - Create a vocabulary of words.  

2️ **Feature Extraction** 🎯  
   - Extract image features using **VGG16 / InceptionV3**.  

3️ **Caption Generation** 📝  
   - Train an **LSTM-based model** to generate textual descriptions.  

4️ **Model Training & Evaluation** 📊  
   - Train on processed data and evaluate using **BLEU score**.  

## 🎯 **Results & Insights**  
 Generates **accurate and meaningful** captions for images.  
 Performance improves with **larger datasets & fine-tuned architectures**.  

## 🚀 **Future Enhancements**  
- 🔹 Implement **Transformers (ViT + GPT-2)** for better accuracy.  
- 🔹 Extend training with a **larger dataset (MS COCO)**.  
