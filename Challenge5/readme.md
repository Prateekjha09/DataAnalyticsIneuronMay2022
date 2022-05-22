
# Crime Analysis report:

In India, the restaurant industry is booming. Currently, the Indian Restaurant Market is one of the most rapidly expanding in the globe. According to a survey by the National Restaurant Association of India (NRAI), the Indian restaurant industry is predicted to reach INR 5.99 lakh crore by 2022-23, rising at a compounded annual growth rate of 9 percent. Despite the difficulties and problems that restaurant owners have experienced in recent years, operating a restaurant in the near future would open the door to a slew of new chances for aspiring restaurant entrepreneurs.

## Tasks involved:
Organically collect data from multiple restaurants and franchise outlets, and get insights about the real challenges involved in the operations in the hospitality industry. 
Research about different types of restaurants and perform an in-depth analysis of the data thus collected, in order to help a business owner understand the key performance metrics for a restaurant business to flourish as per current market demands.
Perform a SWOT analysis for the restaurant and report your findings.

![image](https://user-images.githubusercontent.com/49709510/169707035-09ff7c39-ff7c-4b85-8a2a-19bb46f7ec35.png)



## Dataset:
Use think [link](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants) to access the open source dataset used in this project.

## Installation:

Install Microsft Power BI desktop from [here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

Setup MySQL database for your local instance server for storing csv data using this [location](https://dev.mysql.com/downloads/installer/)

Any version of Python 3.6 or above will work comfortably for this project.

A library called 'sqlalchemy' is used for database related operations using python and it's dataframe
```python
pip install alchemy
pip install pymysql # optional installation needed
```

To import any custom theme in Power BI, you need to create a custom .json file which I created too and use the following code snippet to create a custom theme for Power BI which is imported later in Power BI desktop but it completely depends on an individual if one wants to add a custom theme for a report
```json
{"name":"MyTheme"

,"visualStyles":{"page":{"*":{"background":
    [
     {
                        "image": {
                            "name": "MyBackground",
                            "scaling": "Fill",
                            "url": "image's base 64 link"
                        },
                        "transparency": 10
                    }
    ]
   }
  }
 }
}
```
You can convert any image to it's base64 version using this link: https://www.base64-image.de/

Upload any selected image , and once it is done select the option <b> Copy Image</b> and we will get a base64 link to desired image we want in theme for Power Bi, copy that link and paste in "url" value and save it. The file which is currently implementing the same is <b>MyTheme.json</b> .


## Setup:
Open up anaconda powershell prompt and install

1. SQLAlchemy
```python
$ pip install sqlalchemy
```

2. pymysql
```python
$ pip install pymysql
```

3. Install MySQL database using this [link](https://dev.mysql.com/downloads/installer/)

4. Install some drivers for connecting Power BI to MySQL database by using [this](https://www.mysql.com/products/connector/)
![image](https://user-images.githubusercontent.com/49709510/168513242-26eef5f6-f293-4b5c-ad5c-48802822b556.png)

Install the above two and you're done!
NOTE: Keep in the password for root user handy that you created while installing MySQL database.

## For more info:
Please check out HLD, LLD and wireframe documents uploaded in repository

## Steps to be followed for cloning this report:

1. Run the first cell script named LoadingData.ipynb
2. Open up Microsoft Power BI desktop in your local setup.
3. Click on <b> Get Data </b> option , search for more connectors and select MySQL database
4. When prompted, add server name as "localhost", database as crime_data(which I created for me ofcourse, not a very name to understand!) and username as root, password which your created for you local instance.
5. Import the required table in Power BI desktop or you could with some data cleaning in Power Query editor using "Transform Data" instead of "Load Data".
6. Create calculated columns and measures based on your need, apply the best suited visuals and you're done.
7. Just an additional step if sharing is required, you can login to Power BI service with a professional email account and publish it a workspace assigned on your name. For this you can find plenty of resource on how to do so!!

I hope this helps!! Cheers.

## Contributors
- Prateek Jha









