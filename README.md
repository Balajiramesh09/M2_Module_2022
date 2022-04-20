# THERMAL CONTROL SYSTEM

<h2>INTRODUCTION:</h2>

A Thermal control system is basically used to control the temperature anywhere like in a car, bus, livingroom, bedroom etc. so, let's take a car as an example in this projec,When a user or driver of the car gets settled on a car, the button sensor will get activated. After that, the user will get access to turn on the heater. The temperature sensor will keep monitoring the temperature and sends the analog value to the microcontroller. The microcontroller then process the analog input of the temperature sensor and sends produces as a temperature value through the  serial communication. 


<h2>SIMULATION:</h2>

This process takes place as, first we have to code the thermal control system's base code in embedded c language using any IDE then, the working is demonstrated using an 
opensource simulation software called SimulIDE.


<h2>WORKING:</h2>

The buttons must be switched ON before the application starts to work. The potentiometer acts as a temperature sensor. It gives the signal which is then converted by ADC and used to make a PWM signal of the corresponding duty cycle, whcih can be seen in the oscilloscope. As the potentiometer is varied, the message which contains the detected temperature is shown in the serial monitor.


<h1>SDLC ACTIVITY BASED LEARNING:</h1>

* Codacy Analysis:


![Codacy](https://user-images.githubusercontent.com/101571637/164258116-26611ec8-9dd7-4a3a-9d29-45abff5f5393.JPG)


* Valgrind Analysis:

[![Valgrind](https://github.com/Balajiramesh09/M2_Module_2022/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/Balajiramesh09/M2_Module_2022/actions/workflows/Valgrind.yml)


* C/C++ Analysis:

[![C/C++ CI](https://github.com/Balajiramesh09/M2_Module_2022/actions/workflows/c-build.yml/badge.svg)](https://github.com/Balajiramesh09/M2_Module_2022/actions/workflows/c-build.yml)


<h1>FOLDER STRUCTURE:</h1>



</head>
<body>
	<table>
		<thead>
			<tr>
				<th>FOLDERS</th>
				<th>DESCRIPTION</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td><span style="color: rgb(49, 48, 48); background-color: rgb(255, 255, 255);">&nbsp;1_Requirements</span></td>
				<td>This folder contains documents detailing requirements with regard to the project.</td>
			</tr>
			<tr>
				<td>2_Architecture&nbsp;</td>
				<td>This folder contains documents specifying the design details with regard to the project.&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;3_Implementation</td>
				<td>This folder contains all the codes and documentation of the project.&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;4_TestplanAndOutput</td>
				<td>This folder contains documents with test plans and procedures with regard to project.</td>
			</tr>
			<tr>
				<td>5_Report&nbsp;</td>
				<td>This folder contains the report of the project.&nbsp;</td>
			</tr>
			<tr>
				<td>6_ImagesAndVideos&nbsp;</td>
				<td>&nbsp;This folder contains the images of the completed project.</td>
			</tr>
			<tr>
				<td>7_Simulation&nbsp;</td>
				<td>This folder contains the files necessary for simulation.&nbsp;</td>
			</tr>
		</tbody>
	</table>
</body>
</html>
