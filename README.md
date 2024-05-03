# ProgressBar

Hi! This is the simpliest progress bar in Python. Check it out bellow!

Developed by Dmitriy Volynov (c) 2024

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## Installation

You can install this package in Google Colab or local project using the following commands:

```python
!rm -rf 'progress_bar'
!git clone https://github.com/dvolynov/progress_bar.git
```

## Quickstart

```python
from progress_bar import Bar

iterations = 200
pb = Bar(iterations)

for i in range(iterations):
  ...
  # your code
  ...
  pb.next()
```

<img width="500" alt="image" src="https://github.com/dvolynov/progress_bar/assets/83712099/4e02b230-1948-4632-9ae3-062186b56eab">

## License 

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
