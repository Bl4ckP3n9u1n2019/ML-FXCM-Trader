ML Prediction for FXCM trading with a connection to a live demo account.
You will need to input your own access token and set your own paramters for optimisation on the funds / margin base on what is in your account and the buy / sell range.
So far to get better results, use a larger percentage of the funds / margin in your account.

I do not have the latest a greatest latop to run this from so start to finish in live testing is not the quickest.
The best I have managed is 6 minutes.

## Work In Progress
This will connect to a demp account and I am still working on a way to execute a trade after the ML prediction is finished.

I am new to Python and coding is a bit messy as it is 50/50 being developed to run as a .py and testing it on Digital Ocean at the same time.

### The Theory
This is being tested to compute 15 minute bars and trade on the output of the ML prediction. The time to take to predict would increase thus able to use 10, 5 or even 1 minutes bars to exetute a trade within these given bar timings.
Futher development options are listed below.

### Almost complete

I am sure there is someone out there who is able to provide an answer which is to generate the next predictive output.

Ideas I am looking at further developmetn of this project is save this the data output from the live ticker to a table and append with each new update. However, in the interest of time (as we know it's the race to Zero), this could take up that fraction second more.

The printed output I am looking to do after a time limit has been reached as I will look at running this during certian times and I will want to see the results later.

A stop / loss disconnection is going to be implemented, this could be based just 'making enough money for one day of trading' or if you simply lose too much money from  your account. At the moment I am looking at just running this on a timer just to test the implementation of this.

#### Finally, feel free to reach out to me if you have any questions or suggestions to finish this project.
