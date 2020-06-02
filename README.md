# Pre-trained models for facial landmark prediction tasks of NeurIPS 2020 paper with id 1001

This repository includes the weight files of the pre-trained neural networks for the facial landmark prediction tasks of the NeurIPS paper with ID 1001. The code for the facial landmark prediction tasks is submitted in the `constraintnet_facial_lm_pred` repository as a part of the supplementary material (zip file). The `constraintnet_facial_lm_pred` repository does not contain the weight files due to the limited size of the supplementary material. For
using the weight files in the submitted code repository, there are two options:

* Replace the ./experiments directory in the submitted `constraintnet_facial_lm_pred` repository with the
  ./experiments directory of this repository.
* Copy the weight files within the ./experiments directory of this repository to
  the corresponding subdirectory in the ./experiments directory of the
submitted `constraintnet_facial_lm_pred` repository:
  * ./experiments/exp_1/bb/ckpts/bb_ckpt -> constraintnet_facial_lm_pred/experiments/exp_1/bb/ckpts/bb_ckpt ,
  * ./experiments/exp_1/bb_rel/ckpts/bb_rel_ckpt -> constraintnet_facial_lm_pred/experiments/exp_1/bb_rel/ckpts/bb_rel_ckpt ,
  * ./experiments/exp_1/resnet/ckpts/resnet_exp_1_ckpt -> constraintnet_facial_lm_pred/experiments/exp_1/resnet/ckpts/resnet_exp_1_ckpt ,
  * ./experiments/exp_2/triangle/ckpts/triangle_ckpt -> constraintnet_facial_lm_pred/experiments/exp_2/triangle/ckpts/triangle_ckpt ,
  * ./experiments/exp_2/sector_of_a_circle/ckpts/sector_ckpt -> constraintnet_facial_lm_pred/experiments/exp_2/sector_of_a_circle/ckpts/sector_ckpt ,
  *  ./experiments/exp_2/resnet/ckpts/resnet_exp_2_ckpt -> constraintnet_facial_lm_pred/experiments/exp_2/resnet/ckpts/resnet_exp_2_ckpt .




