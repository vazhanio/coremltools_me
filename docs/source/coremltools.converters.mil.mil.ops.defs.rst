MIL Ops
===============================================

Operators supported by the Model Intermediate Language (MIL):

activation
---------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.activation

   .. autoclass:: clamped_relu
   .. autoclass:: elu
   .. autoclass:: gelu
   .. autoclass:: leaky_relu
   .. autoclass:: linear_activation
   .. autoclass:: prelu
   .. autoclass:: relu
   .. autoclass:: relu6
   .. autoclass:: scaled_tanh
   .. autoclass:: sigmoid
   .. autoclass:: sigmoid_hard
   .. autoclass:: silu
   .. autoclass:: softplus
   .. autoclass:: softplus_parametric
   .. autoclass:: softmax
   .. autoclass:: softsign
   .. autoclass:: thresholded_relu


classify
---------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.classify

   .. autoclass:: classify


constexpr_ops
---------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS16.constexpr_ops

   .. autoclass:: constexpr_affine_dequantize
   .. autoclass:: constexpr_cast
   .. autoclass:: constexpr_lut_to_dense
   .. autoclass:: constexpr_sparse_to_dense


control\_flow
------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.control_flow

   .. autoclass:: cond
   .. autoclass:: Const
   .. autoclass:: select
   .. autoclass:: while_loop
   .. autoclass:: make_list
   .. autoclass:: list_length
   .. autoclass:: list_write
   .. autoclass:: list_read
   .. autoclass:: list_gather
   .. autoclass:: list_scatter


conv
---------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.conv

   .. autoclass:: conv
   .. autoclass:: conv_transpose


elementwise\_binary
------------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.elementwise_binary

   .. autoclass:: add
   .. autoclass:: equal
   .. autoclass:: floor_div
   .. autoclass:: greater
   .. autoclass:: greater_equal
   .. autoclass:: less
   .. autoclass:: less_equal
   .. autoclass:: logical_and
   .. autoclass:: logical_or
   .. autoclass:: logical_xor
   .. autoclass:: maximum
   .. autoclass:: minimum
   .. autoclass:: mod
   .. autoclass:: mul
   .. autoclass:: not_equal
   .. autoclass:: real_div
   .. autoclass:: pow
   .. autoclass:: sub


elementwise\_unary
-----------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.elementwise_unary

   .. autoclass:: abs
   .. autoclass:: acos
   .. autoclass:: asin
   .. autoclass:: atan
   .. autoclass:: atanh
   .. autoclass:: ceil
   .. autoclass:: clip
   .. autoclass:: cos
   .. autoclass:: cosh
   .. autoclass:: erf
   .. autoclass:: exp
   .. autoclass:: exp2
   .. autoclass:: floor
   .. autoclass:: inverse
   .. autoclass:: log
   .. autoclass:: logical_not
   .. autoclass:: round
   .. autoclass:: rsqrt
   .. autoclass:: sign
   .. autoclass:: sin
   .. autoclass:: sinh
   .. autoclass:: sqrt
   .. autoclass:: square
   .. autoclass:: tan
   .. autoclass:: tanh
   .. autoclass:: threshold
   .. autoclass:: cast


image\_resizing (iOS 15)
--------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.image_resizing

   .. autoclass:: affine
   .. autoclass:: upsample_nearest_neighbor
   .. autoclass:: upsample_bilinear
   .. autoclass:: resample
   .. autoclass:: resize_nearest_neighbor
   .. autoclass:: resize_bilinear
   .. autoclass:: crop_resize
   .. autoclass:: crop

image\_resizing (iOS 16+)
--------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS16.image_resizing

   .. autoclass:: resample


linear
-----------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.linear

   .. autoclass:: linear
   .. autoclass:: matmul
   .. autoclass:: einsum


normalization
------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.normalization

   .. autoclass:: batch_norm
   .. autoclass:: instance_norm
   .. autoclass:: l2_norm
   .. autoclass:: layer_norm
   .. autoclass:: local_response_norm


pool
---------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.pool

   .. autoclass:: avg_pool
   .. autoclass:: l2_pool
   .. autoclass:: max_pool


random
-----------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.random

   .. autoclass:: random_bernoulli
   .. autoclass:: random_categorical
   .. autoclass:: random_normal
   .. autoclass:: random_uniform


recurrent
--------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.recurrent

   .. autoclass:: gru
   .. autoclass:: lstm
   .. autoclass:: rnn


reduction
--------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.reduction

   .. autoclass:: reduce_argmax
   .. autoclass:: reduce_argmin
   .. autoclass:: reduce_l1_norm
   .. autoclass:: reduce_l2_norm
   .. autoclass:: reduce_log_sum
   .. autoclass:: reduce_log_sum_exp
   .. autoclass:: reduce_max
   .. autoclass:: reduce_mean
   .. autoclass:: reduce_min
   .. autoclass:: reduce_prod
   .. autoclass:: reduce_sum
   .. autoclass:: reduce_sum_square
  

scatter\_gather
--------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.scatter_gather

   .. autoclass:: gather
   .. autoclass:: scatter
   .. autoclass:: gather_along_axis
   .. autoclass:: scatter_along_axis
   .. autoclass:: gather_nd
   .. autoclass:: scatter_nd


tensor\_operation (iOS 15)
----------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.tensor_operation

   .. autoclass:: band_part
   .. autoclass:: cumsum
   .. autoclass:: fill
   .. autoclass:: non_maximum_suppression
   .. autoclass:: non_zero
   .. autoclass:: one_hot
   .. autoclass:: pad
   .. autoclass:: range_1d
   .. autoclass:: tile
   .. autoclass:: argsort
   .. autoclass:: topk
   .. autoclass:: flatten2d
   .. autoclass:: shape
   .. autoclass:: concat
   .. autoclass:: split
   .. autoclass:: stack
   .. autoclass:: identity


tensor\_operation (iOS 16+)
----------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS16.tensor_operation

   .. autoclass:: topk


tensor\_transformation (iOS 15)
---------------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS15.tensor_transformation

   .. autoclass:: depth_to_space
   .. autoclass:: expand_dims
   .. autoclass:: reshape
   .. autoclass:: reverse
   .. autoclass:: reverse_sequence
   .. autoclass:: slice_by_index
   .. autoclass:: slice_by_size
   .. autoclass:: space_to_depth
   .. autoclass:: squeeze
   .. autoclass:: transpose
   .. autoclass:: pixel_shuffle
   .. autoclass:: sliding_windows


tensor\_transformation (iOS 16+)
---------------------------------------------------------------------

.. automodule:: coremltools.converters.mil.mil.ops.defs.iOS16.tensor_transformation

   .. autoclass:: pixel_unshuffle

