# python_WS_2019

# installation
* open the terminal
```bash
git clone https://github.com/andreassteffen/python_WS_2019.git
``` 
## install all dependencies
```bash
bash
cd python_WS_2019
conda env create -f environment.yml

conda init bash
exit
bash
cd python_WS_2019
conda activate python_workshop_2019
conda install ipykernel
conda install -c conda-forge matplotlib-venn
python -m ipykernel install --user --name python_workshop_2019
```
