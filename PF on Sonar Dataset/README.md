# Professional-Forest-Project

# Philosophy of Professional Forest

In the world of machine learning, we use different algorithms for prediction, each with its own benefits, usage, and performance. Each algorithm can be enhanced in various ways. For example, a decision tree can be powered up by a random forest algorithm. The philosophy behind the random forest is: "Wisdom is in society." A random forest is a society based on decision trees as its members. Trees are created based on features, and we can create an astronomical number of trees. To use this algorithm, there are several ways to create random trees. The key is to create good trees using approaches such as pruning, etc.

During the training phase of the random forest model, all trees are trained on a specific task, and in the predicting mode, the final prediction is based on the voting of the society.

To gain the performance of a random forest by creating good trees, we can approach it differently. Instead of focusing only on creating good trees, we can create a very large forest, which I call the "primary_forest." In the training phase, we train all these trees, and then we calculate the performance of each tree in the test phase. We can easily sort the scores in a list and then select the top scores. For example, selecting the top 10% of trees from the primary forest. Now, we select the best trees and make a professional forest. The philosophy of the professional forest is: "More wisdom is in an expert society." In this way, we create an expert society by selecting and using expert trees based on their performance in real tasks during training and testing.

This philosophy is logical. In this approach, we have two hyperparameters: the number of trees in the primary forest and the percentage of selection from the primary forest (e.g., 5%, 10%, etc.).

In this project, I started with a decision tree algorithm on the sonar dataset. Then, I tried to improve the performance of the decision tree algorithm using usual methods. Next, I improved the model by using a random forest model. The performance of the random forest model indicated better performance. Then, I started improving the model's performance by using the "professional_forest," which clearly indicated better performance than the random forest algorithm. Finally, I tried improving the "professional_forest" performance by fine-tuning the hyperparameters mentioned. It clearly indicates that by fine-tuning hyperparameters, we can achieve higher performance.

I will continue to explore this philosophy in my future projects and try to find different hidden aspects to gain a clear insight into hyperparameter fine-tuning. ali.m.shafiei@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## © 2024 Ali M Shafiei. All rights reserved.
