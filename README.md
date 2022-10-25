# Retrieve Twitter Data Programatically and save to CSV #

I used twarc library to retrieve data, and save to csv. The library is easy to use, and sample code works.

**This notebook is a proof of concept, only to be used for testing**

## Setup ##
* Install VSCode ( I use a mac). https://code.visualstudio.com/
* Download python (if needed)
* Download the Notebook from github in VSCode. Or run git clone commmand to download and install on computer
* Install libary (twarc) using pip command, preferred installer program for python language. Run pip from terminal in VSCode. e.g pip3 install twarc
* Ensure the data-output folder is setup, the query csv results will get stored in this folder


## Run get twitter api in notebook ##
* Update bearer_token with your value saved in a safe place. **Dont share your bearer_token**
* Enter query value, e.g. **"Tesla"**
* Update start_time and end_time values. If testing with Tesla, use **minutes**. If testing the query on your brand switch minutes to **hours**


## Setup AWS Account ##
* In order to add sentiment to your tweet text data analysis, you need to setup an AWS account. If you have one already, great, skip the next step.
* Link - https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&refid=78b916d7-7c94-4cab-98d9-0ce5e648dd5f&redirect_url=https%253A%252F%252Faws.amazon.com%252Fregistration-confirmation

* Download the Python AWS SDK - https://aws.amazon.com/sdk-for-python/
* Follow the python AWS SDK setup instructions. You need to configure your laptop to "talk" to AWS


## Pricing ##
* AWS offers a free tier, if you get the data small for testing purposes, the cost will be minimal. For now, we are justing using the AWS comprehend sentiment service. For detailed pricing follow this link - https://aws.amazon.com/comprehend/pricing/



