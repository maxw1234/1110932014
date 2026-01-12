開發環境 : anaconda navigator jupyterlab

conda 虛擬環境設置 python version : 3.10.19 pytorch version : 2.11.0 cuda version : 13.0

模型檔案存放位置(YTMT-Strategy-main) : C:\Users\user\jupyter_lab_work\YTMT-Strategy-main (jupyter_lab_work為新建資料夾)

訓練及驗證資料位置 : YTMT-Strategy-main\Final_Dataset (train、val)

第一階段訓練指令 : python train_sirs.py --inet ytmt_ucs --model ytmt_model_sirs --name ytmt_ucs_sirs --hyper --if_align --batchSize 8

第二階段訓練指令 : python train_sirs_twostage.py --inet ytmt_ucs --model twostage_ytmt_model --name ytmt_stage2 --hyper --if_align --batchSize 4 --icnn_path "C:\Users\user\jupyter_lab_work\YTMT-Strategy-main\checkpoints\ytmt_ucs_sirs\ytmt_ucs_sirs_040_00114320.pt"(ytmt_ucs_sirs_040_00114320.pt 為第一階段訓練的模型權重)
