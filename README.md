### Date created
March 17th, 2020.

### Explore US Bishare Data
![divvy](https://user-images.githubusercontent.com/49973760/76811158-8cdbb680-6816-11ea-8835-43f1e635ccda.jpg)

### Description
In this project, made use of Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. Written code to import the data and answer interesting questions, by computing descriptive statistics. Also written a python script that takes in raw input to create an interactive experience in the terminal to present these statistics.

### Project overview:
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, you will use data provided by [Motivate](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

### Files used
The files (data) used to explore the project and also included in the execution of the python scripts are:
 * [chicago.csv](https://www.divvybikes.com/system-data)
 * [new_york_city.csv](https://www.citibikenyc.com/system-data)
 * [washington.csv](https://www.capitalbikeshare.com/system-data)

### The Dataset:
All three of the data files contain the same core six (6) columns:
* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Station (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:
* Gender
* Birth Year

### Statistics Computed:
Analyzed the data related to bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, written code to provide the following information:

##### 1. Popular times of travel (i.e., occurs most often in the start time):
* most common month
* most common day of week
* most common hour of day

##### 2. Popular stations and trip:
* most common start station
* most common end station
* most common trip from start to end (i.e., most frequent combination of start station and end station)

##### 3. Trip duration:
* total travel time
* average travel time

##### 4. User info:
* counts of each user type
* counts of each gender (only available for NYC and Chicago)
* earliest, most recent, most common year of birth (only available for NYC and Chicago)

### Technologies Used:
+ **Python**
    > Used Python programming language to explore data related to bikeshare.

+ **Numpy and Pandas**
    > Used to explore and manipulate DataFrames and performed statistical analysis.

+ **Visual Studio Code**
    > Used to make exploratory analysis and write appropriate SQL queries to answer the posed questions.

+ **Git Version Control**
    > Used to control and record the project files. Shared the work on GitHub profile.

## Software requirements:
To complete this project, the following software requirements apply:
* You should have Python 3, NumPy, and pandas installed using Anaconda
* A text editor, like Sublime or Atom.
* A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

### Credits
My sincere thanks to the [Udacity](https://www.udacity.com/) platform for providing the [Programming for Data Science with Python Nanodegree](https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104) program. 

I also would like to acknowledge the credit to the instructors that inspired me and guided me through out this course:

 * Richard Kalehoff, Instructor
 * Juno Lee, Curriculum lead at Udacity
 * Josh Bernhard, Data scientist at Nerd wallet
 * Derek Steer, CEO at Mode Analytics
 * Karl Krueger, Command line instructor

