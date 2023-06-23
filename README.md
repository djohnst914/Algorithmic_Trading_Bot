# Algorithmic ML Trading Bot

## Purpose:
Improve exisiting algorithmic trading systems and maintain the firm's competitive advantage in the market by incorporating Machine Learning models.

## Libraries/Modules:
- Hvplot
- Numpy
- Pandas
  - dateoffset
- Pathlib
  - Path
- Sklearn
  - svm
- Sklearn.metrics
  - classification_report
- Sklearn.preprocessing
  - standardscaler
- Matplotlib
- Warnings

## Process
1. **Establish a Baseline Performance**: I first established a baseline performance using the Support Vector Machine classifier model from sklearn's SVM learning method. Trading signals were generated using short window and long window Simple Moving Averages. 
2. **Tune Baseline Trading Algo**: Next I attempted to tune the trading algorithm by adjusting the size of the training dataset and the SMA input features. 
3. **Evaluate New Machine Learning Classifier**: I imported a new ML classifier (AdaBoost), and used the original training data to evaluate its performance. The new model was backtested to evaluate its performance and compared against the baseline SVM model and the tuned trading algorithm.
4. **Evaluation Report**: Finally, an evaluation report was created summarizing the findings of the analysis. The findings were supported using PNG images created at each step.

## Results

* Baseline Trading Algo plot can be found in 'actual_vs_strategy_returns.png'

* Tuned Baseline Trading Algo plot can be found in 'new_actual_vs_strategy_returns.png'

## Summary

**What impact resulted from increasing or decreasing the training window?**

- Slightly increasing the training window seemed to have a negative effect on the strategy returns in the tuned algo

**Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?**

- This newly tuned model performed worse than the baseline algo

## Contributor:
**Dylan Johnston**

[GitHub](https://github.com/djohnst914) 

Email: dylanhjjohnston@gmail.com

## License:

This project is licensed under the GNU General Public License v3.0. See [LICENSE](https://github.com/djohnst914/Algorithmic_Trading_Bot/blob/main/LICENSE) file for details.