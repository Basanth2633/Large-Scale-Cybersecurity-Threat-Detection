Large-Scale Cybersecurity Threat Detection:
As cyberattacks become increasingly advanced, traditional intrusion detection systems often struggle to manage the scale and complexity of modern network traffic. To overcome these challenges, we developed scalable detection models using the UNSW-NB15 dataset, which mirrors real-world attack scenarios. Utilizing PySpark for distributed computing, we carried out data preprocessing, feature selection, and trained various machine learning models including Decision Trees, Naïve Bayes, Random Forest, and Gradient Boosting. Among these, Gradient Boosting achieved the highest accuracy at over 94%. Additionally, we integrated a Deep Q-Network (DQN) approach for dynamic adaptability, reaching 96% accuracy. Our system enables efficient, real-time processing of large-scale data, significantly reducing false positives and enhancing threat detection. Future directions include fine-tuning hyperparameters, deploying the models in live environments, and exploring deep learning techniques for improved robustness and adaptability.

📊 Dataset:
UNSW-NB15 dataset, designed to simulate real-world cyberattacks.

Includes rich features like protocol, service type, source/destination IPs, flags, and flow attributes.

Both training and testing sets were used for model evaluation.

⚙️ Tech Stack and Tools:
PySpark: Used for distributed data processing and machine learning pipeline creation.

Jupyter Notebook (final_code.ipynb): Code implementation environment.

ML Libraries: Spark MLlib and Python-based tools.

🧹 Data Processing:
Preprocessing: Cleaning, handling missing values, and encoding categorical variables.

Feature Selection: Selected relevant attributes to improve model efficiency and accuracy.

🤖 Models Implemented:
Decision Tree

Naïve Bayes

Random Forest

Gradient Boosting — achieved best performance with over 94% accuracy

DQN (Deep Q-Network) — integrated for dynamic adaptability, achieving 96% accuracy

⚡ Key Achievements:
Real-time, large-scale data handling through distributed computing.

Significant reduction in false positives.

High accuracy and adaptability to evolving threats.

🔍 Future Enhancements:
Hyperparameter tuning for all models.

Real-world deployment in live environments.

Integration of advanced deep learning methods to improve system robustness and adaptability.

