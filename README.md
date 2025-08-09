# My First Foray into Cloud Computing: An Online Resume  

## Project Overview  
This project marks my initial steps into the world of cloud computing. I've taken my professional resume and transformed it into a live, accessible website. The deployment was achieved using Microsoft Azure's Static Web Apps service, with the entire codebase hosted and version-controlled on GitHub. The seamless integration between Azure and GitHub provided an excellent opportunity to learn about automated CI/CD pipelines.
## Technologies Used
This project was built using the following technologies:
 ### 1. HTML:
     I used HTML to create a clean and structured webpage from my original resume document. This allowed me to present my professional information in a web-friendly format.
 ### 2. CSS:
      I used CSS to style the webpage, ensuring a clean and professional layout.
 ### 3. GitHub:
      I leveraged GitHub as a central hub for my project, utilizing its features for version control and collaborating on code. The platform's integration with Azure was key to the deployment process.
 ### 4. Azure Static Web Apps:
      This service was my tool for deploying the website. Its capability to automatically build and deploy my project directly from my GitHub repository made the publishing process straightforward and efficient.
## My Project Journey
 ### 1. Azure Account Setup:
     My journey began by creating a Microsoft Azure account. I took advantage of the Azure for Students offer, which provided me with free credits to explore and experiment with cloud services without any  financial commitment.

 ### 2. Resume Transformation:
    Next, I converted my professional resume from its original PDF format into a web-friendly format using index.html for structure and a separate styles.css file for styling. This step focused on crafting a well-structured and presentable web document.

 ### 3. GitHub Repository:
     I established a new public repository on GitHub, which I named "my-resume," to house my project files.

 ### 4. Deployment to Azure:
     The most exciting part was connecting my GitHub repository to Azure Static Web Apps. This action automatically configured a GitHub Actions workflow, which now handles the continuous deployment of my website. Any time I push an update to the main branch, the site is automatically rebuilt and redeployed.
     
 ### 5. Documentation:
    Documenting my progress in this README.md file was a crucial step. It serves as a personal record of my learning and highlights the process I followed, including any challenges I overcame.
    
## Challenges and Solutions
I encountered an initial obstacle when the automated build process failed. The issue stemmed from my project being a simple HTML/CSS site that didn't require a traditional build step. I resolved this by correctly configuring the output location in the Azure deployment settings, effectively telling the pipeline to serve the root directory directly.
## Live Demonstration 
👉 [View My Resume](https://witty-field-0cad37b00.1.azurestaticapps.net)
