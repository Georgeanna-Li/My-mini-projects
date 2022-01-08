## How to run the notebook ##
The texts are already extracted into `*_text.txt` files and part 3 loads directly from the text files instead of unzipping `lang-8.zip` every time.
To rerun the code for unzipping and text_extraction, uncomment following lines of code before running the notebook:
```python
# unzip("data/lang-8.zip", "data/")
# extract_all("data/lang-8/", "train_text.txt", "data/train.txt")
# extract_all("data/lang-8/", "dev_text.txt", "data/dev.txt")
# extract_all("data/lang-8/", "test_text.txt", "data/test.txt")
```
Otherwise, `Lab4.ipynb` contains all the necessary code to run the project and can be run from beginning to end.
