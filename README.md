# Visualzing-Youtube-Data-by-using-Youtube-Api


 Utilizing YouTube API, we extract the data and  also load this data into a Python Pandas DataFrame and then analyze this data. Eventually, we  make simple visualization from this data  utilizing the Python Seaborn library. 

Firstly, we will be creating an YouTube API Key by going to Google Developer Console which will be our credential to access youtube data. We will be using Youtube data API v3. Then create API key.

Once the API Key is generated, then we will use this API key to access different youtube data. 

![image](https://user-images.githubusercontent.com/100124377/229520259-99b75320-0cb9-47e6-b931-9f0df3499ec2.png)

I have created virtual environment by using anaconda then install "google-api-python-client" (which is the google python package required to access youtube api data), also installed pandas and seaborn.

I used Jupyter notebook for writing my puthon code. I have extracted channel details from youtube for Self-Improvement channels like Hamza, Dre-Dexler and many-more then compare these channels data with each other by loading all this data into a pandas dataframe. Also generated some visualization using seaborn python library.
![image](https://user-images.githubusercontent.com/100124377/229523493-4bbdee30-338e-4144-9204-6b9bed189fe2.png)

![Screenshot 2023-04-03 at 9 54 52 PM](https://user-images.githubusercontent.com/100124377/229570944-8ab0bcf1-daac-41da-b957-fd7565a7fe0e.png)

Then we extract details about a particular channel(Hamza) like top 10 videos, most viewed video of the channel and likes. Then we analyzed the data.

![Screenshot 2023-04-03 at 9 56 02 PM](https://user-images.githubusercontent.com/100124377/229571030-32459e6b-9cb1-4372-b659-806f8d71962b.png)

![Screenshot 2023-04-03 at 9 57 34 PM](https://user-images.githubusercontent.com/100124377/229571074-dd0ad41c-b015-4dfa-a49d-0269fbdeb5e4.png)


At last, I loaded all this data of a particular channel(Hamza) from pandas dataframe to a csv file(I also uploaded the csv file on this repository).



Thanks!

