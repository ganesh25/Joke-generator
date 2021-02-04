# Joke-generator

Alexa Skill to read Jokes generated using a Deep Learning model.

## Data

* We created a data crawler script to scrap jokes from reddit.

## Pipeline
![PipelineImage](pipeline.jpg?raw=true "PipelineImage")

## Models used
* We initially used a LSTM model for training, but this didn't yield good jokes.

* Then we decided to use GPT-2, since it is already trained on a huge corpus. 

* As a result, our new model generated better jokes.

## Examples
![ExampleImage](example_image.jpg?raw=true "ExampleImage")



@misc{pungas,
        title={A dataset of English plaintext jokes.},  
        url={https://github.com/taivop/joke-dataset},  
        author={Pungas, Taivo},  
        year={2017},  
        publisher = {GitHub},  
        journal = {GitHub repository}  
}
