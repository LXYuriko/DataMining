# 数据集选择

## 1 [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)

### Description
#### Context
After watching Somm (a documentary on master sommeliers) I wondered how I could create a predictive model to identify wines through blind tasting like a master sommelier would. The first step in this journey was gathering some data to train a model. I plan to use deep learning to predict the wine variety using words in the description/review. The model still won't be able to taste the wine, but theoretically it could identify the wine based on a description that a sommelier could give. If anyone has any ideas on how to accomplish this, please post them!

#### Content
This dataset contains three files:

winemag-data-130k-v2.csv contains 10 columns and 130k rows of wine reviews.

winemag-data_first150k.csv contains 10 columns and 150k rows of wine reviews.

winemag-data-130k-v2.json contains 6919 nodes of wine reviews.

Click on the data tab to see individual file descriptions, column-level metadata and summary statistics.

#### Acknowledgements
The data was scraped from WineEnthusiast during the week of June 15th, 2017. The code for the scraper can be found here if you have any more specific questions about data collection that I didn't address.

UPDATE 11/24/2017
After feedback from users of the dataset I scraped the reviews again on November 22nd, 2017. This time around I collected the title of each review, which you can parse the year out of, the tasters name, and the taster's Twitter handle. This should also fix the duplicate entry issue.

#### Inspiration
I think that this dataset offers some great opportunities for sentiment analysis and other text related predictive models. My overall goal is to create a model that can identify the variety, winery, and location of a wine based on a description. If anyone has any ideas, breakthroughs, or other interesting insights/models please post them.

## 2 [Chicago Building Violations](https://www.kaggle.com/chicago/chicago-building-violations)

### Description
#### Content
Violations issued by the Department of Buildings from 2006 to the present. Lenders and title companies, please note: These data are historical in nature and should not be relied upon for real estate transactions. For transactional purposes such as closings, please consult the title commitment for outstanding enforcement actions in the Circuit Court of Cook County or the Chicago Department of Administrative Hearings. Violations are always associated to an inspection and there can be multiple violation records to one inspection record. Related Applications: Building Data Warehouse http://www.cityofchicago.org/city/en/depts/bldgs/provdrs/inspect/svcs/building_violationsonline.html. The information presented on this website is informational only and does not necessarily reflect the current condition of the building or property. The dataset contains cases where a respondent has been found to be liable as well as cases where the respondent has been found to be not liable.

#### Context
This is a dataset hosted by the City of Chicago. The city has an open data platform found here and they update their information according the amount of data that is brought in. Explore the City of Chicago using Kaggle and all of the data sources available through the City of Chicago organization page!

Update Frequency: This dataset is updated daily.
#### Acknowledgements
This dataset is maintained using Socrata's API and Kaggle's API. Socrata has assisted countless organizations with hosting their open data and has been an integral part of the process of bringing more data to the public.

Cover photo by Cristina Gottardi on Unsplash
Unsplash Images are distributed under a unique Unsplash License.
