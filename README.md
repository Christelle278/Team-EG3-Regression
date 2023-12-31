# Disaster Preparedness and Resilience Planning with Intelli Data

![Intelli Data!](https://media.discordapp.net/attachments/1168555810721382481/1174317128040579122/Logo_2.png?ex=6567270d&is=6554b20d&hm=ab21c2440ea1fb5cc8f3542c86173a96fc45aaa2e305b94747f2deefaf6cf676&=&width=312&height=312)

## Introduction

Welcome to the Disaster Preparedness and Resilience Planning project, in collaboration with Intelli Data. Our mission is to assist a disaster management agency in enhancing their preparedness for extreme weather events, which can significantly impact energy supply systems. We will be using advanced data analysis and predictive modeling to anticipate energy shortfalls during severe weather occurrences, such as storms, heavy snowfall, or heat waves. Accurate predictions will empower the agency to proactively allocate resources, prioritize affected regions, and deploy emergency response teams. This, in turn, ensures minimal disruption and enhances the resilience of energy supply systems during natural disasters.

## Project Overview

The supply of electricity is vital to the livelihood of citizens in a country. Electricity not only keeps us connected but also plays a crucial role in keeping us warm and ensuring the well-being of our families. However, recent evidence suggests that relying solely on non-renewable energy sources is unsustainable. The government of Spain recognizes the need to invest in renewable energy infrastructure to improve the standard of living and reduce environmental impact.

To support the government of Spain's initiative, this project focuses on modeling the energy shortfall between fossil fuels and renewable sources in the country. The daily shortfall, our target variable, will be modeled as a function of various city-specific weather features, such as pressure, wind speed, humidity, and more.

## Objective

The primary objective of this project is to create predictive models that help the disaster management agency and the government of Spain:

- Anticipate energy shortfalls during extreme weather events.
- Proactively allocate resources to minimize disruptions.
- Prioritize affected regions for efficient disaster response.
- Enhance the resilience of energy supply systems during natural disasters.
- Support the government's renewable energy infrastructure investments.

## Data Sources

We will be using detailed meteorological data, past records of energy load shortfalls during adverse weather conditions, and city-specific weather features to achieve our objectives. Our analysis and modeling will provide valuable insights to make informed decisions and ensure the sustainability of energy supply in Spain.

## Project Team
- Team Leader: Christelle Coetzee
- Project Manager: Mashako Justice Manyelo
- Team Members:
- Data Scientist: Destiny Owobu
- Data Analyst: Edidiong Udofia
- Data Scientist: Anthonia Omonayin
- Data Scientist: Pricilla Vhafuniwap

## Dataset
### Data Source: The dataset contains historical data related to energy generation and weather features for various cities in Spain:
- Barcelona
- Bilbao
- Madrid
- Seville
- Valencia
![Spain!](https://www.thoughtco.com/thmb/r4-HE4WH88Cu3V7Vs-EN3v0SJWs=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/200551095-001-58b9d1215f9b58af5ca84ba0.jpg)
### Data Columns
- time: Timestamp for the data entry.
- wind_speed
- wind_deg
- rain_1h
- humidity
- clouds_all
- pressure
- snow_3h
- rain_3h
- weather_id
- temp_max
- temp
- min
- load_shortfall_3h: The daily energy shortfall, which is the target variable.

## Project Objective
The primary objective of this project is to develop a regression model that predicts the daily energy shortfall in Spain based on the provided weather and city-specific data.

## Project Deliverables
### Data Preprocessing:

Clean and preprocess the dataset, handling missing values, and encoding categorical variables as necessary.

### Exploratory Data Analysis (EDA):

Conduct EDA to understand the relationships between weather features, energy generation, and the energy shortfall.

### Feature Engineering:

Create new features if necessary and select relevant features for modeling.

### Model Building:

Develop and train a regression model to predict the daily energy shortfall using the selected features.

### Model Evaluation:

Evaluate the model's performance using appropriate metrics such as mean squared error, mean absolute error, and R-squared.

### Model Deployment:

Deploy the trained model for making predictions on new data.

### Documentation:

Create documentation that explains the data, methodology, and model for future reference.

### Project Timeline

The project will be conducted in phases, with each phase having specific tasks and deadlines. The timeline for the project will be determined by the project manager in consultation with the team members.

### Data Volume

The dataset contains nearly 8762 rows, and its size may impact data processing and model training times. Appropriate hardware and software resources will be allocated to handle this volume effectively.

### Collaboration

The project team will collaborate closely to ensure the successful completion of each phase. Communication channels will be established to facilitate teamwork and knowledge sharing.

### Conclusion

The successful modeling of the daily energy shortfall in Spain will provide valuable insights for the government's renewable energy infrastructure investments, contributing to a more sustainable and reliable energy supply for the citizens.

## Contact Information

For any inquiries or updates related to this project, please feel free to reach out to the following team members:

- **Project Manager:** Mashako Justice Manyelo
  - Email: [manyelojustice@gmail.com](mailto:manyelojustice@gmail.com)

- **Team Leader:** Christelle Coetzee
  - Email: [christellecoetzeepp@gmail.com](mailto:christellecoetzeepp@gmail.com)

- **Team Members:**
  1. Destiny Owobu
     - Email: [apogeeden@gmail.com](mailto:apogeeden@gmail.com)

  2. Edidiong Udofia
     - Email: [edidiongudofia5050@gmail.com](mailto:edidiongudofia5050@gmail.com)

  3. Tony Onyeka
     - Email: [toniaomonayin@gmail.com](mailto:toniaomonayin@gmail.com)

  4. Pricilla Vhafuniwap
     - Email: [vhafuniwap@gmail.com](mailto:vhafuniwap@gmail.com)

### Trello Board
You can also follow the progress of this project on our Trello board:
- [Trello Board](https://trello.com/invite/b/obu1pWbR/ATTI28571aed72d8beface33cefbef752fb32623C995/regressionsprint2307acdsteameg3)

### Presentation Slides

You can view our presentation slides [here](https://www.canva.com/design/DAFqMlMqwrk/u_lL2OatH1sFgnpLHQQnVQ/edit?utm_content=DAFqMqwrk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

### GitHub Repository

You can access our GitHub repository [here](https://github.com/Christelle278/Team-EG3-Regression.git).

### Requirements

Please advise the requirements folder in order to see what packages and versions of packages you will need to run this notebook: https://github.com/Christelle278/Team-EG3-Regression/blob/main/Requirements.txt

Feel free to contact us if you have any questions, suggestions, or updates related to this project.



