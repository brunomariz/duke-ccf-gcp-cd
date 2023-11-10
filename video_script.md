# Video script

<div style="text-align: justify; text-justify: inter-word;font-family:Courier New">
  
Google Cloud is an online platform which allows you to use diverse cloud services

Lets see how you can use GCP to create automated testing for a simple python script

The first thing you`ll need is to create a new GitHub repo

After that`s done, you can create a new project on your Google Cloud, and open the cloud console

You`ll need to setup a new ssh key to clone your github project

After cloning the repo, you can open the editor right on the GCP website, and create the project files

To give them a quick test, create a virtual environment and activate it

Install the dependencies listed on the requirements.txt file, and test the code

Now that you know the code is working, enable Cloud Build 

This will allow you to create a trigger to listen to events on your github

After creating the trigger, you still need to do some configuration on your cloud build

On the settings tab, enable the app engine

If you havent done so yet, this will prompt you to enable your app engine

Once your app engine is enabled, do the same with service accounts

Thats all the configuration you`ll have to setup on Google Cloud

Now is a good time to add, commit and push your files to github if you havent done so already

Optionally, you can also setup github actions to test your code

To do this, simply head into the Actions tab and create a yaml file with instructions on what to run when code is pushed

One last thing that is missing before your google cloud build works properly, is to create a cloudbuild.yaml file describing what the cloud server should do on trigger events

Now you can modify your code to see the CD in action, for example, creating an error on your function and checking if the test fails, then removing the error you created to see if the test succeeds

The last thing you can do now to make sure everyone knows you`re a devops expert when they check out your repo by adding a status badge to your readme

This was how you can create simple automated tests using CD tools from google cloud and github

</div>
