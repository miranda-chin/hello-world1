# hello-world1
Github repository for Exercise 3
# My first Project
## **Course**: ESS 330
## **Name**: Miranda Chin
## **Year**: 2025
## **Major**: ESS
## **OS**: Mac

## create a personal access token for authentication:
usethis::create_github_token()

install.packages()
## set personal access token:
## If credentials is not installed, do you remember how to install a package?
credentials::set_github_pat("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"")

usethis::git_sitrep(tool = "github", scope = "user")

