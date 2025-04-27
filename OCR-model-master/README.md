# OCR model
This is a model for Optical Character Recognition based on [CRNN-arhitecture](https://arxiv.org/abs/1507.05717)

## Dataset 

Vintext dataset

Number of Samples: 500,000 VIN entries
Type of Data: Text 
Average VIN Length: 17 characters
Number of Unique Manufacturers: ~500
Fields per Entry: 10 (e.g., VIN, Make, Model, Year, Body Style, Engine Type)
Classes: Manufacturers (Ford, Toyota, Honda, etc.)
Languages: English
File Format: CSV

## Requirement

Nvidia drivers >= 470, CUDA >= 11.4
Docker, nvidia-docker

