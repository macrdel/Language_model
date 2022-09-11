# Language Model
A model that generates new ones based on the given texts

### Interface

The main code should be split into two parts: training and generation.

#### Train

Module: `train.py`

Options:
  - `--input-dir` − path to the directory containing the collection of documents; default = `stdin`  (not required)
  - `--model` − path to the file where the model is saved (required)
  
#### Generate

Module: `generate.py`

Options:
  - `--model` − path to the file from which the model is loaded (required)
  - `--prefix` − beginning of a sentence (one or more words). If not specified, the initial word selected randomly from all words (not required)
  - `--length` − length of generated sequence
  
### Data

  - `train.txt` (train data)
  - `test.txt` (test data)
  - `new.txt` (generated data)
  
### Model
  - `trained_model.pkl` (saved after training)
  

