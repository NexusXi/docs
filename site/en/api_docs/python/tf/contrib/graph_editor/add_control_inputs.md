


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.contrib.graph_editor.add_control_inputs

### `tf.contrib.graph_editor.add_control_inputs`

```
tf.contrib.graph_editor.add_control_inputs(op, cops)
```


Add the control inputs cops to co.

Warning: this function is directly manipulating the internals of the tf.Graph.

#### Args:

* <b>`op`</b>: a tf.Operation to which the control inputs are added.
* <b>`cops`</b>: an object convertible to a list of `tf.Operation`.
Raises:
* <b>`TypeError`</b>: if op is not a tf.Operation
* <b>`ValueError`</b>: if any cop in cops is already a control input of op.

Defined in [`tensorflow/contrib/graph_editor/reroute.py`](https://www.tensorflow.org/code/tensorflow/contrib/graph_editor/reroute.py).
