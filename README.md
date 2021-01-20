To run on CPU, be sure to 
- uncomment `CUDNN=0` and `GPU=0` and comment `CUDNN=1` and `GPU=1` in `Makefile`. 
- uncomment `make` and comment `make GPU=1 all` in `build`.
