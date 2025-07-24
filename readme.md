## Create environment
```
conda create -n synthetic-data python=3.12 
```

## Active environment
```
conda activate synthetic-data
```
## Start vllm as service
```
vllm serve unsloth/Llama-3.2-3B-Instruct --port 8000 --max-model-len 4096
```