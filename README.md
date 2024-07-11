# Federated-Learning-Kilo-Bao

## Project Description
This project implements a Python and PyTorch based federated learning simulation system. It includes simulating multiple clients and a base station to train and aggregate models, exploring the impact of non-independent and identically distributed (non-iid) data on model performance. The project offers a variety of datasets and neural network architectures, as well as algorithms for non-iid data distribution.

## Features
- **Multiple Dataset Support**: Supports MNIST, CIFAR-10, and FashionMNIST datasets.
- **Various Network Architectures**: Includes MLP, CNN, AlexNet, VGG, and ResNet.
- **Non-IID Data Simulation**: Implements data distribution to different clients in both iid and non-iid manners.
- **Model Aggregation**: Supports various model aggregation methods, such as simple average and weighted average.
- **Performance Evaluation**: Provides a function to evaluate the model's accuracy on the test dataset.

## File Structure
- `Player.py`: Defines classes for the base station and clients.
- `main.py`: The main program, implementing the initialization, training, and testing processes of federated learning.
- `DataSet.py`: Module for loading datasets, supporting multiple types.
- `noniid.py`: Algorithms for non-iid data distribution.
- `Networks.py`: Defines several neural network models.
- `Functions.py`: Contains a function to evaluate the model.

## Dependencies
- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib



## Usage
Ensure all dependencies are installed and all project files are in the same directory. Adjust federated learning parameters such as the number of clients and training epochs in `main.py`. Run `main.py` to start training. After training, the model's accuracy on the test dataset will be displayed.

## Developer
[Kilo Bao]

## License
This project is licensed under the MIT License.


## Contact
For any queries or further information, please contact [chongyou.bao@pdx.edu].


