# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program

#

# TASK1- BACKGROUND INFORMATION

You’ve been asked to assist with some development to add a chart to a
trader’s dashboard allowing them to better identify under/over-valued
stocks.
The trader would like to be able to monitor two historically correlated stocks
and be able to visualize when the correlation between the two weakens (i.e.
one stock moves proportionally more than the historical correlation would
imply). This could indicate a potential trade strategy to simultaneously buy
the relatively underperforming stock and sell the relatively outperforming
stock. Assuming the two prices subsequently converge, the trade should be
profitable.
Most data visualization for our traders is built on JPMorgan Chase's
Perspective data visualization software, which is now open source. If you
want to explore that, a link is provided in the resources folder.
Before implementing this request using perspective, first, you’ll need to
interface with the relevant financial data feed and make the necessary
adjustments to facilitate the monitoring of potential trade opportunities
#
# TASK BRIEF

For the first task of this project you will need to accomplish the following:
1. Set up your local dev environment by downloading the necessary files,
tools and dependencies.
2. Fix the broken client data feed script in the repository by making the
required adjustments to it.
3. Generate a patch file of the changes you made
4. (optional): Add unit tests in the test script in the
repository.
5. Submit your work.
#
# SETTING UP DEV ENVIRONMENT

Set-Up
Before you can tackle any software development task, you need to set up your
development environment. You can think of your local development environment
as a virtual workbench with all the tools necessary to work on your project. To set
up your dev environment, follow these instructions:
● Install python 3 to your system - any recent version of python 3 will work fine,
though the most up-to-date version is advisable. If you need help with this step,
check out this excellent guide from real python:
https://realpython.com/installing-python/

● Fork and clone the starter repo (Folder available in Task Resources)

● Open the project in your IDE of choice - if you don’t have a favorite python IDE
yet, take a look at Pycharm Community Edition. It’s a well-designed IDE by
Jetbrains packed with features and plugins, powerful enough to work on the most
complex projects, entirely free.

● Create a new virtual environment in the project root. Pycharm can do this
automatically for you using the “configure python interpreter”
(https://www.jetbrains.com/help/pycharm/configuring-python-interpreter.html)
option in settings.

● Install all project dependencies. These are listed in the requirements.txt file.
Congrats, you’ve got your local development environment up and running! Now it’s
time to make changes to the codebase...

#
# MAKING CHANGES

When we are in a working environment, we usually receive tasks in the form of
engineering tickets. Here is an example of what this task looks like in the form of an
engineering ticket
Purpose
We want to process the data feed of stock A and stock B’s price to enable us to
analyze when trading for the stock should occur.
Acceptance Criteria

● getDataPoint function should return correct tuple of stock name, bid_price,
ask_price and price. Note: price of a stock = average of bid and ask

● getRatio function should return the ratio of the two stock prices

● main function should output correct stock info, prices and ratio

4.1 A Task 1 - Step-by-step Guide has been provided to walk you through
completion of the task
4.2 When the task is finished, commit and push the changes to the forked repo,
then upload the git patch file. To generate the patch file, guide has been provided

4.3 It is optional to add tests to the methods in the client application so that
developers are more confident these methods work as expected with different
inputs given to them. A guide on how to do this is provided.
