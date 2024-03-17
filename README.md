---
license: apache-2.0
---
# Grok-1

This repository contains JAX example code for loading and running the Grok-1 open-weights model.

Make sure to download the `int8` checkpoint to the `checkpoints` directory and run

```shell
pip install -r requirements.txt
python transformer.py
```

to test the code.

You should be seeing output from the language model.

Due to the large size of the model (314B parameters), a multi-GPU machine is required to test the model with the example code.
