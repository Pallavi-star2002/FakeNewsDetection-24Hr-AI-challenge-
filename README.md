# FakeNewsDetection-24Hr-AI-challenge-
Build AI fake news detection using machine learning

https://kandi.openweaver.com/collections/techforgood2022/spotting-fake-news

**Kit Deployment Instructions**

For Windows OS,

  Download, extract and double-click the kit installer file to install the kit.

  **Note: Do ensure to extract the zip file before running it. The installation may take from 2 to 10 minutes based on bandwidth.**

  1. When you're prompted during the installation of the kit, press Y to launch the app automatically and execute cells in the notebook by selecting Cell --> Run All from Menu bar
  2. To run the app manually, press N when you're prompted and locate the zip file 'kit_installer.zip'
  3. Extract the zip file and navigate to the directory 'fake-news-detection-main'
  4. Open command prompt in the extracted directory 'fake-news-detection' and run the command 'jupyter notebook'
  
**For other Operating System**,

  1. Click here to install python
  2. Click here to download the repository
  3. Extract the zip file and navigate to the directory 'fakenews-detection-main'
  4. Open terminal in the extracted directory 'fakenews-detection-main'
  5. Install dependencies by executing the command 'pip install -r requirements.txt'
  6. Run the command ‘jupyter notebook’ and select the notebook ‘FakeNewsdetection-starter.ipynb’ on the browser window.
Instructions to Run

**Follow the below instructions to run the solution.**

  1. Locate and open the FakeNewsDetection-starter.ipynb notebook from the Jupyter Notebook browser window.
  2. Execute cells in the notebook by selecting Cell --> Run All from Menu bar
  3. Once all the cells of the notebook are executed, the prediction result will be written to the file 'fake_news_test_output.csv'

**Training with your dataset:**
1. Add news articles to a csv file under a column name 'news_text'.
2. Add corresponding labels as 'real' or 'fake' denoting whether a news article is real or not.
3. You can refer to the file 'fake_news_train.csv' for an example.
4. Set the variable for training file in the notebook under Variables section.

**Testing with your dataset:**
1. Add news articles to a csv file under a column name 'news_text'.
2. You can refer to the file 'fake_news_test.csv' for an example.
3. Set the variable for testing file in the notebook under Variables section.

You can execute the cells of notebook by selecting Cell from the menu bar.
