# Sign Language Identification

## Description

This is the project created by me and my teammates for my Second Year Mini Project of Computer Engineering. <br>
This project aims to identify different sign language gestures using a machine learning model. <br>
The gestures identified include "Hello", "I Love You", "No", "Okay", "Please", "Thank You", and "Yes".

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/sign-language-identification.git
    cd sign-language-identification
    ```

2. **Ensure you have the necessary hardware and software for running machine learning models, such as a compatible GPU and TensorFlow installed.**

## Usage

### Data Collection

The `datacollection.py` script is used to collect data for training the model. Ensure your webcam is properly set up and run the script as follows:

```sh
python datacollection.py
```

This script will capture images of different sign language gestures and save them into designated folders for each label.

### Model Testing

The `test.py` script is used to test the model. Make sure you have a trained model available. You can run the script as follows:

```sh
python test.py
```

### Labels

The gestures identified by the model are defined in labels.txt:

```
0 Hello
1 I Love You
2 No
3 Okay
4 Please
5 Thank You
6 Yes
```

### Contributing

If you want to contribute to this project, please follow these steps:

```
Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes
Commit your changes (git commit -am 'Add some feature')
Push to the branch (git push origin feature-branch)
Open a Pull Request
```
