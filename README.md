
<div align="center">
  <a href="https://github.com/alaaNfissi/INSE6220_Project">
    <img src="voice-biometrics-1024x576.jpg" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">Exploring the Power of PCA and Machine Learning for Speech Emotion Recognition with a Focus on Explainable AI</h3>
   <!-- <a href="https://github.com/alaaNfissi/INSE6220_Project"><strong>Explore the docs »</strong></a> -->
</div>

## Abstract

<p align="justify"> In this study, we propose a method for speech emotion recognition based on the acoustic features of the voice,
with a particular focus on the explainability of the results. To accomplish this, we first calculated as many speech features as possible that may be useful for emotion recognition, resulting in a total of 94 features. We then conducted a feature selection process, using principal component analysis (PCA), to select the 10 features that best represented the variance and information in our dataset. We then applied machine learning models to these features to evaluate their performance. To further improve the accuracy of our model, we applied PCA to reduce the dimensionality of the data and reduce noise. We then applied machine learning models to the first five principal components, resulting in the top three performing models: Extra Tree, Random Forest, and then K-Nearest Neighbors. Finally, we fine-tuned the best performing model and used SHAPLEY values to interpret the explainability of the model’s predictions. Overall, this work presents a comprehensive approach to speech emotion recognition that highlights the importance of both machine learning and explainable AI. The proposed work was evaluated on TESS dataset. </p>
