This directory contains files to run the attack on GTSRB-CNN. Most of the setup is the same as the one for the [LISA-CNN](https://github.com/evtimovi/robust_physical_perturbations/tree/master/lisa-cnn-attack). 

The attack can be run with `run_gennoise_yadav.sh` but you need to download and unzip the `gtsrb_usstop.zip` file from [this Google Drive folder](https://drive.google.com/drive/u/1/folders/1DbsJtE6KT3J15TzcCoVrvoHeCVHhSxtc). When downloading and unzipping, make sure you place the checkpoint files in a `models` subfolder or modify the `model_path` parameter in `run_gennoise_yadav.sh`. When that is done, you can run `run_classify.py` to classify images with this model (change the `srcimgs` parameter to point to a folder of the images you want classified). 