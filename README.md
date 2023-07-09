```
conda create -n semantic-topic-modeling python=3.9
conda activate semantic-topic-modeling
module load cuda/11.6u2
module load singularity/3.9.5
singularity pull tensorflow-notebook.sif docker://jupyter/tensorflow-notebook
singularity run --nv tensorflow-notebook.sif
```