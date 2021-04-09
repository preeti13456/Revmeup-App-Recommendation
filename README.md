# Revmeup-App-Recommendation
Created a Recommendation Engine based upon the analysis of product reviews using collaborative filtering method.



<h1 text-align= "center"><b>fedora-contributor-trends</b></h1> 

<div text-align= "center">
  <h3> This is a hacky collection of scripts to create visualizations and hopefully insight from contributor-triggered activity on Fedora's messaging bus, via the "datagrepper" service. </h3>
</div>

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://pagure.io/fedora-contributor-trends/issues)[![Forks](https://img.shields.io/pagure.io/fedora-contributor-trends/forks.svg?logo=github)](https://pagure.io/fedora-contributor-trends/stats#authors)[![Stargazers](https://img.shields.io/pagure.io/fedora-contributor-trends#.svg?logo=github)](https://pagure.io/fedora-contributor-trends#/stargazers)[![Issues](https://img.shields.io/pagure.io/fedora-contributor-trends/issues.svg?logo=github)](https://pagure.io/fedora-contributor-trends/issues)[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/preeti/)[![Contributors](https://img.shields.io/pagure.io/fedora-contributor-trends/stats#commits.svg?logo=github)](https://img.shields.io/pagure.io/fedora-contributor-trends/stats#commits)

<br>


# Why fedora-contributor-trends?
This is a hacky collection of scripts to create visualizations and hopefully insight from contributor-triggered activity on Fedora's messaging bus,via the "datagrepper" service. Results are currently run on a personal system belonging to Matthew Miller, and published weekly there: https://mattdm.org/fedora/fedora-contributor-trends/
There's also a text report: https://mattdm.org/fedora/fedora-contributor-trends/report.txt.

You may also want to watch talk at DevConf 2016 where these metrics were first presented: https://mattdm.org/fedora/2016devconf/
 
# Home Page: 
<img src = "https://github.com/akrish4/CityonBikes/blob/akrish4/cityonbikes.PNG"> </img>
 
# Tech Stack 

-fedmsg==1.1.2
-matplotlib==3.4.1
-numpy==1.20.2
-pandas==1.2.3
-requests==2.25.1
-pytz==2021.1
-pytest==6.2.2


# Prerequisites🔑 :
 All the dependencies and required libraries are included in the file  `requirements.txt`  [See here](https://pagure.io/fedora-contributor-trends/blob/main/f/requirements.txt)


## Project Demo :hourglass:

- [![Already deployed version](https://mattdm.org/fedora/fedora-contributor-trends/active-contributors-by-week.svg)](https://mattdm.org/fedora/fedora-contributor-trends/)



# Contribution Guidelines🏗

We invite you to contribute to this project and make it better. Please have a look at [Code of conduct](https://pagure.io/fedora-contributor-trends/blob/main/f/README.md) first.

🎇 To start contributing, follow the below guidelines: ✨

**1.**  Fork [this](https://pagure.io/fedora-contributor-trends.git) repository.

**2.**  Clone your forked copy of the project.

```
git clone https://pagure.io/fedora-contributor-trends.git
```


**3.** Navigate to the project directory :file_folder: .

```
cd CityonBikes
```

**4.**   Create a new branch.

```
git checkout -b <your_branch_name>
```
**5.**  Setup your machine.
Overwhelmed about setting up your machine? No worries! We have got you covered!😇✌️.
Please head to [Installations section below in this README](#setup) 👇👇

**6.**  Now that you are ready with the setup, perform your desired changes to the code base. 🤩👍 
    
**7.**  Track your changes :heavy_check_mark:

```
git add . 
```

**8.**  Commit your changes .

```
git commit -m "Relevant message"
```

**9.**  Push the committed changes in your feature branch to your remote repo.

```
git push  origin <your_branch_name>
```

**10.**  To create a pull request, click on `compare and pull requests`.
Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.


**11.**  Add appropriate title and description to your pull request explaining your changes and efforts done.


**12.**  Click on `Create Pull Request`.


**13.**  Voila :exclamation: You have made a PR to the fedora-contributor-trends project :boom: .
Sit back patiently and relax while the project maintainers review your PR. 
Please understand at times the time can vary from a few hours to a few days.


# Installations 💻

After cloning the repo, run the following commands in the terminal to set up the environment to work on the project.

Make sure you are using Python 3  and inside fedora-contributor-trends folder.

**1.**  Install a virtual environment

```
$ pip3 install virtualenv
 ```

**2.**  Create virtual environment

```
Linux/MacOS
    $ python3 -m venv .venv
    $ source .venv/bin/activate
        

Windows
   $ python -m venv .venv
   $ .venv/bin/activate.bat

 ```

**3.**  Activate the environment

 For Linux:
 ```
 $ source env/bin/activate
```
For Windows:
 ```
 > .\env\Scripts\activate
```

**4.**  Install the requirements

```
 $ pip install -r requirements.txt
 $ pip install pyzmq(Command prompt)
```
**5.** Before you push any changes or improvements remember in order to follow the rules PEP8 you must run the style code tools
 
 Running `flake8`
 $ all project
 $ flake8 .

or a single file
    $ flake8 my_python_file.py
     **NOTE** you must resolve any errors that show `flake8`

**6.** Running `black`
 
  $ all project
  
   $ black .

or a single file

    $ black my_python_file.py

```
**7.**  Run the server

```
 $ ./run.sh

```
This will start the project and you can view it on ```127.0.0.1:8000``` in your browser.


## 💥 Issues:
For major changes, you are welcomed to open an issue  about what you would like to contribute. Enhancements will be appreciated.

#### All the Best!🥇

<p text-align = "center">

<a href="https://github.com/preeti13456"><img src="http://ForTheBadge.com/images/badges/built-by-developers.svg" alt="built by developers"></a>
[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://pagure.io/fedora-contributor-trends)

</p>


