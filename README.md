# Robo Advisor

Challenge 15


> "In this Challenge, I combine my new AWS (Amazon Web Services) skills with existing Python superpowers to create a bot that will recommend an investment portfolio for a retirement plan
"



## Table of content
- [Overview of the project and project goals](https://github.com/ShengGaoSG/Robo_Advisor#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/ShengGaoSG/Robo_Advisor#software-version-control)
    - [Libraries](https://github.com/ShengGaoSG/Robo_Advisor#libraries)
    - [Work with GitHub](https://github.com/ShengGaoSG/Robo_Advisor#work-with-github)
    - [How to install](https://github.com/ShengGaoSG/Robo_Advisor#how-to-install)
- [License](https://github.com/ShengGaoSG/Robo_Advisor#license)



## Overview of the project and project goals

Using the power of machine learning and NLP to disrupt finance and improve the customer experience, we are creating a robo advisor. Both existing and potentially new customers will be able to use this robo advisor to get investment portfolio recommendations for retirement.

Following main tasks were accomplished:

  1. Configure the initial robo advisor: Define an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.

  2. Build and test the robo advisor: Make sure that your bot works and accurately responds during the conversation with the user.

  3. Enhance the robo advisor with an Amazon Lambda function: Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.



 



## Software version control

Amazon Lex is used to create the bot

### Step 1: Initiate the bot

<img width="742" alt="Screen Shot 2021-07-05 at 12 25 15 PM" src="https://user-images.githubusercontent.com/80833988/124686468-0e31df00-de88-11eb-86b6-8694b0b56d53.png">

### Step 2: Create the intent

<img width="844" alt="Screen Shot 2021-07-05 at 12 36 39 PM" src="https://user-images.githubusercontent.com/80833988/124686569-391c3300-de88-11eb-8b29-2896ae16589b.png">

### Step 3: Create Lambda

Amazon Lambda is used to enhance original bot

<img width="864" alt="Screen Shot 2021-07-06 at 6 32 21 PM" src="https://user-images.githubusercontent.com/80833988/124686760-83051900-de88-11eb-98c2-3b314725d635.png">

### Step 4: Test Lambda

You can find Test Files in the repo in separate folder. On the following picture "negative age" mistake was tested and code passed.

[
<img width="809" alt="Screen Shot 2021-07-06 at 9 02 56 PM" src="https://user-images.githubusercontent.com/80833988/124698345-8ce54700-de9d-11eb-8c0c-5ddfef0f60de.png">
](url)


### Step 5: Deploy Lambda

<img width="691" alt="Screen Shot 2021-07-06 at 6 31 25 PM" src="https://user-images.githubusercontent.com/80833988/124686672-623cc380-de88-11eb-905f-3616e0e6a1fc.png">

### Libraries 

* Following libraries were imported

```
# Import the required libraries and dependencies

from datetime import datetime
from dateutil.relativedelta import relativedelta
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* File with code for Lambda function included lambda_function.py


### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/ShengGaoSG/Robo_Advisor.git
```

now you can find repo on your desktop


* Choose [ lambda_function.py ] file to see the code for Enhanced Robo Advisor.






## License

MIT


Contact me: 
sheng_gao@outlook.com
