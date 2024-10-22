# Latent diffusion for Language
## Setup
1. Installing dependencies

    `pip -r requirements.txt`
2. Login to wandb
    
    Please generate a login key on wandb and login to wandb library or contact me for the key
    
    `python -m wandb login` (paste the key when prompted for)

## Adding the dataset
Add the `datasets/` folder to the root working directory (along with the rest of code).

## Model Training and Evaluation

Execute the cells in `run.ipynb`. 
    
I have already written the arguments that needs to be passed to each file already in the run.py file that will automatically run the code for ROCStories dataset.

## Acknowledgment

https://github.com/justinlovelace/latent-diffusion-for-language