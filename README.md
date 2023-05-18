# USI_GDL_ST-SSL
Reproductivity paper on Spatio-Temporal Self-Supervised Learning for Traffic Flow Prediction

# Requirements
numpy==1.21.2 <br>
pandas==1.3.5 <br>
PyYAML==6.0 <br>
torch==1.10.1 <br>

# How to run the code

The code can be ran in a computational cluster by:
1. clone the repository to the cluster
2. Load anaconda module (module load <anaconda-module-name>
3. create a conda environment named stssl and install torch, pyyaml, numpy, pandas
4. activate the environment
5. submit a job with slurm with command sbatch slurm_files/run_bike1.slrm 


# Citation
@inproceedings{ji2023spatio, <br>
  title={Spatio-Temporal Self-Supervised Learning for Traffic Flow Prediction}, <br>
  author={Ji, Jiahao and Wang, Jingyuan and Huang, Chao and Wu, Junjie and Xu, Boren and Wu, Zhenhe and Zhang, Junbo and Zheng, Yu}, <br>
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, <br>
  year={2023}<br>
}
