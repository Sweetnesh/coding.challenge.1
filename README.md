## The challenge
---
* Create a new repo, name it by using a GUID generator
* REMOVE ALL the content in this readme, don't put any wording like "prive" or "challenge" so that other candidates cannot search your repo and copy your code.
* Do NOT fork, as other candidates would be able to see your solution easily.
* Create a currency monitoring application
* The code will be run on Ubuntu 14.04 for final review if needed.
* If you are using windows, find a way to code and test before submission.


## Goal
---
Create a currency monitoring Web application with the following functional requirements:
---
1. Provide users with the ability to add currencies (Supply simple validation on input for illegal characters or existing currencies)
2. Display the following information for each currencies: symbol, price in HKD, percentage change over the past 1 month. You can use  historical data about currency from the internet, such as from xe.com
3. Provide users with the ability to delete a currency from the list
3. Provide users with the ability to refresh currency calculations
4. Display a timestamp indicating when the last calculation occurred

You MUST use Java and GWT.
Communication to get historical data from the internet MUST be done through the server. 

## Tools you need
---
Here is a minimum list of prerequisites to install (listed in order):
---
1. install JDK, set environment variable JAVA_HOME and add to PATH
	http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
2. install Ant, set environment variable ANT_HOME and add to PATH
	http://ant.apache.org/manual/index.html
3. install GWT
	http://www.gwtproject.org/gettingstarted.html
4. create the sample GWT project and use the StockWatcher tutorial as a starting point:
	http://www.gwtproject.org/doc/latest/tutorial/create.html

Using Eclipse is optional. You can debug the client-side code in Chrome DevTools
	https://developers.google.com/web/tools/chrome-devtools/?hl=en


## Things that will get our attention:
---
1. How quickly you learn GWT and get the challenge done
2. How easy it is for someone else to understand the code you wrote and easily extend the functionality
3. Does your code compile, does it do the job as expected, is it bug-free?
