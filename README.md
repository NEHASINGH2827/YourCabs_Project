# YourCabs_Project

Overall analysis and implementation plan -
ID - Drop - All values unique

User_ID - Drop - PII - mobile number - we do not use Personal Information Identifiers in machine learning features

vehicle_model_id - transform into is_VMID_12 for if the vehicle model id was 12 or not, since >70% of values are 12

Divide the data into 3 datasets based on travel_type_id, since for different travel types different features are applicable

After dividing the data into 3 subsets, 3 different machine learning models are to be created:

ML Model 1 for travel_type_1
ML Model 2 for travel type_2
ML Model 3 for travel_type_3
