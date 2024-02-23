# DocTamper
The DocTamper dataset is now avaliable at [BaiduDrive](https://pan.baidu.com/s/1nEEnq1ZWIem7wnkQ1YdTNw?pwd=od9k) and Google Drive ([part1](https://drive.google.com/file/d/150teGvJbtWSULljrh9Sp_NrTlEXKPsTm/view?usp=drive_link) and [part2](https://drive.google.com/file/d/1rJOMEu8c25ZxpWliCXmxRk6wFULZS7Z2/view?usp=share_link)).


The DocTamper dataset is only available for non-commercial use, you can request a password for it by sending an email  __with education email__ to 202221012612@mail.scut.edu.cn explaining the purpose.

To visualize the images and their corresponding ground-truths from the provided .mdb files, you can run this command "python vizlmdb.py --input DocTamperV1-FCD --i 0".

I delay the release of training codes as forced by my supervisor and the cooperative enterprise who bought them. My training pipline for DocTamper dataset and the IoU metric heavily brought from a famous project in this area, the results of  the paper can be easily re-produced with [it](https://github.com/DLLXW/data-science-competition/blob/main/tianchi/ImageForgeryLocationChallenge/utils/deeplearning_qyl.py), you just need to adjust the loss functions and the learing rate decay curve. I also used its [augmentation pipline](https://github.com/DLLXW/data-science-competition/blob/main/tianchi/ImageForgeryLocationChallenge/dataset/RSCDataset.py) except for (RandomBrightnessContrast, ShiftScaleRotate, CoarseDropout).


Open Source Scheme: <br>
1、Inference models and codes: June, 2023. <br>
2、Training codes: TBD. <br>
3、Data synthesis code: Within 2024. <br>


Any question about this work please contact 202221012612@mail.scut.edu.cn.

# DocTamper dataset

Dear researcher,


Thank you for your attention. the password of the dataset is IntSig_DLVC_411


After unrar, the resulting .mdb files should be opened by Python scripts:

To visualize the images and their corresponding ground-truths from the provided .mdb files, you can run the command like "python vizlmdb.py --input DocTamperV1-FCD --i 0". The vizlmdb.py is https://github.com/qcf-568/DocTamper/blob/main/vizlmdb.py The dataloader for training or inference can be refered to Line43~Line107 of https://github.com/qcf-568/DocTamper/blob/main/models/eval_dtd.py To run the eval_dtd.py, you can refer to this Colab Notebook https://colab.research.google.com/drive/1rWaSKy2Rsy5welyvj6FbzF01o2zv8ips?usp=sharing Kind Regards,

Chenfan Qu


