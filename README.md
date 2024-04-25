# Spotify Song Recommender Using Siamese Network

## Introduction
This project leverages a Siamese neural network to recommend songs on Spotify. By comparing audio features of songs, the network learns to identify and suggest tracks with similar musical characteristics. This project aims to enhance user experience by providing personalized song recommendations.

## Architecture 
<img title="Modified Siamese Network" alt="Architecture diagram" src="/images/boo.svg">

## Technologies Used
- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Spotipy (Spotify Web API Python library to generate data)
- Tensorflow GPU
- scikit-learn
- scipy
- seaborn
- matplotlib

## Installation
To set up this project locally, follow these steps:
1. Clone the repository:
git clone https://github.com/your-github-username/spotify-siamese-recommender.git
2. Navigate to the project directory:<br>
```cd spotify-siamese-recommender```

4. Install the required dependencies:<BR>
   ```pip install -r requirements.txt```

   
## Usage
To run the recommender:
1. Execute the main script:
  ```python recommend.py ```
Replace `recommend.py` with the script you use to start the recommendation process.

## File Structure
- `train_model.py` - Script for training the Siamese network.
- `recommend.py` - Script to generate song recommendations.
- `utils/` - Directory containing utility scripts and data processing modules.
- `data/` - Folder where song data and model weights are stored.


## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Thanks to the Spotify Web API for access to song data and Hugging face.
- Inspired by the research on Siamese networks for image similarity.



   
