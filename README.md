# vercel-svc-mn
temp project for Minnesota data, related to SVC codes; part of vercel final project

# steps taken to get the file up 
- go to https://www.health.state.mn.us/data/apcd/publicusefiles/download.html and download excel file
- make the excel file smaller and only keep the data tab, delete everything else
- save the file as a csv file
- create a data folder and then create a file called about.md and write #this is a placeholder file
- git add then git commit -m 'example msg' and then git push
- now the repo is updated and you should see a folder called data; upload your CSV file here
- now you need to refresh the repo so the file appears in the shell environemnt
- do git pull

# steps after file is done
- create a main.py
- create a requirements.txt
- create a vercel.json

# to deploy to Vercel
- go to vercel
- deploy a new project by importing the existing Git Repository