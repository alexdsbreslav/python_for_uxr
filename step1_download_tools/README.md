# Step 1: Download Tools
Before we do anything, we need to set up your computer with the appropriate applications, accounts, and settings.

## Download Anaconda :snake:
[Click on this link](https://www.anaconda.com/distribution/) to head to the website. When you are there, download Anaconda using the 64-Bit Graphical Installer.
### What is Anaconda?
Anaconda creates a home for coding on your computer. When you open Anaconda Navigator on your computer, it is like opening the Applications tab on your finder. When you want to start coding, you'll open Anaconda Navigator and, from there, start up JupyterLab.
### What is JupyterLab?
JupyterLab is the application that you will be doing all of your coding in. JupyterLab is an application, which you will use to interact with your data - in this way, JupyterLab is equivalent to Excel. However, JupyterLab is different from Excel in one very important way: in Excel, you make changes to you data by hand; in JupyterLab, you are writing Python code so that your computer will makes changes to the data for you.

## Create a copy of this GitHub repo :octocat: on your computer.
On GitHub, collections of files and folders is a called a repository or **repo**. This repo is called `python_for_uxr`. I want you to download this repo on to your computer. When you do, you'll have a perfect copy of everything that is online. 

To copy this repo to your computer:
1. Go back out to the `python_for_uxr` home page. You can [click here](https://github.com/alexdsbreslav/python_for_uxr) to open the repo home page in another tab. 
2. Click on the green `Clone` button.
3. Click `Download ZIP`.
4. Go to the documents folder on your computer. Double-click on the file `python_for_uxr-master.zip` to unzip it.
5. Move the file to your desktop.
6. Rename the folder `python_for_uxr`.

## Set up Anaconda on your computer.
At this point, you should have downloaded Anaconda and downloaded a copy of the `python_for_uxr` repo on to your computer. If you would prefer to read these directions on your computer, you can view them offline! To view these directions offline, navigate to the `step1_download_tools` folder in the `python_for_uxr` repo that you just downloaded onto your computer. Open the `offline_README.pdf` to see these same directions in a PDF on your computer.

Now we need to get Anaconda set up. Remember that Anaconda is the home for coding on your computer. Anaconda does not come with all of the things that you will need for coding. To get your computer totally set up to start coding, we will create a coding **environment**.

### What is an environment?
When we code, we utilize packages like pandas and numpy (pronounced numb-pie) to do things for us. When we create a coding environment, we specify exactly what packages we want to use while we are coding. I've created the `python_for_uxr_env.yml` file; this is a special kind of file that tells Anaconda what packages to download.

### To set up the environment in Anaconda on your computer...
1. Open Anaconda
2. Open JupyterLab
3. Open a Terminal window
4. Type `conda install nb_conda_kernels` and hit enter. This line of code updates an important setting in Anaconda. You only need to do this once right after you install Anaconda.
5. Next we are going to type something **that looks like**:  
`conda env create -f /Users/alexbreslav/Documents/python_for_uxr/step1_download_tools/python_for_uxr_env.yml`
    - `conda` says "Anaconda, do this thing".
    - `env create` says "create an environment".
    - `-f` says create the environemnt from a file.
    - `/Users/alexbreslav/.../python_for_uxr_env.yml` is the file path that describes where to find the environment file on **my** computer.

    - Update/type out the line of code above and hit enter:
      - Replace `alexdsbreslav` with the username on your computer.
      - If you are on a PC the slashes are flipped; rather than `/Users/alexdsbreslav...` your file path would look `\Users\alexdsbreslav`
      - If you put the `python_for_uxr` folder somewhere other than your Documents folder, make sure you specify that in the file path.
      - If you did not change the name of folder to `python_for_uxr` or changed it to something else entirely, make sure you specify that in the file path.
  
6. Close JupyterLab and open it back up again. When you do, you should see the new environment in the Launcher.

## Step 1 :white_check_mark: :clap:
Now you have all of the tools that you need and you've done all of the necessary set-up to start coding! You have the power of Python and JupyterLab on your computer, now let's start learning how to code! [Click here](https://github.com/alexdsbreslav/python_for_uxr/tree/master/step2_learn_python_basics#step-2-learn-python-basics) to see the step 2 instructions online. You can also open up the instructions on your computer by navigating to the `step2_learning_python_basics` folder and opening the `offline_README.pdf`.

