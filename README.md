# supervised-machine-learning-challenge
Repository to hold files for Module 19 Challenge

This README.md file is just to hold thoughts/comments/analysis I have while doing this challenge.
For challenge instructions, please refer to README_original.md.

This challenge was pretty simple. Initially I had the first model use unscaled data but the second model use scaled data, and they were evenly matched, but the RFC model took longer to run than the Linear Regression. I believe this is because Linear Regression uses simple algebra which doesn't take too much time, whereas RFC uses trees.
I then wanted to compare with both models using scaled data, and saw that the performance of the Linear Regression model actually dropped, which I didn't expect.
