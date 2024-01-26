# Speaker Recognition Program

## Overview

This Python project is a speaker recognition program that uses basic signal processing and signal analysis techniques. The program is designed to receive 15 audio recordings from three users, where the first 10 recordings are used for training a custom model, and the last 5 recordings are used for testing.

## Features

- Manages file directories using the OS module.
- Utilizes the librosa module for audio file sampling.
- Created a custom model, training it on 10 audio recordings per user, the last 5 recordings are tested.
- Using NumPy, signals are converted from the time domain to the frequency domain.
- At the end, the speaker recognition accuracy and overall program accuracy are calculated.
- Use pip for convenient installation of required modules.

## Usage

1. Clone the repository.
2. Navigate to the `AudioFiles` folder to find the prementioned recordings.
3. Run the program and follow the instructions for training and testing the speaker recognition model.

## Installation

```bash
pip install os
pip install librosa
pip install numpy
```

## Folder Structure

- `AudioFiles`: Contains the provided audio recordings.

Feel free to reach out for any questions or improvements!
