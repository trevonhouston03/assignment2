#Workflow Analysis

## 1. What triggers this workflow to run?
It only runs when either the code is pushed to the main branch or when a pull request occurs

## 2. What are the four main steps this workflow performs?
1. Checkout code
2. Validate the HTML
3. Check the links
4. Upload artifact

## 3. What does the "Checkout code" step do and why is it necessary?
The checkout code pulls the repository code into the workflow runner. It's necessary because all of the steps need access to the files
## 4. What is the purpose of the environment configuration?
To tell Github where to publish the website and manages permissions for deployment.

## 5. How does this automated deployment improve reliability compared to manual deployment?
It automatically checks the code so less mistakes happen.

## 6. What would happen if you pushed code to a different branch (not main)?
The workflow would simply not run. Only the main branch triggers the deployment.
