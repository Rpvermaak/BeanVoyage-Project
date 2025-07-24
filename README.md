# ☕ BeanVoyage Project

![GitHub last commit](https://img.shields.io/github/last-commit/Rpvermaak/BeanVoyage-Project?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/Rpvermaak/BeanVoyage-Project?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Rpvermaak/BeanVoyage-Project?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/Rpvermaak/BeanVoyage-Project?style=for-the-badge)

## ✨ Introduction

Welcome to the **BeanVoyage Project**! This repository houses a data analysis project focused on understanding customer behavior and improving customer retention for "BeanVoyage," a hypothetical coffee subscription service.

The core of this project is the `BeanVoyage_Project.ipynb` Jupyter Notebook, where all the magic happens! It takes you on a "voyage" through customer and subscription data, revealing insights into churn patterns and identifying opportunities to increase average order value or subscription length.

## 🌟 Features

Here are some of the key functionalities and analyses performed in this project:

* **Comprehensive Data Import and Merging:** Imports customer and subscription order data, then merges them into a unified dataframe for a holistic view.
* **Exploratory Data Analysis (EDA):** Detailed examination of data types, missing values, and descriptive statistics for both numerical and categorical features.
* **Missing Value Imputation:** Handles missing values in aggregated columns by imputing them with zeros, signifying no activity.
* **Extensive Visualizations:** Generates histograms and box plots for all numerical features to understand their distributions and identify outliers.
* **Categorical Feature Analysis:** Explores the composition of the customer base across different categories (e.g., `subscription_plan`, `product_type`) using value counts and bar charts.
* **Churn Analysis:** Identifies the percentage of churned customers and investigates the reasons for churn, highlighting key factors like "Price Too High" and "Trying Another Service."
* **Bivariate Analysis vs. Churn:** Visualizes churn rates across different categorical features to understand their relationship with customer churn.

## 🚀 Getting Started

To get this project up and running on your local machine, follow these simple steps.

### Prerequisites

Make sure you have Python installed (preferably Python 3.8+). You'll also need `pip` for package management.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Rpvermaak/BeanVoyage-Project.git](https://github.com/Rpvermaak/BeanVoyage-Project.git)
    cd BeanVoyage-Project
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
    *(If you don't have a `requirements.txt` yet, you can generate one after installing all necessary packages in your environment using `pip freeze > requirements.txt`)*

## 📊 Usage

Once you have installed the dependencies, you can run the Jupyter Notebook:

1.  **Start Jupyter Lab or Jupyter Notebook:**
    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```

2.  **Open `BeanVoyage_Project.ipynb`:**
    Navigate to the `BeanVoyage_Project.ipynb` file in the Jupyter interface and open it.

3.  **Run the cells:**
    Execute the cells sequentially to see the data analysis, model training, and results unfold.

## 📁 Data

This project utilizes two primary datasets:

* **`beanvoyage_customer_data.csv`:** Contains information about individual customers, including `customer_id`, `join_date`, `subscription_plan`, `monthly_spend_usd`, `last_purchase_date`, `customer_lifetime_value_usd`, `email_engagement_score`, `churned` (boolean), `churn_date`, and `survey_feedback_reason`.
* **`beanvoyage_subscription_order_data.csv`:** Contains detailed order information, including `order_id`, `customer_id`, `order_date`, `product_type`, `item_count`, and `order_value_usd`.

These datasets are merged based on `customer_id` to create a comprehensive `final_customer_df` for analysis.

## 📈 Results & Insights

The analysis provides valuable insights into BeanVoyage's customer base and churn behavior:

* Approximately **38% of customers have churned**.
* The primary reasons for churn identified from survey feedback are **"Price Too High"** and **"Trying Another Service."** Other reasons like "Not Drinking Enough," "Delivery Issues," "Too Much Coffee," "Wants More Variety," and "Found Local Roaster" also contribute.
* Customers on the **"Basic" subscription plan have the highest churn rate (57.14%)**, followed by "Standard" (40.74%). Notably, the "Premium" plan shows **0% churn** in this dataset, indicating high loyalty among premium subscribers.
* Visualizations provide a clear understanding of the distribution of numerical features like `monthly_spend_usd`, `customer_lifetime_value_usd`, and `email_engagement_score`.

## 🛠️ Technologies Used

* **Python:** The primary programming language.
* **Jupyter Notebook:** For interactive development and presentation.
* **Pandas:** For robust data manipulation and analysis.
* **NumPy:** For efficient numerical operations.
* **Matplotlib / Seaborn:** For creating compelling data visualizations.
* **Scikit-learn:** (Potentially for future modeling, though not explicitly detailed in the provided content for model building).

## 🤝 Contributing

Contributions are always welcome! If you have suggestions for improvements, new features, or find any bugs, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
5.  Push to the branch (`git push origin feature/AmazingFeature`).
6.  Open a Pull Request.

## 📄 License

This project is licensed under the  MIT License. See the `LICENSE` file for details.

## 📧 Contact

If you have any questions, feel free to reach out!

* **Your Name:** [Ruben Vermaak/Rpvermaak]
* **GitHub Profile:** [[Profile](https://github.com/Rpvermaak)]
* **Email:** [rpvermaak123@gmail.com]

---

Thank you for exploring the BeanVoyage Project! Enjoy the journey through data!
