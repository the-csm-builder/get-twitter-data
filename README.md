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
* Link