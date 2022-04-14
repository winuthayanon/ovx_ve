# Ovariectomized: Vehicle or Estrogen (ovx_ve):

Notebook of scRNA-seq analysis from cells collected from the mouse oviduct.

Adult (8-12 weeks old) C57B6/J mice were ovariectomized (OVX) and treated with either vehicle (V) or estrogen (E) for 24 hours (*n*=5-6 mice/treatment/group). The oviducts were dissected into infundibulum + ampulla (AmpIsth) or isthmus + uterine-tubal junction (IsthUTJ) before single cell isolation.

# How to create new conda environment
conda env create -n winuthayanon-lab -f winuthayanon-lab.yml
conda activate winuthayanon-lab

# How to add kernel
python -m ipykernel install --user --name winuthayanon-lab --display-name "winuthayanon-lab"

# How to remove kernel
jupyter kernelspec list
jupyter kernelspec remove -f winuthayanon-lab

# How to remove conda environment
conda env list
conda remove --name winuthayanon-lab --all

# How to export conda environment
conda-env export -n winuthayanon-lab -f winuthayanon-lab.yml 
