# Setting Up

Please follow these steps before the first lecture. If you get stuck at any step, please come see me after class.


## Software

1. Install the following software. If you already have R/RStudio installed, please ensure you have the latest version.
    * [R](https://cran.r-project.org/) programming language and software environment for statistical computing and graphics
    * [RStudio (preview version)](https://www.rstudio.com/products/rstudio/download/preview/) open source integrated development environment (IDE) for R 
    * LaTeX word processor and document markup language
    + [MacTeX](https://tug.org/mactex/downloading.html) for Mac (2.5GB)
    + [MiKTeX](http://miktex.org/download) for Windows (176MB)
    * [Git](https://git-scm.com/) open source distributed version control system
2. Ensure you can login to RStudio Server from your browser at [`https://rstudio.middlebury.edu`](https://rstudio.middlebury.edu/) (note the `https`) or simply [`go/rstudio`](go/rstudio). If you are off-campus you must first log into the [Middlebury VPN](http://mediawiki.middlebury.edu/wiki/LIS/Off-campus_Access).


## Installing Packages

We now describe how to install R packages, or extensions to R.
* In one of the panels in RStudio, there is a tab *Packages*.
* Click *Install* and in the *Packages* field type `ggplot2 dplyr` to install both those packages. 
* If prompted to restart R, say yes.
* In another panel, there is a tab *Console*. Type `library(ggplot2)` and `library(dplyr)` and ensure there are no error messages.


## Testing R Markdown

1. Open RStudio and starting in the menu bar, go to *File* -> *New File* -> *R Markdown...* -> *OK*.
2. A document `Untitled1` should pop-up. In that panel, click on the arrow next to *Knit HTML* and select *Knit PDF*.
3. Give the file a name and save
4. If prompted to install any packages, say yes.

A PDF document should pop-up.


## GitHub

GitHub is a web-based Git repository hosting system.

* Go to [GitHub](https://github.com/), create an account using your `@middlebury.edu` account, and verify your email.
* Email me `aykim@middlebury.edu` your GitHub login name. 
* Edit your profile:
    + Change your profile picture to a cropped picture of you (this will help me learn your names faster)
    + (Optional) Add your personal email
* Go to [GitHub Education](https://education.github.com/discount_requests/new)
    + Request an "Individual Account" discount
    + For "How do you plan to use GitHub?" type in: For my Middlebury College MATH 216 Introduction to Data Science course https://github.com/Middlebury-Data-Science


## RStudio and GitHub

In RStudio, follow the steps on [RStudio and GitHub](http://www.r-bloggers.com/rstudio-and-github/) up to and including the
```
git config --global user.email "mail@ewenharrison.com"
git config --global user.name "ewenharrison"
```
step, but replacing `mail@ewenharrison.com` with your `@middlebury.edu` email and `ewenharrison` with your GitHub login.


## Survey

Please complete the following [survey](https://docs.google.com/forms/d/1MgV-LbQsYvE4GgAE8hMARHEGu6eckE-cvqbZTQ9BbWU/edit?usp=forms_home).
