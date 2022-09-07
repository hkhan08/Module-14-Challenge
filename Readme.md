

### Step 1: Tune the training algorithm by adjusting the size of the training dataset. 

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing the training window?

Increasing trading window to 6 months results in more accurate model (accuracy 0.56 vs 0.55 originally) and also the strategy return is close to 1.8 (80%) compared to original 1.6 (60%). 


### Step 2: Tune the trading algorithm by adjusting the SMA input features. 

Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. 

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

Changing SMA window to 50 and 200 trades (instead of 4 and 100) does not result in better performance compared to original model. The accuracy decreased to 0.54 and strategy return is below actual returns. 

### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.

In step 1 we increased the size of training window to 6 months and got better model, 