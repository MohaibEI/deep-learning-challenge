# Alphabet Soup Charity Deep Learning Challenge

## Instructions

### Step 1: Preprocess the Data
1. Upload the starter file to Google Colab.
2. Read in the charity_data.csv to a Pandas DataFrame.
3. Identify target(s) and feature(s) for your model.
4. Drop the EIN and NAME columns.
5. Determine the number of unique values for each column.
6. For columns with more than 10 unique values, determine data points for each unique value.
7. Bin "rare" categorical variables together using a cutoff point.
8. Encode categorical variables using pd.get_dummies().
9. Split data into features array (X) and target array (y).
10. Scale training and testing features datasets using StandardScaler.

### Step 2: Compile, Train, and Evaluate the Model
1. Create a neural network model using TensorFlow and Keras.
2. Design hidden layers with appropriate activation functions.
3. Compile and train the model.
4. Create a callback to save model weights every five epochs.
5. Evaluate the model using test data to determine loss and accuracy.
6. Save results to AlphabetSoupCharity.h5.

### Step 3: Optimize the Model
1. Adjust input data to optimize the model.
2. Experiment with different configurations:
   - Drop more or fewer columns.
   - Create more bins for rare occurrences.
   - Adjust the number of values for each bin.
   - Add more neurons or hidden layers.
   - Use different activation functions.
   - Modify the number of epochs.

### Step 4: Write a Report on the Neural Network Model
- Overview of the analysis.
- Data Preprocessing:
  - Target and feature variables.
  - Variables removed from input data.
- Compiling, Training, and Evaluating the Model:
  - Neurons, layers, and activation functions chosen and why.
  - Achievement of target model performance.
  - Steps taken to increase model performance.
- Summary:
  - Overall results of the deep learning model.
  - Recommendation for a different model to solve the classification problem.

### Step 5: Copy Files Into Your Repository
1. Download Colab notebooks.
2. Move them to your Deep Learning Challenge directory in your local repository.
3. Push the added files to GitHub.
