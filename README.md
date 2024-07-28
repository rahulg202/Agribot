# AGROBOOT
**Objective**: To develope a machine learning model to accurately identify and segment regions of plant leaves affected by diseases or pests from images.<br/>
**Data Handling**: Utilized a large dataset of plant leaf images, leveraging TensorFlow for preprocessing and augmentation to enhance model performance.<br/>
**Model Architecture**: Designed a deep learning model with multiple Conv2D layers, MaxPooling, and Dense layers, optimized with Adam optimizer and trained with Sparse Categorical Crossentropy loss.<br/>
**Performance Metrics**: Achieved high accuracy and low loss on both training and validation datasets, monitored through comprehensive accuracy and loss plots.<br/>
**Data Augmentation**: Implemented advanced data augmentation techniques, including random flips and rotations, to improve model robustness.<br/>
**Evaluation**: Evaluated the model using a separate test dataset, obtaining precise accuracy and loss metrics.<br/>
**Prediction Capability**: Developed a function for predicting the class and confidence of disease/pest in new images, ensuring practical applicability.<br/>
**Model Deployment**: Successfully saved and deployed the trained model for real-world usage on a Jetson Nano using Raspberry Pi CAM for image capturing.<br/>
**Tools & Technologies**: TensorFlow, Keras, Python, NumPy, Matplotlib, Google Colab.
