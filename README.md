# Malnet-Graph-tiny

NOTE：Run this notebook in SageMaker instance instead of SageMaker Studio

paper: https://mal-net.org/ https://mal-net.org/#Citation

code: https://github.com/safreita1/malnet-graph THANKS

datasets: http://malnet.cc.gatech.edu/graph-data/


Core requirements:
1. PyTorch1.13.1+py39
2. extended pre-built container + BYOC
3. SageMaker+Malnet-Graph
4. BYOS 
5. using FastFile mode to access dataset files in S3

Steps:
1. Generate Dockerfile
2. Generate requirements.txt
3. Build docker image
4. SageMaker setting
5. Download datasets and upload to s3
6. Upload container image to Amazon ECR
7. Start SageMaker training job

Please open the malnet-graph.ipynb file to walk through.
