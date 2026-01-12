開發環境 : anaconda navigator jupyterlab

conda 虛擬環境設置
python version : 3.10.19
pytorch version : 2.11.0
cuda version : 13.0

模型檔案存放位置(IBCLN) : C:\Users\user\jupyter_lab_work\IBCLN (jupyter_lab_work為新建資料夾)

訓練及驗證資料位置 : IBCLN\datasets\reflection (trainA、trainB、valA、valB)

訓練指令 : python train.py --dataroot datasets/reflection --name IBCLN --model IBCLN --dataset_mode unaligned --no_flip --gpu_id 0 --display_id -1 --batch_size 8 --num_threads 12
