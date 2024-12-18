#Thermal Sim by Peter Xiong and Anoushka
#Implementation Steps
To run the simulation, use the following command-line format:
./therm <dimx> <dimy> <dimz> <nTicks> <dx> <dy> <dz> <dt>
	Arguments:
•	dimx: The number of tiles along the x-dimension.
•	dimy: The number of tiles along the y-dimension.
•	dimz: The number of layers along the z-dimension.
•	nTicks: The total number of simulation timesteps to compute.
•	dx: The size of each tile in the x-direction (in meters).
•	dy: The size of each tile in the y-direction (in meters).
•	dz: The thickness of each layer in the z-direction (in meters).
•	dt: The time increment per simulation tick (in seconds).

Note: Thermal conductivity and thermal diffusivity values are currently hard coded within the source code. Adjust these values in the code prior to compilation if different material properties are needed. 

To run visualization:
Mount vizualization.ipynb in colab and changed path to desired
csv file. Sample csv files are included. Run code to get plot.
