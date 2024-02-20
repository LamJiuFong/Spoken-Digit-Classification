# Spoken-Digit-Classification

1. Ensure that the `data` folder is in the same directory with the `main.ipynb` file.

2. Ensure that `scikeras`, `librosa` and `os` has been installed on your local. If not, open the terminal and run either:<br>
    a. `pip install scikeras`<br>
    b. `pip install librosa`<br>
    c. `pip install os`<br>

3. Open `main.ipynb`, select Run All.

4. Scroll to the end of the file, you will see a commented section.

5. Select which model and feature combination you want, uncomment that line and click Run.

6. To experiment different values of batch size, num_of_frames, cv (in GridSearchCV), epochs and hyperparameters. You can find them at their respective locations:<br>
    a. batch size : `grid_search.fit()`<br>
    b. num_of_frames : `load_data_function()`<br>
    c. cv : `GridSearchCV()`<br>
    d. epochs : `KerasClassifier()`<br>
    e. hyperparameters : params_grid{}