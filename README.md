# NodeJs-Di-MVC
# Project Name 
Epl match Api test
## Description
football game app 
# Table of Contents
- [Installation](#npm i )
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
# Architecture
    project-root
    |-- app
    |   |-- applayer
    |   |   |-- controller
    |   |   |   |-- global
    |   |   |       |-- GlobalController.js
    |   |   |
    |   |   |-- di
    |   |   |   |-- container.js
    |   |   |   |-- serviceLocator.js
    |   |   |
    |   |   |-- model
    |   |   |   |-- league.js
    |   |   |
    |   |   |-- service
    |   |       |-- globalService.js
    |   |
    |   |-- helper
    |   |   |-- globalHelper.js
    |   |
    |   |-- routes
    |       |-- global-route.js
    |
    |-- config
    |   |-- configApi.json
    |   |-- dotenv file, etc.
    |
    |-- logs
    |-- node_modules
    |-- test
    |-- server.js
    |-- logger.js
    |-- .gitignore, package.json, etc.
## Installation
[Include instructions on how to install and set up your project. Include any dependencies and their versions.]

```bash
# Example installation commands
git clone [repository_url]
cd [project_directory]
npm install
