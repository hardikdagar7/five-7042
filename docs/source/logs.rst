Latest Logs From Latest Build
==============================

Generated On: 2024-12-01 04:48:05 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-01_04:45:32] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-01_04:45:35] STEP 2: Create topics started

  [INFO 2024-12-01_04:45:49] STEP 2: Completed

  [INFO 2024-12-01_04:45:54] STEP 3: producing data started

  [INFO 2024-12-01_04:45:57] MQTT connection established...

  [INFO 2024-12-01_04:45:57] STEP 4: Preprocessing started

  [INFO 2024-12-01_04:45:59] STEP 4: Preprocessing started

  [INFO 2024-12-01_04:46:00] STEP 7: Visualization started

  [INFO 2024-12-01_04:46:07] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-01_04:46:17] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-01_04:46:18] STEP 8: Starting docker push for: hardikdagar0207/five-7042-amd64

  [INFO 2024-12-01_04:46:23] STEP 9: Starting privateGPT

  [INFO 2024-12-01_04:46:33] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-01_04:46:39] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 74174610d3ec hardikdagar0207/five-7042-amd64 - message=0

  [INFO 2024-12-01_04:47:59] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/five-7042-amd64 - message=0

  [INFO 2024-12-01_04:48:05] STEP 10: Started to build the documentation

  [INFO 2024-12-01_04:48:05] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


