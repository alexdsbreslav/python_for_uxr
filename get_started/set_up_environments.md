# Get Anaconda and JupyterLab Set Up to Handle Environments
**Before you start**: Make sure that you have set up your file directory first. See `set_up_your_file_directory.md` for directions on setting up a proper directory of folders on your local computer.

**What are environments**: When we code, we utilize packages like pandas and numpy to do things for us. When we create a coding environment, we specify exactly what packages are in that environment.  

**Why create an environment**: When we code, we want to make sure that everyone is using the same packages so that we all encounter and/or avoid the same problems/bugs.

**Add the `python_for_uxr_env environment` to Anaconda**
1. Open Anaconda
2. Open JupyterLab
3. Open a Terminal window
4. Type `conda install nb_conda_kernels` and hit enter
5. Type `conda env create -f /filepath/to/resources/folder`. If you used the default settings when you set up your file directory, the `/filepath/to/resources/folder` should look like this `/Users/alexbreslav/Documents/GitHub/python_for_uxr` where `alexbreslav` is replaced with the username on your computer.
6. Add `/python_for_uxr_env.yml` to the end. The line of code should now read `conda env create -f /filepath/to/resources/folder/python_for_uxr_env.yml`. If it looks correct, hit enter.

NOTE: All of my filepath examples are for Mac; if you are on a PC the slashes are flipped: `\Users\alexbreslav\Documents\Github\resources`
