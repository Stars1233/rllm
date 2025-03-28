.. _page1:

Main Hyper-Parameter Reference
=========================

+---------------------+------------------------------------------------------------------------------------------------------------+
| **Name**            | **Description**                                                                                            |
+=====================+============================================================================================================+
| :obj:`activation`   | Activation function used in the model layers.                                                              |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`batch_size`   | Number of samples per batch during training.                                                               |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`bias`         | Whether to include bias terms in the model layers.                                                         |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`conv_dim`     | Dimension of convolution layers when the input and output dimensions must be the same.                     |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`concat`       | Whether to concatenate the outputs from multiple heads in multi-head attention.                            |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`dataset`      | Dataset to be used for training or evaluation.                                                             |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`dropout`      | Dropout rate applied to the model to prevent overfitting.                                                  |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`emb_dim`      | Dimension of the embedding layer.                                                                          |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`epochs`       | Number of training epochs.                                                                                 |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`head_dim`     | Dimension of each attention head in multi-head attention mechanisms.                                       |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`hidden_dim`   | Dimension of the hidden layers within the model.                                                           |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`in_dim`       | Dimension of the input data.                                                                               |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`lr`           | Learning rate for training.                                                                                |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`metadata`     | Metadata of graph or tabular data, including node and edge types, and other related information.           |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`num_classes`  | Number of classes in the classification task.                                                              |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`num_feats`    | Number of features in the dataset.                                                                         |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`num_heads`    | Number of attention heads in multi-head attention mechanisms.                                              |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`num_layers`   | Number of layers in the model.                                                                             |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`out_dim`      | Dimension of the model's final output.                                                                     |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`patience`     | Early stopping criterion, specifying the number of epochs to wait for improvement before halting training. |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`seed`         | Random seed for reproducibility of results.                                                                |
+---------------------+------------------------------------------------------------------------------------------------------------+
| :obj:`wd`           | Weight decay parameter to regularize the model.                                                            |
+---------------------+------------------------------------------------------------------------------------------------------------+
