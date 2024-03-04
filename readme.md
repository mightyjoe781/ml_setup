### ml_ai setup
Note this setup is adapted from following repo : https://github.com/jplane/pyspark-devcontainer for learning from the following book : **Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 3rd Edition**

#### requirements
* install docker-desktop
* install vscode
* install vscode extension : dev containers

#### open in dev-container
* open command-pallete and select: reopen in container

#### changelog :
* original repo doesn't work on m1 macs : added this to devcontainer.json to fix : `"initializeCommand": "ls"`
