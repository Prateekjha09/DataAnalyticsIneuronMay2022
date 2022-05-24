
# Indian Edtech startups Analysis report:
Educational technology (Ed-Tech)  refers to a wide range of teaching and learning-related software and hardware that is increasingly being used in college and university classrooms. The ultimate purpose of educational technology, commonly known as Ed Tech, is to provide a better learning environment, which in turn is intended to improve student results. It's also been shown to boost student involvement and participation in class.

Educational technology (Ed-Tech) is a technology that typically aids in the facilitation of cooperation in an active learning setting. Educators can use educational technology to develop digital, interactive textbooks, gamify courses, take attendance, assign homework, hold quizzes and assessments, and receive real-time results linked to teaching subject, style, and format. Traditional education and teaching methods are being disrupted by educational technology, which allows both teachers and students to learn in an environment that makes use of now-common gadgets such as smartphones, computers, and tablets.

![image](https://user-images.githubusercontent.com/49709510/170094839-bb66d383-336e-4395-b06a-ddf1b9be5b0b.png)



## Dataset:
Use think [link](https://raw.githubusercontent.com/PacktPublishing/Data-Visualization-Solutions-for-Beginners-/master/Section%206/Data/startup_funding.csv) to access the open source dataset used in this project.

## Installation:

Install Microsft Power BI desktop from [here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

Setup MySQL database for your local instance server for storing csv data using this [location](https://dev.mysql.com/downloads/installer/)

Any version of Python 3.6 or above will work comfortably for this project.

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
Please check out HLD, LLD and wireframe documents uploaded in repository for more information on this report architecture.

## Steps to be followed for cloning this report:

1. Run the first cell script named LoadingData.ipynb
2. Open up Microsoft Power BI desktop in your local setup.
3. Click on <b> Get Data </b> option , search for more connectors and select MySQL database
4. When prompted, add server name as "localhost", database as crime_data(which I created for me ofcourse, not a very name to understand!) and username as root, password which your created for you local instance.
5. Import the required table in Power BI desktop or you could with some data cleaning in Power Query editor using "Transform Data" instead of "Load Data".
6. Create calculated columns and measures based on your need, apply the best suited visuals and you're done.
7. Following are the measures that we used in our current report:
![image](https://user-images.githubusercontent.com/49709510/170095096-7d9154c5-0bec-4c4c-aca4-092b89669475.png)


8. Just an additional step if sharing is required, you can login to Power BI service with a professional email account and publish it a workspace assigned on your name. For this you can find plenty of resource on how to do so!!

I hope this helps any one out these Cheers.
Please feel free to reach out to me if any changes/ suggestions/ updates that you want in this report on my <b>jha09prateek@gmail.com</b>

## Contributors
- Prateek Jha









