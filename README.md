# Automated Parking System using ML

### Statement: "Design and Develop a automated parking system using ML , use pictures to detect the car numbers and allocate a parking spot "

#### Goal: Understand image detection of car number plate recognition and improve the accuracy.


Steps for execution :

1)install python, xampp, anaconda.

2)Save all the python scripts and images folder in 'xampp->mysql->bin' location.

3)Start mysql and apache in xampp.

4)Open anaconda->create an new environment (just once)->open through terminal->activate anaconda using 'conda activate your_env_name'->install all the libraries required(just once)->change the directory in same terminal ex: cd C:\xampp\mysql\bin->(just once)Create car database with slot,duration, entry, exits, cost tables. Use mysql -u root in command prompt->run your script using 'python detection.py'->use control keys to detect the license plate number of the next image 

5)Libraries required: mysql.connector, PyQt5,easyocr,opencv-python-headless, imutils, pandas.
use the following commands to install the above libraries

pip install mysql-connector-python
pip install PyQt5
pip install easyocr
pip install opencv-python-headless  
pip install imutils
pip install pandas







