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

## Alexa Skills Interface with Examples

![Example1](example1.png?raw=true "ExampleImage1")

![Example2](example2.png?raw=true "ExampleImage2")


## Future Scope

 * Remove offensive jokes due to biased data
 * 1 forward pass ~ 45 seconds
 * Make the model fetching + reading out real time and automated
 * Make the model learn the difference between Humour and Sarcasm, since they are both distinct


@misc{pungas,
        title={A dataset of English plaintext jokes.},  
        url={https://github.com/taivop/joke-dataset},  
        author={Pungas, Taivo},  
        year={2017},  
        publisher = {GitHub},  
        journal = {GitHub repository}  
}
