# Fire-detection-using-yolov10

You need to create a conda environment as explained in the official yolov10 github ripository.

conda create -n yolov10 python=3.9

conda activate yolov10

pip install -r requirements.txt

pip install -e .

But to use cuda in training you need to do this step "conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.8 -c pytorch -c nvidia" before installing the previous requirements.

All next steps are explained in the notebook called file.ipynb.
