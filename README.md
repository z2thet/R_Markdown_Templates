# MoffittTemplates

PDF, Word, and Powerpoint templates for Moffitt reports

## Getting Started


```r
# Installing from Gitlab
#Installing from Gitlab if you have ssh key set up
cred = git2r::cred_ssh_key(
	publickey = "MYPATH/.ssh/id_rsa.pub", 
	privatekey = "MYPATH/.ssh/id_rsa")

devtools::install_git(
    "git@gitlab.moffitt.usf.edu:ReproducibleResearch/R_Markdown_Templates.git", 
    credentials = cred, 
    build_opts = NULL)


```

Once installed restart Rstudio, then go to *File -> New File -> R Markdown -> From Template* and select appropriate Moffitt report
