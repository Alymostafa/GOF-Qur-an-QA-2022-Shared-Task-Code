To Run the code:<br>
1.) Run the cells in the notebook sequentially, except for the focal loss, run it if you want to change from cross-entropy to focal loss. <br>
2.) This code is our final phase of model that trained on Ar-TyDi QA  + ArSQuAD + ARCD + QRCD. <br>
3.) The checkpoints of the model trained on Ar-TyDi QA  + ArSQuAD + ARCD is downloaded and loaded when start training. <br>
4.) If you want to replicate the focal loss experiment change the model from loading checkpoint to ```aubmindlab/araelectra-base-discriminator``` and run focal loss cell.
