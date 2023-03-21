

# RUN

```
setenv PATH /usr/local/GNU/gcc11/bin:/usr/local/cuda-11.1/bin:$PATH
setenv LD_LIBRARY_PATH /usr/local/GNU/gcc11/lib64:/usr/local/cuda-11.1/lib64:$LD_LIBRARY_PATH
conda activate salient
```

```
cd experiments
./initial_setup.sh
```

```
env CUDA_VISIBLE_DEVICES=1 ./performance_breakdown_salient.sh ogbn-papers100M
```


# INSTALL
