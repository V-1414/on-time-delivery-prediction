This project analyzes supply chain operational data to predict whether an order will be delivered on time. Using classification models such as CART, KNN, Naive Bayes, and Neural Networks, it identifies key delay factors and offers actionable business recommendations.

## 📊 Objective
Build a predictive model to classify orders as **on-time (1)** or **delayed (0)** using features such as order details, supplier performance, production efficiency, and logistics.

## 📁 Dataset Overview
The dataset includes:
- **Order Details**: Volume, priority, lead time  
- **Supplier Performance**: On-time % and quality rating  
- **Production**: Machine uptime, defect rate, production time  
- **Inventory**: Stock levels, forecast accuracy  
- **Logistics**: Shipping cost, transport mode, delivery time

Target Variable: `On_Time_Delivery`

## 🧠 Models & Accuracy
| Model            | Accuracy |
|------------------|----------|
| CART             | **85.4%** |
| Naive Bayes      | 84.5%    |
| Neural Network   | 83.4%    |
| KNN              | 83.2%    |

## 🔍 Key Insights
- **Supplier on-time % < 80%** significantly increases chances of delay.
- Even with reliable suppliers, **lead time > 11.5 days** increases risk of late delivery.
- CART outperformed other models in accuracy and interpretability.

## 💼 Business Recommendations
- Prioritize reliable suppliers and incentivize on-time performance.
- Reduce lead time through better inventory control and logistics optimization.
- Use model predictions to proactively mitigate delivery risk via strategic adjustments (e.g., route optimization, supplier diversification).

## 🛠 Tools Used
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- CART (DecisionTreeClassifier), KNN, GaussianNB, MLPClassifier

## 📂 Files Included
- `on_time_delivery.ipynb`: Complete code and analysis
- `slides.pdf`: Summary presentation with methodology, results, and recommendations

## 📌 Author
Vidhi Sikarwar | Undergraduate Economics Student | Ashoka University  
