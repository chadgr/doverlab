# Dover AI Lab

# Day Flow
Here is the outline of the day.  Please use this page as your guide as to all the steps we will go through together.  If you ever get lost as to where to go, come back here and follow down to the last step you were on to continue.

# Quick Introductions
Some of the initial prep steps take a while, so we will just say hello, start to configure machines then have a deeper introduction while we wait for configurations to finish.
* Introduce the facility logistics
* Quick introductions of attendee's

# Ensure Internet Connecitivity
* Make sure that all laptops are connected to the internet
* If there are difficulties with connecting or other laptop issues we have devices to use


# Login and Prepare Machines
There are perconfigured Azure Data Science VM's allready created for you.  You will need to finish the configuration of these machines.

   * Login to VM
   
      **User Name for all VM's:** labuser
   
      **Password for all VM's :** Doverlab2018#
   
   * Open a browser to this web page and follow along from the VM.

   * Download and install Docker
     * https://store.docker.com/editions/community/docker-ce-desktop-windows
     * After Install of Docker, you need to click on the Docker Icon in the system try 
     * Select 'Switch to Windows Containers'
     * This will enable Hyper-V and re-boot your machine
     * Once back in, click on the Docker icon and select 'Switch to Windows Containers' again
     * This **WILL Fail**
     * **Choose Re-Set to Factory Defaults**
     * When you seee the Docker welcome you are ready to go.
          
   * Install Azure ML Workbench
      * There is a shortcut on the desktop to install the workbench
      
      * This will take about 30 minutes
      
# Deeper Introductions

  * Introductions again; this time we will understand the work you do, tools you use and goals for the session.
  
# Azure Machine Learning Overview
  * Overview of the Azure Machien Learning Solutions.  Discover how it enables you to collaborate, train and operationalize models.
  * Review Azure environemnt setup for the labs
  * Review the labs that we will go through at a high level

# Create Azure Machien Learning Services
This the start where you will create Azure machine learning services in your Azure accounts.  j
  * Loign to [Azure Portal](http://portal.azure.com)
  * **User:** labuser{x}@doverailaboutlook.onmicrosoft.com - replace {x} with your lab number assigned.
  * **Passowrd:** Doverlab2018#
  * Press '+ Create a resource' in the upper left hand corner of the portal
  * Pick 'AI + Cognitive Services' from the left hand side of the Azure Market Place column
  * Click - 'Machine Learning Experimentation' 
  
  
  * Keep Defaults except as noted:
    * **Experimentation Account Name:** Give any name you want
    * **Resource Group:** Use Existing - You will only have 1 choice
    * **Location:** Pick one of the US regions
    * **Workspace for Experimentation account:** Can be anything, usually <Your first name>WS is a good choice
    * **Create Model Mangement Account:** - Keep checked.
    * **Model Pricing Tier:**  Select Devtest
    * **Press Create**
  
  # Start the hands on labs
  The labs we will be doing for this session is a sub-set of a 4-5 day course.  All the labs for the entire 4-5 course are available here: https://azure.github.io/LearnAI-Bootcamp.  Plese **DO NOT** go there there now.  This link is just for your reference for later.  Fell free to do any of the labs after our session here at the MTC.
  
  # Lab 1 (lab 3.2 of the larger course)
  We are going to start with lab 3.2 of the larger Azure AI course.  This lab will show us how to connect to an Azure ML workspace, run experientments locally and in a Docker container.  We will also see how to run multipul experiments and see how easy it is to compare the results.
  
  Please follow the instructions for this lab here: https://azure.github.io/LearnAI-Bootcamp/lab03.2-compare_and_choose_models/0_README
  
  **NOTE:**  There are some challenges with Docker containers on windows sometimes.  Please see a proctor for help if you can not get your experiement to run in a container.  
  
  # Lab 2 (lab 3.3 of the larger course)
  Azure ML usese both Conda and Docker together to tightly align configureations and ensure consistancy across depolyments.  
  
  Pelase follow the instructions of this lab here: https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab03.3_manage_conda_envs_in_aml/0_README.md
  
  # Lab 3 (lab 3.4 of the larger course)
  **Do not create the azure linux machine**, one is allready created.  There is allready a linux VM that everyone in the class can use setup for remote execution.  Follow this lab and do everything **Except** creating the VM.  Connection information below:
  
  https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab03.4-execute_in_remote_environment/0_README.md
  
  **IP:**  
  
  **User:** labuser
  
  **Passowred:** Dover2018#
  
   
   # Lab 4 (lab 3.5 of the larger course)
   This lab will be simular to the last one only this time we will execute against a VM running GPU's.  Again a central VM has been created for everyone to use.
  
  https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab03.5-execute_remote_gpu/0_README.md
  
  **IP:**  
  
  **User:** labuser
  
  **Passowred:** Dover2018#
  
  
  
  
  
  
