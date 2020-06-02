# Set up your file directory for data analysis
Keeping your files organized is very important for programming; it is especially important as you are learning how to code!  

## Step 1: Get all of the GitHub repos synced to your local drive
1. Open GitHub Desktop on your computer
2. Click File > Clone Respository
3. Click GitHub.com
4. Click THRIVING-Team/resources
5. Click Clone
6. Repeat steps 2-5 for `clean`, `describe`, and `visualize`

## Step 2: Check your local directory to make sure everything worked!
If you stuck with GitHub's defaults, all of those file folders should be located in `/Users/yourusername/Documents/GitHub`. If they are not there, go to GitHub Desktop, click File > Clone Repository, and check what GitHub set as the local path. Your repos should be there!

## Step 3: Add folders to your local drive that will not sync to the GitHub cloud
In your computer's finder, go to `/Users/yourusername/Documents/GitHub`. Add two new folders - `local` and `data`.
- `local` is where you will store any files that you do not want to sync to the GitHub cloud. These may be Jupyter Notebooks (.ipynb files) where you were just experimenting or other files that are just for you.
- In your `data` folder, create three more folders: `raw_data`, `cleaned_data`, and `figures`.
  - `raw_data` is where you will store raw data downloaded from RedCap. Once your raw data files are in this folder, you shouldn't ever open, move, alter, or overwrite them. We want these to remain in the exact form that everyone else who downloads data from RedCap sees.
  - `cleaned_data` is where our cleaning scripts will output their data to.
  - `figures` is where our visualizations scripts will output their figures to.

## WARNING - PLEASE READ
It is extremely important that we are very careful in maintaining data security:
- Raw data should never be put in folders that sync to GitHub cloud (`resources`, `clean`, `describe`, `visualize`)
- Cleaned data should never be output to folders that sync to GitHub cloud (`resources`, `clean`, `describe`, `visualize`)
- Figures should never be output to folders that sync to GitHub cloud (`resources`, `clean`, `describe`, `visualize`)
- It is very common to preview the data that you are looking at in your Jupyter Notebook. Before you push your changes, ensure that there are no data previews in your Jupyter Notebooks
