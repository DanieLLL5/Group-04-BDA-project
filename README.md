# E-Commerce Recommender System with Databricks & Spark

This is a dedicated GitHub repository for a Big Data Analytics project that leverages Apache Spark and Databricks to develop a scalable recommender system for an E-Commerce platform.

## 🚀 Project Overview

The goal of this project is to build a recommender system that enhances the customer experience by suggesting relevant products based on user behavior and transaction history. By processing large-scale datasets efficiently using Spark, we aim to provide personalized and meaningful recommendations.

## 📂 Repository Structure

```text
.
├── code/                          # Folder that stores the code
│   └── delete_me.txt              # Placeholder (will be removed)
├── data/                          # Folder that stores the dataset
│   └── Sales Transaction v.4a.zip # Transactional dataset (compressed)
└── README.md                      # Project documentation
```

## 📈 Dataset

The dataset is located in the data/ folder and includes historical sales transactions from an E-Commerce platform. The file Sales Transaction v.4a.zip contains the raw data used to train and evaluate the recommender system.

## 📊 Key Features

In the code folders you will find Jupyter notebooks that contain the following features our recommender system contains:

- **Customer Segmentation:** A personalized customer segmentation fully Spark native using K-Means.
- **Recommender based on previous purchases:** A recommender system that provides two main recommendations - one based on the purchase the customer did in the company and another based on what other people similar to him also buys.
- **Did you forget? recommender:** This recommender joins the customer purchase roadmap when it reaches the checkout stage presenting the client with 5 products it does not have in the cart, but that normally buys with the ones it already have in the cart.
- **Streaming:** An implementation of a in real time new purchase being made by the product and how the entire system works out.
- **Graph Frames:** (to be implemented)

## 👤 Contributions

This work was done by:

- Daniel Caridade
- Gonçalo Teles
- Gonçalo Peres
- Guilherme Godinho
- Vinicius Pinto

