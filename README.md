# Efficient Transformer Library

Code for DASFAA-2023 submission:


Note: this library is being updated continuously.

The library is built upon PyTorch and RecBole for reproducing recommendation algorithms based on Transformers and exploring their effectiveness and efficiency.


## Requirements

```
recbole>=1.0.0
pyg>=2.0.4
pytorch>=1.7.0
python>=3.7.0
```

## Quick-Start

With the source code, you can use the provided script for initial usage of our library:

```bash
python run_recbole.py
```

If you want to change the models or datasets, just run the script by setting additional command parameters:

```bash
python run_recbole_trm.py -m [model] -d [dataset]
```

## Implemented Models

The implemented models can be seen in the **[Efficient Transformer Library](/recbole/model/efficient_transformer_recommender/)**.

path: /recbole/model/efficient_transformer_recommender/

e.g., [Linformer](/recbole/model/efficient_transformer_recommender/linformer.py), [Performer](/recbole/model/efficient_transformer_recommender/performer.py), [Synthesizer](/recbole/model/efficient_transformer_recommender/synthesizer.py), etc.
