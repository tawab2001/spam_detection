# Job Prediction

## Overview
This project predicts job titles and locations based on given skills using machine learning. A dataset containing job titles, locations, and required skills is used to train predictive models.

## Dataset
The dataset consists of job listings with the following features:
- **Title**: The job title.
- **Location**: The geographical location of the job.
- **Skills**: Required skills for the job.

## Project Workflow
1. **Data Preprocessing**
   - Convert skills to lowercase for uniformity.
   - Remove missing values from relevant columns.
2. **Feature Extraction**
   - Use **TF-IDF Vectorization** to transform skills into numerical features.
3. **Model Training**
   - Train a **Random Forest Classifier** to predict job titles.
   - Train another **Random Forest Classifier** to predict locations.
4. **Prediction Function**
   - Predict the most relevant job title and location based on provided skills.
   
## Technologies Used
- **Python**
- **Pandas** for data manipulation.
- **Scikit-learn** for machine learning and vectorization.
- **NumPy** for numerical operations.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd job-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script:
   ```bash
   python job_prediction.py
   ```

## Future Enhancements
- Improve accuracy by fine-tuning the Random Forest model.
- Add support for multiple languages.
- Deploy as a web application.

## Contact
For any inquiries or collaboration, reach out via:
- **Email**: ahmedtawab017@gmail.com
- **LinkedIn**: [Ahmed Tawab](https://www.linkedin.com/in/ahmed-tawab)

### Contributions
Feel free to fork this repository, submit pull requests, and contribute improvements!

