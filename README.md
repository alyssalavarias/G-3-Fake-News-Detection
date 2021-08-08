# G-3-Fake-News-Detection

## ModelBuild vs. ModelTest

The **ModelBuild** notebooks are what the group used to process the datasets, separate the articles used for testing and training, build and save the classification models, test model accuracy, and visualize the effectiveness of each model. Running the code in this notebook will overwrite our saved datasets and models.

The **ModelTest** notebooks can be used to load the processed datasets and classification models and visualize the accuracy of the models. The manual_testing function found in the notebook can be used to take text from news articles as input then use our models to predict whether or not the inputted text is real or fake news.

## Limitations

<br>The news content from the learning datasets is primarily composed of specific classifications of news. As such, news tested for legitimacy using this prototype should also be under the same classifications for optimal results. The top 4 largest classifications for the news are: (1) Current Affairs, (2) Politics & Government, (3) International News, (4) Entertainment & Lifestyle.<br><br>

## Reminders
1. Running the code in the ModelBuild notebook will randomize the raw dataset again, which means that the produced model and results may vary significantly from ours. Use the ModelTest notebook to use our model. <br>
2. Unzip all zipped files in the FinalEnglish folder to ensure that the code runs properly.
