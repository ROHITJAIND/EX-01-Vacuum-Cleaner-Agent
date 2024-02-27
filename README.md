# Developing AI Agent with PEAS Description

### Aim:
To find the PEAS description for the given AI problem and develop an AI agent.
### Theory:
<h3>Medicine prescribing agent:</h3>
<p>Such this agent prescribes medicine for fever (greater than 98.5 degrees) which we consider here as unhealthy, by the user temperature input, and another environment is rooms in the hospital (two rooms). This agent has to consider two factors one is room location and an unhealthy patient in a random room, the agent has to move from one room to another to check and treat the unhealthy person. The performance of the agent is calculated by incrementing performance and each time after treating in one room again it has to check another room so that the movement causes the agent to reduce its performance. Hence, agents prescribe medicine to unhealthy.</p>
<hr>
<h3>PEAS DESCRIPTION:</h3>
<table>
  <tr>
    <td><strong>Agent Type</strong></td>
    <td><strong>Performance</strong></td>
     <td><strong>Environment</strong></td>
    <td><strong>Actuators</strong></td>
    <td><strong>Sensors</strong></td>
  </tr>
    <tr>
    <td><strong>Medicine prescribing agent</strong></td>
    <td><strong>Treating unhealthy, agent movement</strong></td>
     <td><strong>Rooms, Patient</strong></td>
    <td><strong>Medicine, Treatment</strong></td>
    <td><strong>Location, Temperature of patient</strong></td>
  </tr>
</table>

### Design Steps:
STEP 1: Identifying the input:(Temperature from patients, Location.)<br>
STEP 2:Identifying the output:(Prescribe medicine if the patient in a random has a fever.)<br>
STEP 3:Developing the PEAS description:(PEAS description is developed by the performance, environment, actuators, and sensors in an agent.)<br>
STEP 4:Implementing the AI agent:(Treat unhealthy patients in each room. And check for the unhealthy patients in random room.)<br>
STEP 5:(Measure the performance parameters: For each treatment performance incremented, for each movement performance decremented)<br>
