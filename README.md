# BFVM19PROG1

Programming 1 course for DSLS

see also https://fennaf.gitbook.io/bfvm19prog1/

- `assessment` folder: In this folder you find all the assignments
- `data` folder: In this folder you find data for the tutorials and assignments
- `scripts` folder: Demo scripts such as unit testing scripts and creating sql database
- `study cases` folder: Examples of study cases for analysis of both continous and categorical data
- `tutorials` folder: Tutorials for specific topics

# Install on your own system
Run the following code in your terminal (using a prefered virtual environmnent name)

```
#create virtual environment
python3 -m venv {path/name}
source {path/name}/bin/activate
#create jupyter notebook kernel for venv
pip install ipykernel
python -m ipykernel install --user --name={name}
#install required packages
pip install numpy
pip install pandas
pip install bokeh
```

#run jupyter notebook
```
jupyter notebook
```
after running the notebook select the just created kernel

contact information: f.feenstra@pl.hanze.nl
