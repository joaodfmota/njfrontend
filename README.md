# front-end-seed-nj
A front-end project skeleton using Nunjucks and others tools that optimize my job converting PSD/AI to static HTML.

## Getting Started
To get you started you can simply clone the front-end-seed-nj repository and install the dependencies:

### Prerequisites
You need git to clone the front-end-seed-nj repository. You can get git from [http://git-scm.com/](http://git-scm.com/ "Git").

We also use a number of node.js tools to initialize front-end-seed-nj. You must have node.js and its package manager (npm) installed. You can get them from [http://nodejs.org/](http://nodejs.org/ "Git").

### Clone front-end-seed-nj
Clone the angular-seed repository using [git](http://git-scm.com/ "Git"):
    git clone https://github.com/joaodfmota/front-end-seed-nj.git
    cd front-end-seed-nj

## Install Dependencies
    npm install
    bower install

## Run the Project
I've have preconfigured the project with a simple development web server. The simplest way to start this server is:

    gulp watch

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