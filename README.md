# Computer Vision Course Projects

A collection of computer vision projects covering various topics including image segmentation, object detection, classification, and more.

## About

This repository contains practical implementations and projects completed during a comprehensive computer vision course. Each project demonstrates different aspects of computer vision and deep learning techniques.

## Projects

### 1. Insulator Segmentation
**Semantic segmentation of insulators in power line images**

- **Task**: Segment insulators on aerial power line photos captured by UAVs
- **Architecture**: U-Net with ResNet34 encoder
- **Performance**: 0.9895 Dice coefficient
- **Techniques**: Transfer Learning, Data Augmentation, Test-Time Augmentation
- **Framework**: PyTorch

[View Project →](./01_insulator_segmentation)

---

## Homework Assignments

Course homework assignments implementing various computer vision techniques:

- **Homework 5.1**: Neural network fundamentals
- **Homework 5.2**: Dense and convolutional neural networks
- **Homework 5.3**: AlexNet implementation and activation map visualization

## Seminars

Practical notebooks from course seminars:

- **Seminar 1**: Introduction to Computer Vision and PyTorch basics
- **Seminar 2 Part 1**: Gradient descent and optimization
- **Seminar 2 Part 2**: Wine classification with neural networks
- **Seminar 3**: Advanced classification techniques

## Repository Structure

```
computer_vision_course/
├── README.md                        # This file
├── requirements.txt                 # Common dependencies
│
├── Homework_5_1.ipynb               # Homework assignments
├── Homework_5_2.ipynb
├── Homework_5_3.ipynb
│
├── Seminar_1.ipynb                  # Seminar notebooks
├── Seminar_2_part1.ipynb
├── Seminar_2_part2.ipynb
├── Seminar_3.ipynb
│
├── 01_insulator_segmentation/       # Project 1: Insulator segmentation
│   ├── insulator_segmentation.ipynb
│   ├── requirements.txt
│   ├── README.md
│   └── samples/
│
└── 02_[next_project]/               # Next project
```

## Technologies Used

- **Deep Learning Frameworks**: PyTorch, TorchVision
- **Computer Vision**: OpenCV, Albumentations
- **Data Science**: NumPy, Pandas, Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Development**: Jupyter Notebook, Git

## Key Skills Demonstrated

- Semantic Segmentation
- Transfer Learning
- Data Augmentation
- Model Training & Optimization
- Performance Evaluation
- Deep Learning Best Practices

## Installation

Each project has its own `requirements.txt` file. Navigate to the specific project directory and install dependencies:

```bash
cd 01_insulator_segmentation
pip install -r requirements.txt
```

## Contact

**Murat Raimbekov**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/murat-raimbekov)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/raimbekovm)

## License

This repository is for educational and portfolio purposes.
