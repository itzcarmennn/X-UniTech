# X-UniTech Team, Malaysia

Welcome to X-UniTech Team Malaysia! 

This repository showcases our final robot design, developed to complete both the **Open Challenge** and **Obstacle Challenge**. For an overview of our development journey from **Generation 1 to Generation 4**, please refer to the [**Robot Development & Iteration Cycle**](https://github.com/itzcarmennn/X-UniTech/blob/4292ab41017db0be74e6131bf3cbaa6cbdb87c5d/others/Robot%20Development%20%26%20Iteration%20Cycle.pdf). For detailed information about our robot's design, engineering decisions, calculations, and testing results, please refer to our **[Engineering Journal](PASTE_YOUR_ENGINEERING_JOURNAL_LINK_HERE)**.

# Table of Contents

# Summary Video
This 6-minute video provides a brief overview of our project and its documentation. We encourage you to watch it for a quick and clear understanding of our work!

# Team Members
We are X-UniTech, a team of two teacher trainees from Malaysia, made up of **Raymond Ting Yih Wei**, the brain behind the code, and **Carmen Heng Jia Min**, the hands behind the robot. Together, we turn ideas into robots!

<p align="center">
<img width="700" alt="Team Photo (Version 2)" src="https://github.com/user-attachments/assets/ab3b53d3-a38d-4b28-a1b8-44ece449975a" />
</p>

# Robot Overview

<p align="center">
<img width="600" alt="20261107_155658" src="https://github.com/user-attachments/assets/2813e15e-82a7-43a1-ac9d-37d74dccddfa" />
</p>

<table>
  <tr>
    <td align="center"><strong>Top View</strong><br><img src="https://github.com/user-attachments/assets/295aefa3-17d0-49da-a170-f994833643bf" width="300" alt="Top View"></td>
    <td align="center"><strong>Front View</strong><br><img src="https://github.com/user-attachments/assets/a1fb0da6-7ff4-4987-8d24-5d465aa64d5b" width="300" alt="Front View"></td>
    <td align="center"><strong>Left View</strong><br><img src="https://github.com/user-attachments/assets/c2df38c0-c39f-470d-aa3e-501a581375d2" width="300" alt="Left View"></td>
  </tr>
  <tr>
    <td align="center"><strong>Bottom View</strong><br><img src="https://github.com/user-attachments/assets/8d5aa74f-a769-46b4-88b2-701372d4f17d" width="300" alt="Bottom View"></td>
    <td align="center"><strong>Back View</strong><br><img src="https://github.com/user-attachments/assets/1801f573-e855-4326-bf82-026ae7fcefd7" width="300" alt="Back View"></td>
    <td align="center"><strong>Right View</strong><br><img src="https://github.com/user-attachments/assets/d4d43af9-68ea-4f3c-ac10-84a0d1e47acc" width="300" alt="Right View"></td>
  </tr>
</table>

# Performance Video 

<table>
  <tr>
    <td align="center" width="50%">
      <strong>Open Challenge</strong><br><br>
      <img src="https://github.com/user-attachments/assets/ab32c76a-84c3-4365-bd72-2c4ba67838fe" width="100%" alt="Open Challenge"><br><br>
      <a href="https://youtu.be/6Eh0cw0jpJg"><strong>▶ Watch Open Challenge Video</strong></a>
    </td>
    <td align="center" width="50%">
      <strong>Obstacle Challenge</strong><br><br>
      <img src="https://github.com/user-attachments/assets/da579b6e-b8f2-4b8c-90f3-ecbf68387cb3" width="100%" alt="Obstacle Challenge"><br><br>
      <a href="https://youtu.be/F9Ot-lOl4QI"><strong>▶ Watch Obstacle Challenge Video</strong></a>
    </td>
  </tr>
</table>

If you are interested, explore the previous robot generations (Generation 1–3) in the [**V-Photos Folder**](https://github.com/itzcarmennn/X-UniTech/tree/59bc95add0fecbfca5860f1d18f3c837b4af057b/v-photos).

# 1.0 Mobility and Mechanical Design

## 1.1 Mechanical Structure
<p align="center">
  <img width="500" alt="Robot Photo (Fourth Generation)" src="https://github.com/user-attachments/assets/0619c5e1-ac45-4093-ad3f-fbb5645d838b" />
</p>

**Robot Dimensions:** Our robot dimensions (**250 mm × 120 mm × 295 mm**) were selected to maximize camera height while maintaining a compact and mechanically stable structure that accommodates all components. 

**Robot Building Process:** Follow our step-by-step building tutorial to learn how to assemble the robot in the [Video Building Process](https://youtu.be/vY-6_uyMKQI?si=AjLbu2vJUjDL66he).

**Robot Chassis:** We initially used a LEGO-built chassis in Generation 1-3 but later switched to a custom 3D-printed chassis to reduce the complexity of multiple LEGO connections and create a more compact, stable structure.

<table>
  <tr>
    <td align="center" width="50%">
      <strong>Previous LEGO Chassis</strong>
    </td>
    <td align="center" width="50%">
      <strong>Recent 3D-Printed Chassis</strong>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/6c608480-51ff-4b2e-80e1-4a7e177dfb68" width="60%" alt="Previous LEGO Chassis">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ae273db1-53fb-48eb-aed3-17a28b2fc5cb" width="60%" alt="Recent 3D-Printed Chassis">
    </td>
  </tr>
</table>

[Click for Robot Chassis CAD and Camera Mounting in STL File](https://github.com/itzcarmennn/X-UniTech/tree/59bc95add0fecbfca5860f1d18f3c837b4af057b/models/Materials%20of%20Computer-Aided%20Design%20(CAD)%20%5BFourth%20Generation%5D)

**Motor:** We selected the **EV3 Medium Motor (45503)** for its higher rotational speed and compact size. During the Open Challenge, the drive motor operates at 100% speed. During the Obstacle Challenge, the drive motor operates at 65% speed, while the steering motor operates at 70% speed to maintain stability and ensure reliable obstacle navigation. [**Purchase Link**](https://www.brickowl.com/catalog/lego-mindstorms-ev3-medium-motor-99455)

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/82b349ba-2aad-4604-beaf-e26a20844b3a" />
</p>

## 1.2 Drive System

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <img src="https://github.com/user-attachments/assets/a266057b-339a-405c-a32f-a4c0d4256708" width="230" alt="Gearbox Configuration">
    </td>
    <td width="70%" align="justify" valign="middle">
      We selected the <strong>EV3 Medium Servo Motor (45503)</strong> with a 20T driving gear and 28T differential-driven gear, achieving a 1.4:1 gear reduction ratio. The wheel assembly uses <strong>LEGO Parts 32019</strong> and <strong>86652</strong> to complete the drive mechanism. This configuration reduces the output speed while increasing the available torque to support robot movement.
      <br><br>
      Here's how we calculate it:
    </td>
  </tr>
</table>

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/fedc6b7e-e0eb-4895-a6a8-b00e534cf694" />
</p>

This combination also provides an ideal force and thrust-to-weight ratio. Here’s how we calculate it. 

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/f4451a4c-e4a4-45ca-9ce4-af841e39921a" />
</p>

[Click for detailed information on Drive System Choice](https://drive.google.com/file/d/1EcJO7IQbdKK3gPobmQDVCEyetCO6iOfM/view?usp=sharing)

## 1.3 Steering System

<p align="center">
<img width="1000" alt="Steering Structure" src="https://github.com/user-attachments/assets/7d06e6bf-942e-4d2b-97ca-d499c019bd9b" />
</p>

Our steering system combines a **LEGO Pin Crank (33299)**, which serves as the transmission component, with custom-designed 3D-printed parts. LEGO axles and connectors are used to connect the components and complete the steering mechanism.

[Here’s more about Steering Component CADs in STL File](https://github.com/itzcarmennn/X-UniTech/tree/59bc95add0fecbfca5860f1d18f3c837b4af057b/models/Materials%20of%20Computer-Aided%20Design%20(CAD)%20%5BFourth%20Generation%5D/Steering%20Parts)

<p align="center">
<img width="320" alt="image" src="https://github.com/user-attachments/assets/f4bc829e-ff4a-40f0-8559-754e452a900b" />
</p>

**Ackermann Steering:** We chose Ackermann steering because it allows the inner wheel to turn more than the outer wheel, resulting in smoother turns. The following calculation shows the outer wheel angle when the inner wheel angle is 35° during a left turn.

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/ebd5f25d-d3a0-40bd-96c0-6a1cd12fa678" />
</p>

**Iterations & Trade-off:** In Generation 2, we tested a **gear-reduced steering system** but found it responded more slowly than direct steering. Therefore, we decided to retain the **direct steering** mechanism for more responsive turning. 

<p align="center">
<img width="700" alt="Iterations   Trade-off" src="https://github.com/user-attachments/assets/da26252a-6840-4fd1-a85b-9c0cbe13f55c" />
</p>

**Steering System Trade-off**
<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/4bf82cf7-e127-49c0-9031-31660304c491" />
</p>

• The Ackermann steering system was selected because it provides better turning performance, reduces tyre scrubbing and improves manoeuvrability. 
<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/a6f32511-a8e0-4b0d-8dc7-a14b56995de7" />
</p>

[Click for detailed information on Steering System Choice](https://drive.google.com/file/d/1WwsIxELfLkICFE4XAowNIsLzPJPw8FXX/view?usp=sharing)

# 2.0 Power and Sensor Architecture

**Power System Layout:** A 9V battery supply powers the **EV3 Intelligent Brick** as the **“brain”** of our robot, which manages two motors and four sensor connections, including two Ultrasonic Sensors through the MUX.
<p align="center">
<img width="700" alt="Power System Layout" src="https://github.com/user-attachments/assets/a1277063-d993-4621-9d46-27f82ffb46d2" />
</p>

## 2.1 Power Budget

The maximum current value is used, while both EV3 Medium Motors are calculated using their stalled current of 800 mA each. 
<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/cb02ad6f-55db-4bc4-bbb2-3058b3b982ab" />
</p>

The total power consumption is: 0.015 + 0.075 + 0.200 + 0.175 + 14.400 + 0.700 = <strong><ins>15.565 W</ins></strong>.  
Here’s how to calculate the Battery Runtime Calculation for Max Load (15.565W):


<div align="center">

<table>
  <tr>
    <td width="50%" align="center" valign="middle">
      <table>
        <tr style="background-color: #DCEAF7;">
          <th align="center">Battery Parameter</th>
          <th align="center">Value</th>
        </tr>
        <tr>
          <td align="center"><strong>Nominal Voltage</strong></td>
          <td align="center">9V</td>
        </tr>
        <tr>
          <td align="center"><strong>Battery Capacity</strong></td>
          <td align="center">2333mAh</td>
        </tr>
        <tr>
          <td align="center"><strong>Total Energy</strong></td>
          <td align="center">21Wh</td>
        </tr>
      </table>
    </td>
    <td width="50%" align="center" valign="middle">
      <img src="https://github.com/user-attachments/assets/86003477-24a4-4682-b976-39317c52d829" width="398" alt="Battery Runtime Calculation">
    </td>
  </tr>
</table>

</div>

