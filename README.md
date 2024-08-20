# 🧠 WeaklySupervised-Classification-Benchmark-For-Computational-Pathology
Welcome to my implementation of a classical approach for weakly supervised classification using the MNIST dataset! This project is inspired by the methodologies outlined in the paper "Benchmarking weakly-supervised deep learning pipelines." The goal of this project is to explore weakly-supervised deep learning techniques for detecting malicious cells in a structured data environment.

## 🚀 Project Overview

This repository contains the implementation of the classical apporach outlinesd in the paper cited above, this model aims at detecting a specific type of "malicious" data point within the MNIST dataset. Specifically, I considered a "bag" of 10 MNIST digits, where the digit '1' is treated as the "malicious" cell. This project demonstrates the effectiveness of traditional approaches in a weakly-supervised setting.

### Key Features:
- **Data Source:** MNIST dataset, a large database of handwritten digits.
- **Malicious Cell:** The digit '1' is treated as the target for detection.
- **Bag of Digits:** Each training example is a bag containing 10 digits.
- **Weak Supervision:** The approach uses weak labels, focusing on detecting the presence of a malicious cell in each bag.

## 🚧 How It Works

The project leverages classical machine learning techniques to detect the presence of a "malicious" digit '1' within a bag of 10 MNIST digits. The process involves:

1. **Data Preparation:** Loading the MNIST dataset and organizing it into bags.
2. **Model Training:** Training a classifier to identify the presence of the digit '1' within each bag.
3. **Evaluation:** Measuring the model's performance using standard metrics like accuracy, precision, and recall.

## 🎯 Results

The goal of this project was to implement the approach proposed in the paper. However, I wasn't able to achieve satisfactory results, and the model's performance fell short of expectations. Further fine-tuning of the hyperparameters is necessary to fully demonstrate the potential of classical methods in weakly-supervised scenarios.

## 📚 References

- [Benchmarking weakly-supervised deep learning pipelines](https://www.sciencedirect.com/science/article/abs/pii/S1361841522001219)

## 📬 Contact

If you have any questions or suggestions, feel free to reach out to me at [hatim.mrabet@student-cs.fr](hatim.mrabet@student-cs.fr).

