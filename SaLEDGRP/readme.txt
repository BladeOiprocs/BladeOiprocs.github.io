The instructions for setup are in Saled.zip. You will need to establish an anaconda environment. The README details the instructions for the environment based in Unix. For Windows, you have to remove the word "env" so that you get: 
conda create --name <saled11>

Using "env" will attempt to make an environment from the given environment in the project. However, this environment uses a a dependency called "tree", which only exists in Unix, and not Windows. So the project will fail to create the environment if you use this command. Removing env simply create a new environment, the project still runs regardless.

