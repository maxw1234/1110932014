開發環境 : anaconda navigator jupyterlab

conda 虛擬環境設置 python version : 3.10.19 pytorch version : 2.11.0 cuda version : 13.0

模型檔案存放位置(Reflection-Removal-with-Auxiliary-Techniques-main) : C:\Users\user\jupyter_lab_work\Reflection-Removal-with-Auxiliary-Techniques-main (jupyter_lab_work為新建資料夾)

訓練及驗證資料位置 : Reflection-Removal-with-Auxiliary-Techniques-main\unified_dataset (train、val)

訓練指令 : python train.py --data_dir ./unified_dataset/train --save_dir ./checkpoints/wacv_model --epochs 100 --batch_size 8
