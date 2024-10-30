将训练集和测试集放在data文件夹下 参考 config文件
训练和测试参考如下
python main.py --config config/uav-cross-subjectv2/train.yaml --work-dir work_dir/2104 --model_saved_name runs/2104 --device 0 --batch-size 16 --test-batch-size 16 --warm_up_epoch 5 --only_train_epoch 100 --seed 777
python main.py --config config/uav-cross-subjectv2/test.yaml --work-dir work_dir/3003 --model_saved_name runs/3003 --device 0 --batch-size 128 --test-batch-size 128 --weights "D:/AI Competition/TE-GCN-main/runs/2103-49-25650.pt"
