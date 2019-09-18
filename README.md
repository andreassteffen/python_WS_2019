# python_WS_2019

# installation
## clone this rep via 
git clone https://github.com/andreassteffen/python_WS_2019.git

## install all dependencies
* open the terminal
* cd python_WS
* type conda env create -f environment.yml
* type python -m ipykernel install --user --name python_workshop_2019

in addition:
* pip install matplotlib-venn


# data download
please download the following files:
[url](https://depmap.org/portal/download/)

cd python_WS_2019/data

* sample info:
 * wget https://ndownloader.figshare.com/files/16757723 -o sample_info.csv
* mutation data:
 * wget https://ndownloader.figshare.com/files/16757702 -o mutation.csv
* expression data:
 * wget https://ndownloader.figshare.com/files/16757690 -o expression.csv

and also:
the mask_rcnn_balloon.h5
 model from https://github.com/matterport/Mask_RCNN/releases
