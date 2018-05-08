# Process
### Create vocab
```
./word2vec_vocab.sh
```

### Create corpus with vocab
```
./word2vec_corpus.sh
```

### Create word2vec embedding
```
./word2vec_trainer.sh
```

### Use word2vec embedding
```
python ./word2vec_embedding_test.py
```
![logo](https://github.com/bage79/nlp4kor-pytorch/raw/master/ipynb/img/word2vec_embedding_test_1.png)
![logo](https://github.com/bage79/nlp4kor-pytorch/raw/master/ipynb/img/word2vec_embedding_test_2.png)
![logo](https://github.com/bage79/nlp4kor-pytorch/raw/master/ipynb/img/word2vec_embedding_test_3.png)


### Create tensorboard format file for visualization. (option)
```
./word2vec_tensorboard.sh
```
- http://localhost:6006/#projector
![logo](https://github.com/bage79/nlp4kor-pytorch/raw/master/ipynb/img/word2vec_tensorboard.png)
