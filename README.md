# d2l-zh

```zsh

echo "# d2l-zh" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:tishenme/d2l-zh.git
git push -u origin main

conda info --envs
conda env list
conda deactivate
conda remove -n d2l --all -y
conda create --name d2l python=3.9 -y
conda activate d2l
pip list
pip install --upgrade pip
pip install --upgrade setuptools

pip install torch==2.0.0 torchvision==0.15.1
pip install d2l==1.0.3

conda activate d2l
cd ./d2l-zh-2.0.0/pytorch
jupyter notebook

```
