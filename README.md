# few-shot-learning--Deep-learning-project
Project Description
The project explores techniques for learning from limited data on the CIFAR-10 dataset. It addresses two challenges: Challenge 1, which involves using only 50 training examples without external data, and Challenge 2, which allows the use of external data or pre-trained models.

Challenge 1
In Challenge 1, the project investigates a specialized network architecture with regularization techniques such as dropout and batch normalization to counteract overfitting. Data augmentation techniques, including horizontal flipping and diffeomorphic augmentation, are employed to enhance the diversity and size of the training dataset. The project compares the model's performance with and without data augmentation, analyzes the training loss and accuracy, and performs an extensive hyperparameter search to determine the optimal network architecture.

Challenge 2
Challenge 2 explores two methods: transfer learning and fine-tuning using AlexNet and VGG16 models. The code implements these models as feature extractors and trains small fully connected classifiers on the extracted features. Fine-tuning is performed by adapting the models' learned features to the CIFAR-10 dataset. The project compares the performance of both models before and after fine-tuning and includes hyperparameter adjustments, learning rate scheduling, and early stopping to optimize the fine-tuning process.
