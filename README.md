 # PyCondrop 0.19.09

## README

	PyCondrop is a set of computer vision utilities for photovoltaic (PV) glass soiling analysis,
	for evaluation of anti-soiling and self-cleaning surface coatings.
	The programs included in the software package allow the user to:

### PyDrop
	Analyze dew formation on the PV glass in laboratory and field conditions
		- Determine the dew drop size and location
		- Help user to calculate dew drop slide off times
	Automatically calculate and map the area and location of parts of glass cleaned by sliding dewdrops using OpenCV methods
		- Smart detection of dew water drops on the surface of the PV glass
		- Motion detaction and drop path calculation
### PySurfaceArea
	Provide tools for quantification of dust deposition on the surface of PV glass
		- Using light refleaction intensity methods


## REQUIREMENTS

	PyCondrop is written in Python 3.6.
	Running the application in Anaconda Python environment is advised.
	The following python modules are required, please use pip to install the dependancies:

```bash
pip install opencv-python
pip install scikit-image, scikit-learn, scipy, scimage
pip install numpy, pandas
pip install matplotlib
pip install imutils, pathlib, pytest-shutil
pip install -U wxPython
pip install tqdm
```

## TROUBLESHOOTING

	Any trouble encountered with the software should be reported to:
	Illya Nayshevsky
	illya.nayshevsky@csi.cuny.edu

## License
[MIT](https://choosealicense.com/licenses/mit/)


Chemistry Department, College of Staten Island
2800 Victory Blvd, Building 6S
Staten Island, NY 10314
https://www.csi.cuny.edu/academics-and-research/departments-programs/chemistry



