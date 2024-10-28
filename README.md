Let's set up the environment and dependencies for this project. Open up a new terminal and make sure you are in the home/project directory.

Create a Python virtual environment and install Gradio using the following commands in the terminal:
Then,
      pip3 install virtualenv 
      virtualenv my_env # create a virtual environment my_env
      source my_env/bin/activate # activate my_env

Then, install the required libraries in the environment,

  pip install langchain==0.1.11 gradio==4.44.0 transformers==4.38.2 bs4==0.0.2 requests==2.31.0 torch==2.2.1
