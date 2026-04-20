This is the start of the read me file for the BGSA website.
To make chnages to the BGSA website you need to start by installing hugo via Winget. Go to the terminal in your computer and enter `winget install Hugo.Hugo.Extended` for Windows. Otherwise, follow instructions at this link for Mac/Linux : https://gohugo.io/installation/

To make any changes a previous collaborator needs to add you as a collaborator on the github website.

Once you have been added as a collaborator, yo can download the files as well as make pushes and pulls to the git repository.

Pushes and pulls can be done in R Studio. To do this you need to connect R Studio and Git. This can be done by following these steps.
1. Register on GitHub: https://happygitwithr.com/github-acct
2. If relevant, update RStudio: https://happygitwithr.com/install-r-rstudio
3. Install & Configure git: https://happygitwithr.com/install-git
4. Introduce yourself to git: https://happygitwithr.com/hello-git
5. Set up HTTPS tokens. This step is very important because it allows you to securely connect you to GitHub every time you want to use it from your computer, to do so:
Read the section’s intro https://happygitwithr.com/connect-intro.html
Set up an https pat https://happygitwithr.com/https-pat.html 

In the terminal in rstudio use `git submodule update --init --recursive` to load in the submodules.

In the terminal use `hugo serve` to check a local version of the website for pushed changes.

To deploy the website go to the terminal and type `hugo`

Instructions on how to use hugo to adjust the website, you can find instructions here: https://gohugo.io/documentation/