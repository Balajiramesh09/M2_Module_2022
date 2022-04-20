 <h1>THERMAL CONTROL SYSTEM</h1>

<h2>INTRODUCTION:</h2>

A Thermal control system is basically used to control the temperature anywhere like in a car, bus, livingroom, bedroom etc. so, let's take a car as an example in this projec,When a user or driver of the car gets settled on a car, the button sensor will get activated. After that, the user will get access to turn on the heater. The temperature sensor will keep monitoring the temperature and sends the analog value to the microcontroller. The microcontroller then process the analog input of the temperature sensor and sends produces as a temperature value through the  serial communication. 


<h2>CONDITIONS:</h2>

</head>
<body>
	<table>
		<thead>
			<tr>
				<th>ADC Value<br>(Temperature Sensor)</th>
				<th>Output PWM</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>&nbsp;0 - 200</td>
				<td>20% - 20℃&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;210 - 500</td>
				<td>&nbsp;40% - 25℃</td>
			</tr>
			<tr>
				<td>&nbsp;510 - 700</td>
				<td>70% - 29℃&nbsp;</td>
			</tr>
			<tr>
				<td>&nbsp;710&nbsp; - 1024</td>
				<td>95% - 33℃&nbsp;</td>
			</tr>
		</tbody>
	</table>
  
<h2>SWOT ANALYSIS:</h2>
  
  ![swot](https://user-images.githubusercontent.com/101571637/164236928-1061984c-f087-4a73-8917-b7904645e2d2.jpg)

  
  <h1>4W's AND 1H:</h1>
  
<h2>WHO:</h2>
  For every user who wants high temperature in low temperatutre region can be identified.
  
<h2>WHAT:</h2> 
  This is an application where one can adjust their required temperature to get comfort from the external environmental temperatures.
  
<h2>WHEN:</h2>
  This is used mostly in winter seasons.
  
<h2>WHERE:</h2>
  This application can be implemented in low twmpwrature regions.
  
<h2>HOW:</h2>
  This application is implemented in SimulIDE using Visual Studio code.
