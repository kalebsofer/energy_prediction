# energy_prediction
An approach to predicting energy consumption, inspiration and data taken from the ASHRAE - Great Energy Predictor III (Kaggle competition)

How much energy will a building consume?

Assessing the value of energy efficiency improvements can be challenging as there's no way to truly know how much energy a building would have used without the improvements. The best we can do is to build counterfactual models. Once a building is overhauled the new (lower) energy consumption is compared against modeled values for the original building to calculate the savings from the retrofit. More accurate models could support better market incentives and enable lower cost financing.

The competition challenges us to build these counterfactual models across four energy types based on historic usage rates and observed weather. The dataset includes three years of hourly meter readings from over one thousand buildings at several different sites around the world.

### Connecting to gcp:
Data for this project was uploaded from kaggle to a GCP bucket.
- gcloud init
- gcloud auth list 
- gcloud config set account kalebsofer@gmail.com
- gcloud config set project PROJECT_ID

### Installing requirements
[PySpark requires Java](https://phoenixnap.com/kb/install-java-macos)

pip3 install -r requirements.txt

