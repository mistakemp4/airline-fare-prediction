# GitHub upload instructions

## Files in this folder
- `airline_fare_modeling_case_study.ipynb` - the cleaned notebook
- `README.md` - the GitHub landing page text
- `requirements.txt` - Python dependencies
- `.gitignore` - ignores environment and notebook checkpoint files

## Recommended GitHub repository name
`airline-fare-prediction`

## Before uploading
1. Create a GitHub account if you do not already have one.
2. Download this whole folder to your computer.
3. Make sure the dataset file `Airfares.csv` is either:
   - included in a local `data/` folder if you are allowed to share it, or
   - excluded from GitHub if you are not allowed to share course data.

## Option A: Upload through the GitHub website
1. Create a new repository on GitHub named `airline-fare-prediction`.
2. Keep it public if you want recruiters to see it.
3. Click `uploading an existing file`.
4. Drag these files into the repository page.
5. Commit the files.

## Option B: Upload with Git
Open a terminal in this project folder and run:

```bash
git init
git add .
git commit -m "Add airline fare prediction portfolio project"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

## What to put on your portfolio site
Use this project title:
**Airline Fare Prediction with Regression and Regularization**

Use this one-line summary:
**Built and compared regression models in Python to predict airline fares, identify price drivers, and estimate the impact of market competition on pricing.**

## Suggested project page structure
1. Problem
2. Approach
3. Key results
4. Tools used
5. GitHub link

## Best screenshots to include on your site
- Correlation heatmap
- One category comparison chart
- A short list of final model results
- The Southwest scenario result showing the estimated fare drop

## Important note about the dataset
If `Airfares.csv` came from course materials and you are not sure you can share it publicly, do not upload it. In that case:
- keep the notebook and README public
- add a note that the dataset is not included because of source restrictions
- explain how the project was conducted and summarize the results
