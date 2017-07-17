# njfrontend
A front-end project skeleton using Nunjucks and others tools that optimize my job converting PSD/AI to static HTML.
[WIKI](https://github.com/joaodfmota/njfrontend/wiki)

## Quick install
    npm i njfrontend -g
    njfrontend your-folder
    cd your-folder
    npm install

Obs.: your-folder is optional to clone in current directory or in another folder

## Getting Started

### Prerequisites
You need git to clone the repository. You can get git from [http://git-scm.com/](http://git-scm.com/ "Git").

You must have node.js and its package manager (npm) installed. You can get them from [http://nodejs.org/](http://nodejs.org/).

## Instalation
Over npm or git clone

### NPM
    npm i njfrontend -g
    njfrontend your-folder
    cd your-folder

### Clone
Clone the repository using [git](http://git-scm.com/ "Git"):
    git clone https://github.com/joaodfmota/front-end-seed-nj.git
    cd front-end-seed-nj

## Usage
After cloned or installed over npm you need to install the dependencies of your new project

### Install Dependencies
    npm install

### Run the Project
I've have preconfigured the project with a simple development web server. The simplest way to start this server is:

    gulp watch

Other's commands

    gulp
    gulp --production

## Directory Layout
    assets/                     --> assets files for the project
      fonts/                   
      images/
        svg/                        --> svg files
      scripts/
        main.js                     --> DOM-based Routing scripts
      styles/
        common/                   --> Common styles
        components/               --> Components styles
        layouts/                  --> Layouts styles
        main.scsss              --> Main SCSS file
      manifest.json             
    dist/                       --> dist files for the project
    source/                     --> source files for the project
      pages/                      --> pages files
      templates/                  --> templates files
        partials/                 --> partials files
    bower.js                    --> bower file
    gulpfile.js                 --> gulp file  