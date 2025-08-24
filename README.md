# Manually load raw data to data/raw directory
  Note: Link to the raw data https://drive.google.com/drive/folders/19mYvqKLcQJ018ZgNxxRbKiGa2eCuLtte?usp=drive_link

# Preprocessing notebook loads, resaples, silence trims and normalize the audio and load the processed data to data/processed.
   Note: I have loades the preprocessed data to the given link 
   metadata: https://drive.google.com/file/d/1J5OoWGlGaaCdS5Nn1XMj2oLgD0YJaj97/view?usp=sharing
   processed data: sad, neutral, happy, angry, sad directory from the link https://drive.google.com/drive/folders/1KPbiV9MHS97czxU7p5zDNxoOeurLaJHR?usp=sharing

# Feature extraction notebook extracts the audio features from the processed audio
  Note: This notebook creates - `data/processed/features_16d.csv`  
- `data/processed/features_16d_scaled.csv` (z‑scored)  
- `data/processed/scaler_standard.pkl` (for reuse)

# Dimentionality reduction reduces the extracted audio features to reqiured numbers of principle components and saves the cvs file extracted to data/processed

