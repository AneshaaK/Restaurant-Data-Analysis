# Restaurants Data Analysis - Yelp
## Data Visualization
- Project Methodology: CRISP-DM
  - Data Collection : Yelp (https://www.yelp.com/dataset)
    - Leveraged two subsets of dataset: Businesses (business.json) and Check-ins (checkin.json)
  - Data Preparation & Processing:
    - Stored both json files in cloud storage
    - Removed unnecessary columns and approx 1% of missing values using Google Dataprep
    - Created tables in Bigquery with processed data
  - Data Visualization: 
    - Connected to Bigquery in Tableau Desktop
    - Joined both tables and created date fileds, lociation hierarchy and visual tool tips for better view
