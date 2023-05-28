# Project Title

Fashion Image Classification using Transfer Learning and CNN

## Description

The dataset used in this project consists of fashion images representing various weather conditions. It encompasses a diverse collection of clothing images captured in different weather scenarios to ensure the model's robustness and generalization.

## Algorithms Used

- Transfer Learning: Pre-trained models (e.g., ResNet, VGG, Inception) are used to extract features from fashion images. These features are then fed into the custom CNN model.

- Convolutional Neural Network (CNN): The custom CNN architecture is designed to learn and classify fashion images based on their visual features. It consists of convolutional layers, pooling layers, fully connected layers, and dropout layers.

## Dataset

The fashion image dataset used in this project is composed of a diverse collection of sky images captured in various weather conditions. The dataset is labeled with three categories: sandstorm, shine, and snow. It encompasses a wide range of weather scenarios to ensure the model's robustness and generalization.

## Installation

1. Clone the repository:
```
git clone https://github.com/yongjun-hong/ResNet-CNN-AI_Project.git
```

## Usage

1. Prepare the dataset:
- Place the fashion image dataset in the `data` directory.
- Ensure the dataset is organized with separate folders for each category.

2. Train the model:
- Run the `train.py` script to train the fashion image classification model using transfer learning and CNN.
- Adjust the hyperparameters and model configurations in the script as desired.

3. Evaluate the model:
- Run the `evaluate.py` script to evaluate the trained model on the test dataset.
- View the accuracy and performance metrics of the model.

4. Experiment with different settings:
- Modify the architecture, hyperparameters, or dataset to experiment with different configurations and improve the model's performance.

## Results

The trained fashion image classification model achieves high accuracy on the test dataset, demonstrating its effectiveness in accurately categorizing fashion images under different weather conditions. The results include a comparison between transfer learning and the custom CNN approach, along with visualizations of feature clusters using t-SNE.

<details>
    <summary> epochs </summary>

```
Epoch 0/14
----------
Loss: 35.1723 Acc: 0.6966

Epoch 1/14
----------
Loss: 11.6631 Acc: 0.8180

Epoch 2/14
----------
Loss: 15.0258 Acc: 0.7978

Epoch 3/14
----------
Loss: 17.9296 Acc: 0.8292

Epoch 4/14
----------
Loss: 7.9915 Acc: 0.8494

Epoch 5/14
----------
Loss: 6.0286 Acc: 0.8202

Epoch 6/14
----------
Loss: 4.9641 Acc: 0.8719

Epoch 7/14
----------
Loss: 2.0133 Acc: 0.9213

Epoch 8/14
----------
Loss: 2.7915 Acc: 0.9101

Epoch 9/14
----------
Loss: 2.1360 Acc: 0.8989

Epoch 10/14
----------
Loss: 1.8703 Acc: 0.8787

Epoch 11/14
----------
Loss: 1.5321 Acc: 0.9034

Epoch 12/14
----------
Loss: 1.4601 Acc: 0.9034

Epoch 13/14
----------
Loss: 1.1378 Acc: 0.8944

Epoch 14/14
----------
Loss: 1.3390 Acc: 0.9101

Training complete in 1m 49s
Best Acc: 0.9213
```
</details>

<details>
    <summary> Result Images </summary>
  
 ![3가지 이미지](https://github.com/yongjun-hong/ResNet-CNN-AI_Project/assets/104314593/7057ca08-6063-4ff7-b917-533cc06319ec)

  ![정확도](https://github.com/yongjun-hong/ResNet-CNN-AI_Project/assets/104314593/787ef69a-d615-40a9-a999-678fdf4362e2)
  
  ![손실률](https://github.com/yongjun-hong/ResNet-CNN-AI_Project/assets/104314593/f6cbf76a-4f67-4d4a-9782-34b742fc098c)
  
</details>


## Contributors

- [Yongjun-Hong]([https://github.com/your_username](https://github.com/yongjun-hong))

## License

This project is licensed under the MIT License
