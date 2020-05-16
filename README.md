# Python_bot-covid-19-Tracker
Track covid-19 and get customized notification.


![Start](https://github.com/upa-mihir07/Python_bot-covid-19-Tracker/blob/master/Screenshot%20(958).png)

## Installation
* Python
* Slack account + slack webhook to send your notification to slack account
* Install dependencies 
  - pip install tabulate.
  - pip install requests.
  - pip install beautifulsoup4.
  
* Clone this repo
  > git clone https://github.com/upa-mihir07/Python_bot-covid-19-Tracker.git

* Make a new *auth.py* in the directory where you cloned this repo.
* Write your slack Webhook into auth.py
  > DEFAULT_SLACK_WEBHOOK = 'https://hooks.slack.com/services/your custome webhook url'

* Set-up Task Scheduler on Windows
  - To autamate your python script. It will run continously as customized. 
  
  
#### Setting up Task Schedular
* For windows 
  > [Link to go](https://towardsdatascience.com/automate-your-python-scripts-with-task-scheduler-661d0a40b279)
* For linux
  > [Link to go](https://www.howtogeek.com/101288/how-to-schedule-tasks-on-linux-an-introduction-to-crontab-files/)
###### Whenever the change in the data occured you will get notification.
You can receive data on mobile too.

![Start](https://github.com/upa-mihir07/Python_bot-covid-19-Tracker/blob/master/noti.jpeg)
![Start](https://github.com/upa-mihir07/Python_bot-covid-19-Tracker/blob/master/noti2.jpeg)



"---------------------------------------------------------------------------------------"

## Important Note
  * The Source of the data is Worldometer, you cn check it [here](https://www.worldometers.info/coronavirus/#countries)
  * If the format of the site changes !!!
    > Don't worry you'll get exception notification on slack too. *Check bot.log for exception and handle it accordingly*
  
