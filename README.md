# SA-Cup---Rocket Flight-Simulator

# Methodology
The flight simulator is being developed using Python. The software uses the thrust curve data, Rocket data to run a simulation loop, which calculates all the variables at each time step, thus simulating the entire Flight.

# Thrust curve of Estes F-15 rocket motor used to develop and test the simulator
<img width="945" alt="image" src="https://user-images.githubusercontent.com/73430464/174431943-57a3e36b-72b0-4e1f-98d1-c6ebe4b95ecb.png">



## Previous Simulator result on a sample rocket

### 1)
<img width="942" alt="image" src="https://user-images.githubusercontent.com/73430464/171872454-eebe3ef9-80e5-4432-ad62-f6cba996bf92.png">

### 2)
<img width="960" alt="image" src="https://user-images.githubusercontent.com/73430464/174255929-c18b7e7b-4b12-43ab-b5b2-2ef127434206.png">

### 3)
<img width="942" alt="image" src="https://user-images.githubusercontent.com/73430464/174423192-511b7804-0426-4d9a-a281-e15c49ea00f9.png">

### 4)

<img width="954" alt="image" src="https://user-images.githubusercontent.com/73430464/174426385-abd0ed67-7c6b-4702-a050-ced3e39e97ef.png">

### 5)
<img width="960" alt="image" src="https://user-images.githubusercontent.com/73430464/174426980-bf333b07-6de3-4730-bf57-c94f693d5596.png">

### 6) 
As can be seen, the acceleration gradually increases from -9.8 to 0 and then gradually increases from there. The graph looks very similar to the Open Rocket graph. Our next step is integrating Parabolic motion into the simulator. 
<img width="960" alt="image" src="https://user-images.githubusercontent.com/73430464/174431569-2d70d247-2cc4-4739-a7e0-f573a0614ef6.png">

## Current Simulator result on a sample rocket
Converted the 1D model into a 2D model. The trajectory of the rocket considered is shown below : 
<img width="739" alt="image" src="https://user-images.githubusercontent.com/73430464/177479918-ab3578a0-eb56-4ebb-a40a-ae0fe3932520.png">

The final output is shown below for launch angle = 10 degrees from the y axis: 

<img width="960" alt="image" src="https://user-images.githubusercontent.com/73430464/177480100-cded4465-b20f-456f-a2fc-f50cc2c4d825.png">


## Current OpenRocket Simulation result on a sample rocket
<img width="946" alt="image" src="https://user-images.githubusercontent.com/73430464/171843854-0cb9951f-bd4d-4e7d-868a-8fda7eec96a9.png">
