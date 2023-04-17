# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">
# Logistic Regression Model for Binary Classification

## Introduction
This is a logistic regression model for binary classification. It reads a CSV file containing input data with two attributes and a target class label, and pre-processes the data by removing unwanted columns and splitting it into training and test sets.

<img width="491" alt="image" src="https://user-images.githubusercontent.com/117291117/232397236-ac31019b-7a3e-49fd-acce-d765907dcd86.png">


## Functions
1. sigmoid(z): computes the sigmoid of an input z.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232397522-7ba829ab-7960-4da8-8250-cf981aeec7fc.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232397634-ba23a4e7-6a72-4f4e-86d3-a0bb9c16b541.png">

2. loss(Y, y_hat): computes the logistic regression loss.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232398153-b37bd1db-7d9a-475a-a640-bc0f510de36c.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232398311-594a279a-98f4-4e9a-9e11-6664a65c33df.png">
3. gradients(X, Y, y_hat): computes the gradients of the loss w.r.t the weights.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232398400-cddfc54f-4cf9-43c0-8fa1-8c6c5b8b9c85.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232398607-a60c0f12-910d-48e1-aa5a-3ac1534c5589.png">

4. normalize(X): normalizes the input data.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232398901-fd7ae994-dd63-49cc-91fc-4ed82228c1e8.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232399077-f61b0a13-e360-4575-b968-9833aec40c0b.png">

5. predict(X, w): predicts the class label of input data using the learned weights.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232399353-6535be0b-75c0-4d29-9754-fdc0ade137bf.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232399553-ccab23bd-0100-4c0a-8f6f-be4259babf90.png">

6. plot_decision_boundary(X, w): plots the decision boundary for the input data.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232399833-2f2ad5a2-22ac-4be8-99e4-924edce24843.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232400009-1d547e47-f75f-4c56-8879-92279917150e.png">

7. train(X, Y, epochs, eta): trains the logistic regression model on the input data using gradient descent. It returns the learned weights and the loss vs. epoch list.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232400241-a22867fd-ec96-4f4b-a843-61ba4acedf4e.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232400790-c38a9c8e-63be-4444-b73a-acb84cad5790.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232400909-da90b5b7-34e2-4565-83b7-4b2dbad89ead.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232401072-dd76254f-5e18-42d2-8936-7d2074881c8a.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232401231-b6ba4a6a-63c3-48fc-b94d-42ae5e3dda40.png">



## Model Usage
1. Using the trained model, predict the output class labels for the test set.
2. Calculate the accuracy of the model on the test set by comparing the predicted class labels with the true class labels.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232401746-7bd85ab0-9c17-41cb-ab7b-5417dd1480e6.png">

3. Visualize the decision boundary by plotting the test set along with the decision boundary line, which is the line that separates the positive and negative classes.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/117291117/232401511-eb12c16f-43d8-486e-9c5c-4c0ca641804d.png">


## Conclusion
After training and evaluating the logistic regression model, the results can be interpreted and conclusions drawn.
