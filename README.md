# Mushroom Classification Predictor using Decision Tree and Flask
This machine learning project utilizes physical characteristics of mushrooms to predict whether they are edible or poisonous. Featuring models like Decision Tree, the code evaluates their predictive performance on a dataset of mushroom attributes.

## Dataset Overview
The dataset includes the following features to determine if a mushroom is edible or poisonous:

- Cap shape, Cap surface, Cap color
- Bruises, Odor
- Gill attachment, Gill spacing, Gill size, Gill color
- Stalk shape, Stalk root, Stalk surface above/below ring
- Stalk color above/below ring, Veil type, Veil color
- Ring number, Ring type, Spore print color
- Population, Habitat

Missing values were handled and categorical data were encoded using `LabelEncoder`. The dataset was preprocessed for optimal model training.

## Model Training and Evaluation
After preprocessing, including encoding features:

- A Decision Tree Classifier was trained.
- Model performance was evaluated using accuracy, precision, recall, and F1 score.

### Results Summary
- The Decision Tree achieved an accuracy of approximately 99.25%.
- Detailed performance metrics are available in the classification report and confusion matrix.

## Usage
To replicate the analysis:

- Clone the repository.
- Ensure all dependencies are installed.
- Run the Flask app to interact with the model through a web interface.

For more details, see the provided Jupyter notebooks and Flask application scripts.

## Contact
For inquiries or contributions, please contact [spomar36@gmail.com](mailto:spomar36@gmail.com).

## Production Services
To ensure our mushroom classification model operates seamlessly in a production environment, we leverage the following cloud services and ML operations practices:

### AWS
- **Amazon S3**: Store and retrieve any amount of data at any time.
- **AWS Lambda**: Run code in response to data changes in S3 buckets.
- **Amazon SageMaker**: Train, tune, and deploy the machine learning models.

### Azure
- **Azure Blob Storage**: For large-scale data storage.
- **Azure Functions**: Event-driven compute for data processing.
- **Azure Machine Learning Service**: Build, train, and deploy models.

### GCP
- **Google Cloud Storage**: Durable and scalable object storage.
- **Cloud Functions**: Serverless execution of functions in response to cloud events.
- **AI Platform**: End-to-end machine learning model lifecycle management.

### ML Operations
- **Continuous Training**: Implement pipelines to retrain models with new data.
- **Data Validation**: Use services like AWS Data Pipeline or Azure Data Factory for data integrity checks.
- **Model Monitoring**: Track model performance and data drift to maintain accuracy over time.

These services ensure our model stays updated, scalable, and maintainable, with robust ML operations that support continuous improvement.

## Quickstart

```bash
git clone https://github.com/GOSS-hash/ml-webapp-using-flask

