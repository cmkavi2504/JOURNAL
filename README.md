# JOURNAL

** **A Review on Speech Emotion Recognition With Machine Learning Techniques** **

**Introduction**
 - The paper explores the challenges of speech emotion recognition and highlights the need for more research to improve current approaches. 
 - The review emphasizes the importance of defining emotions and representing features accurately. 
 - The study identifies research gaps in the fine-grained emotion classification, which is crucial for applications such as psychiatric therapy. 
 - To address these gaps, the review suggests delving deeply into machine learning approaches to improve SER's precision and efficacy. 

**Background of the Paper**
 - Using Convolutional Neural Networks (CNNs) for voice emotion recognition involves processing spectrograms or other audio representations to capture patterns related to emotions.
 - Convolutional Neural Networks (CNNs) employing architectures like VGG16 have demonstrated remarkable efficiency.
 - VGG16, with its deep hierarchical structure, excels in learning intricate patterns from spectrograms or features extracted from audio signals, enabling nuanced emotion detection.

**Related works**
 - According to Li Min Zhang, Yu Beng Leau, Giap Weng Ng, and Hao Yan, [1] The difficulties in Speech Emotion Recognition (SER), a critical component of human-computer interaction with applications in senior care, healthcare, and education, are discussed in this work
 - According to Shifang Cai, Ce Wang, and Gang Liu , [3] method for speech emotion recognition validated by initial trials on the IEMOCAP dataset. The method is crucial for human intelligence, decision-making, and social interaction, and has numerous applications. The researchers emphasize the need for improved emotional information modeling and look ahead to future developments in speech emotion detection.
   
**Problem Formulation**
 - The problem identification revolves around developing a robust system capable of accurately categorizing emotions such as joy, anger, sadness, and more based on the acoustic features of a person's voice. 
 - Challenge in speech emotion recognition: Analyzing and detecting emotions in speech signals.
 - Limitations of current approaches: Reliance on traditional signal processing and handcrafted features, lacking nuanced emotional expression capture.

**Proposed System**
 - The proposed system wants to increase the efficiency and accuracy of speech emotion recognition using convolutional neural network (CNN) with the VGG-16 architecture. 
 - The VGG-16 architecture, renowned for its effectiveness in image recognition tasks, is adapted to process speech spectrograms efficiently. 
 - Spectrograms capture the frequency content of speech signals over time and provide valuable insights into emotional states. 
 - The system pre-processes raw audio data to extract relevant features such as spectrograms.
 - These features are then fed into the VGG-16 CNN model for training and classification. 
 - Transfer learning techniques may be employed to leverage pre-trained weights of the VGG-16 model, enhancing the training process and performance. 
 - The proposed system is evaluated using standard speech emotion datasets such as the Ravdess dataset. 
 - Several metrics for performance, like accuracy, recall, f1-score and precision are utilized to calculate the model's effectiveness in recognizing different emotional states.

**Expected Results**
 - **Training & testing** - CNN is trained to know the patterns between the extracted features and the labeled emotions. Then trained data will be tested for future accuracy prediction.
 - **Performance metrics** -  Measure how reliable a model's predictions are, representing the proportion of properly classified samples in relevance to the  total samples.
 - **Expected Prediction** - The confusion matrix serves as a valuable tool to achieve higher accuracy and robustness. Each cell in the matrix contains the count of instances that belong to the intersection of the predicted and actual classes.
   
**Conclusions**
 - This review explores the complexities of Speech Emotion Recognition (SER) and highlights the need for a deeper understanding. 
 - It strives to enhance SER capabilities by exploring machine learning techniques. With potential applications in areas like psychological counseling, this work advocates for a nuanced approach to understanding SER. 
 - By identifying gaps in research and emphasizing the crucial role of SER, this review highlights the need for continued exploration and innovation in this field.

**Future work**
 - speech emotion recognition (SER) using CNNs involves exploring complex architectures, integrating attention mechanisms, and utilizing larger datasets for better generalization. 
 - Incorporating contextual information and transfer learning techniques can enhance accuracy, while real-time SER systems for human-computer interaction remain a promising area for further research.

**References**
 - [1] Li-Min Zhang, Giap Weng Ng, Yu-Beng Leau, Hao Yan, " A Parallel Model Speech Emotion Recognition Network Based on Feature Clustering" , DOI:10.1109/access.2023.3294274, pub month: July 2023.
 - [2] Taiba Majit Wani , Teddy Suriya Gunawan , Syed Asif Ahmad Qadri , Mira Kartiwi ,and Eliathamby Ambikairajah, "A Comprehensive Review of Speech Emotion Recognition Systems " doi: March 2021.
 - [3] Gang Liu, Shifang Cai, Ce Wang, "Speech emotion recognition based on emotion perception" access: EURASIP Journal on Audio, Speech, and Music Processing  2023, Article number: 22 (2023), Doi: 10.1186/s13636-023.
 - [4] Felicia Andayani, Lau Bee Theng, Mark Teekit Tsun, and Caslom Chua , "Hybrid LSTM-Transformer Model for Emotion Recognition From Speech Audio Files" access:doi.org/10.1109/2022.3163856, doi: March 2022.
 - [5] Bagus Tris Atmaja,  Akira Sasou, and Masato Akagi, "Speech Emotion and Naturalness Recognitions With Multitask and Single-Task Learnings", DOI:10.1109/ACCESS.2022.3189481, Date of publication: January 2022.
