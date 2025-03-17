# starter code for a2

Add the corresponding (one) line under the ``[to fill]`` in ``def forward()`` of the class for ffnn.py and rnn.py

Feel free to modify other part of code, they are just for your reference.

---

One example on running the code:

**FFNN**

``python3 ffnn.py --hidden_dim 10 --epochs 1 ``
``--train_data ./training.json --val_data ./validation.json``
python3 ffnn.py --hidden_dim 10 --epochs 10 --train_data ./training.json --val_data ./validation.json --test_data ./test.json

**RNN**

``python rnn.py --hidden_dim 32 --epochs 10 ``
``--train_data training.json --val_data validation.json``
python3 rnn.py --hidden_dim 8 --epochs 10 --train_data training.json --val_data validation.json --test_data test.json
