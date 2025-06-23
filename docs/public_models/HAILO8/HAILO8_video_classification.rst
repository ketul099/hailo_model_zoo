Public Pre-Trained Models
=========================

.. |rocket| image:: ../../images/rocket.png
  :width: 18

.. |star| image:: ../../images/star.png
  :width: 18

Here, we give the full list of publicly pre-trained models supported by the Hailo Model Zoo.

* Network available in `Hailo Benchmark <https://hailo.ai/products/ai-accelerators/hailo-8-ai-accelerator/#hailo8-benchmarks/>`_ are marked with |rocket|
* Networks available in `TAPPAS <https://github.com/hailo-ai/tappas>`_ are marked with |star|
* Benchmark and TAPPAS  networks run in performance mode
* All models were compiled using Hailo Dataflow Compiler v3.31.0



.. video_classification:

--------------

kinetics400
^^^^^^^^

.. list-table::
   :widths: 31 9 7 11 9 8 8 8 7
   :header-rows: 1

   * - Network Name
     - float mAP
     - Hardware mAP
     - FPS (Batch Size=1)
     - FPS (Batch Size=8)
     - Links
     - Input Resolution (HxWxC)
     - Params (M)
     - OPS (G)
   * - r3d_18
     - 48.9
     - 49.2
     - 40
     - 78
     - `S <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/VideoClassification/r3d_18/pretrained/09-05-2024/r3d_18.zip>`_  `PR <https://pytorch.org/vision/stable/models.html#video-classification>`_ `H <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.15.0/hailo8/r3d_18.hef>`_ `PR <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.15.0/hailo8/r3d_18_profiler_results_compiled.html>`_
     - 112x112x48
     - 33.42
     - 81.4

