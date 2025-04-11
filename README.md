# Semantic Segmentation of Mars Surface Images
This project was developed during a two-week [Coding Challenge](https://www.kaggle.com/competitions/an-2-dl-2024-2025-homework-2/overview) as part of the evaluation for the _Artificial Neural Networks and Deep Learning_ course at Politecnico di Milano, A.Y. 2024-2025. The programming language used is Python, specifically employing the TensorFlow/Keras library.

## Files description
- [https://github.com/niccolo-s/BloodCellsClassification/blob/main/CNN_for_Blood_Cells_Classification.pdf](https://github.com/niccolo-s/Mars-Semantic-Segmentation/blob/main/Mars_Semantic_Segmentation.pdf): this is the project report, where you can find detailed information about the development process and the results of our tests.
- [https://github.com/niccolo-s/BloodCellsClassification/blob/main/EfficientNetB6_Tuned.ipynb](https://github.com/niccolo-s/Mars-Semantic-Segmentation/blob/main/code.ipynb) is the notebook containing the code for building, training and testing the models. It is designed to allow users to select a model to train from a list simply by modifying the "__confing__" dictionary in the "_Model Parameters_" section.

## Final results 
The final model achieved an __overall accuracy of 64.87%__ on the evaluation test set, placing it in the top 30% of the class. The highest accuracy achieved in the class was 69.39%.

It is worth noting that this challenge prohibited the use of pre-trained models, requiring all participants to train their networks from scratch. Additionally, the training masks provided were of very low quality, which posed significant challenges during the development phase. Despite these limitations, the model demonstrated decent performance and provides a solid foundation for further improvements.

## Authors
- Agnese Negroni
- Alberto Pola
- Fabio Romagnoli
- Niccolò Signorelli

## Grade
This project received the highest grade possible (5.5 out of 5.5).
