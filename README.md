# FocusedNPC
Creating a non-player character in a game backed by generative AI that will stay focused on its goals

## Setup
You will first need to create an Azure OpenAI resource with a GPT-4o model deployment, and update the .env file with their endpoints and keys.  

Finally, use the following commands in a python environment (such as an Anaconda prompt window) to set up your environment. This creates and activates an environment and installs the required packages. For subsequent runs after the initial install, you will only need to activate the environment and then run the python script.

### First run
```
conda create --name npc -y
conda activate npc

pip install -r requirements.txt
python focused_npc.py
```

### Subsequent runs
```
conda activate npc
python focused_npc.py
```

## Image Credit
I used DALLE-3 to generate the image on the left-hand side of the screen.  The image prompt was "high-quality video game image of a glowing spirit woman standing in the woods at night at a divergent path, where each option looks equally dangerous".  
!["high-quality video game image of a glowing spirit woman standing in the woods at night at a divergent path, where each option looks equally dangerous"](spirit_guide.png)
