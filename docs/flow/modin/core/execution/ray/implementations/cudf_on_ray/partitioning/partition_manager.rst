cuDFOnRayDataframePartitionManager
""""""""""""""""""""""""""""""""""

This class is the specific implementation of :py:class:`~modin.core.execution.ray.generic.partitioning.partition_manager.GenericRayDataframePartitionManager`.
It serves as an intermediate level between :py:class:`~modin.core.execution.ray.implementations.cudf_on_ray.dataframe.dataframe.cuDFOnRayDataframe`
and :py:class:`~modin.core.execution.ray.implementations.cudf_on_ray.partitioning.partition.cuDFOnRayDataframePartition` class.
This class is responsible for partition manipulation and applying a function to
block/row/column partitions.

Public API
----------

.. autoclass:: modin.core.execution.ray.implementations.cudf_on_ray.partitioning.partition_manager.cuDFOnRayDataframePartitionManager
  :members:
