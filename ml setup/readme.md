# Install tutorial
## python (user/project env)
linux
https://medium.com/codex/python-version-management-with-pyenv-and-pyenv-virtualenv-linux-ecd6578b7bbf
https://miguendes.me/how-i-set-up-my-python-workspace

pyenv versions
pyenv virtualenv --version
pyenv virtualenv 3.10.1 venv-name-3.10.1
pyenv activate venv-name
pyenv local venv-name
thun
wsl
https://medium.com/geekculture/how-to-install-and-manage-multiple-python-versions-in-wsl2-6d6ce1b6f55b

https://python-poetry.org/docs/master/#installing-with-the-official-installer

## pycaret
https://machinelearningmastery.com/pycaret-for-machine-learning/


# Model metrics
ML Observability Model
https://docs.arize.com/arize/glossary/model-metric-definitions

Accuracy - # of correct predictions / # of total predictions
Precision - TP / (TP + FP)
Recall - Sensitivity = TPR = TP/ (TP + FN)
F1 - F- 0.5, 1, & 2 based on the measure of weightage given to precision over recall
AUC - Area Under the Curve#
MCC - Matthews correlation coefficient (derived from confusion matrix)
KAPPA - Cohen’s kappa statistic is a very good measure that can handle very well both multi-class and imbalanced class problems.
