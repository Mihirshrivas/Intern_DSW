steps to perform the task is :
Step 1: Setting Up Your Environment:
# Create a virtual environment
python3 -m venv myenv

# Activate the virtual environment
source myenv/bin/activate

# Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn

Step 2:  Data Understanding

Step 3: Exploratory Data Analysis (EDA)

Step 4: Modeling

Step 5 : Model Selection

# Resources Used:
 - Chat-GPT
 - Google Search
 -Devfolio website
 -Research  paper




# Products-Top-Flop-Prediction
A fashion e-commerce company is planning its collections for the upcoming year. Therefore the company put together many potential products as candidates and now would like to estimate which products would be successful (top) or not (flop). To do so, you are provided with data on the past years’ top and flop products. This will allow us to create a small machine-learning application.

### Data Overview (shared in separate files)
Historic data: Contains attributes of products from the past two years, including the success indicator label. File: historic.csv (8000 products)
Prediction data: Contains attributes of potential products for the upcoming year without the success label. File: prediction_input.csv (2000 product candidates)



### Columns:
Item_no: Internal identifier for past or future products.
category: Category of the product.
main_promotion: Main promotion used or planned for the product.
color: Main color of the product.
stars: Review rating from a comparable product (0 to 5 stars).
success_indicator: Indicator of past success (top) or failure (flop). Only available for historic data

## Technical Requirements
▪ EDA:
Perform EDA and submit in a notebook named “eda.ipynb”.
For each analysis/chart code block add a comments markdown block.
▪ Modeling:
-
Prepare the training pipeline and submit it in a script named “model_<model_name>.py”.
Where <model_name> is the model algorithm you are using. Create at least two different
models and corresponding model files, one of them must be an artificial neural network (ann)
model.

