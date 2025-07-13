Personal Portfolio Website – CI/CD to AWS S3 via GitHub Actions

📌 Overview

This project is a personal portfolio website built with HTML and CSS and deployed to AWS S3 using GitHub Actions for CI/CD automation. Every time code is pushed to the main branch, it automatically updates the hosted website.



✨ Features

Static website built with HTML and CSS

CI/CD pipeline using GitHub Actions

Hosted securely on AWS S3

IAM user with limited programmatic access

Secrets securely stored in GitHub



🛠 Tech Stack

HTML5 / CSS3

Git & GitHub

GitHub Actions (CI/CD)

AWS S3 (Static Website Hosting)

AWS IAM (Programmatic User Management)



🚀 How It Works

Code is written in index.html and styles.css

Pushed to GitHub using Git

GitHub Actions detects the push

It runs the workflow .github/workflows/deploy.yml

This script:

Authenticates with AWS using GitHub Secrets

Syncs the latest code to the S3 bucket

Your live website is updated instantly



📦 Project Structure

cj-portfolio/
├── index.html
├── styles.css
├── .gitignore
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md



🧪 Setup Instructions (Local to Live)

Clone the repo

Make sure AWS CLI and Git are installed

Create a new S3 bucket with static hosting enabled

Create a programmatic IAM user with AmazonS3FullAccess

Store credentials in GitHub > Settings > Secrets:

AWS_ACCESS_KEY_ID

AWS_SECRET_ACCESS_KEY

AWS_S3_BUCKET

AWS_REGION

Push any change to main branch

GitHub Actions will deploy it automatically



📸 Screenshots (To Add)

GitHub repo with files

GitHub Actions > Successful deployment run

AWS S3 bucket config

Final live website output



📚 Learning Points

Git workflow: add, commit, push

GitHub Actions: .yml structure, triggers, steps

AWS S3 setup and static hosting

IAM: user creation, permissions, security

Secrets: GitHub secrets to store AWS credentials



🔗 Live Demo

Click to View Website



🙋‍♂️ Author

King CJBuilt under tactical guidance of Commander Erwin



📬 Contact

If you're a recruiter, engineer, or cloud enthusiast, feel free to connect:

GitHub

LinkedIn

Victory through Automation. Deployment without delay.
