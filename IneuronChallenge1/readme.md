
# Crime Analysis report:

Crime analysis is a law enforcement duty that involves a systematic investigation of patterns and trends in crime and disorder. Pattern information can help law enforcement organizations deploy resources more effectively and aid detectives in locating and apprehending criminals. Crime analysis is also important in developing answers to crime problems and developing crime prevention methods.

Our project will help Baton Rouge Police Department in understanding the current pattern in data available in Power BI visuals and help them to be more aware and eradicate any suspected incidents that might happen in the future within the city at any given address and at any given daytime.

## Dataset:
Use think [link](https://catalog.data.gov/dataset/baton-rouge-crime-incidents) to access the open source dataset used in this project.

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
}```
