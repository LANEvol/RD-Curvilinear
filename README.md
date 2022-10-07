# RD-Curvilinear
This code was developed by Ebrahim Jahanbakhsh in the lab of Michel Milinkovitch (LANE) https://www.lanevol.org

Corresponding author email : Ebrahim.Jahanbakhsh@unige.ch

## Description:

	RD-Curvilinear is a GPU-based finite-difference implementation used to simulate the reaction-diffusion process on a structured curvilinear grids with no-flux boundary conditions at the domain borders.

## Files:

	build folder:
		RD_Curvilinear
	example folder:
		Contains data for test examples below.

## Requirements:

	NVIDIA graphics cards (compute capabilities > 3.0)
	Linux operating system

## Run:

	To run the test example type :
		cd example
		../build/RD_Curvilinear controlFile.txt
	Inital conditions and the intermediate states will be stored as VTK mesh format.
