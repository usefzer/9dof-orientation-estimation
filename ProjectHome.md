The aim of this project is to achieve efficient orientation estimation algorithms using a 9 DOF IMU.

We used the iNEMO V2 as IMU; It is the inertial module unit released by ST Microelectronics (official site http://www.st.com/internet/evalboard/product/250367.jsp ).
This project is done in cooperation with ST Microelectronics: R&D group, AST Advanced System Technologies / Remote Monitoring (andrea.vitali@st.com).


We're two software engineering students of "Università degli studi di Bergamo" ( http://www.unibg.it/ ).
The project has started as an academic experience related to "Progetto di Microelettronica" course, and over time it has became an hobby.

We developed the following algorithms:

- Complementary filter: the simplest way to estimate orientation using a 9DOF IMU. Attached in the "Download" section Matlab and C# sources.

- Kalman filter: implementation of Kalman filter using quaternion as system state. Attached in the "Download" section  Matlab and C# sources.

- AHRS estimation algorithm: this implementation is provided by the project imumargalgorithm30042010sohm ( http://code.google.com/p/imumargalgorithm30042010sohm/ ). We inserted the source as a class into our C# project, fitting it to our IMU (downloadable in the "Download" section).

There's also a report of our work attached as pdf file (Italian language).

Demonstration videos:
http://www.youtube.com/watch?v=p8H2-vkUM0I

2011/05/16: UPLOADED latest improvements achieved during last month.
Old versions of Kalman filter, Complementary filter and C# application has been marked with the "OLD" label.

2011/12/29: We are sorry for the long time during which this site has not been maintained: in the latest months we have been busy a lot (inter alia, we got the master's degree in computer engineering). Nevertheless we have continued to work on this project in the spare time; here is below a link to a demonstration video showing our rough first prototype of a motion tracking system.
As you can see, there are ONLY two BIG and WIRE CONNECTED marg sensors without the CASE. Besides, some TAPE has been used to keep them fixed on the arm, hence the system is not very precise. The software application is a NOT optimized alpha version and uses a very old version of a quaternion based Complementary Filter.

http://www.youtube.com/watch?v=mn8vfYt1U1I&context=C3e2c6f5ADOEgsToPDskKHH6ybFsuhwhsC-CkazIrX

2012/08/28: Here we are with some news. We have developed a new wireless MARG sensor in collaboration with ST-Microelectronics. In the following link you can see a brief description of our work with a video showing the first (and bulky) prototype.

http://www.youtube.com/watch?v=RRKzzHHReRA

Next steps: soon (hopefully) we'll add the embedded version of the quaternion Kalman filter. Then we'll try to use the new MARG sensors in order to move an avatar.

2012/11/24: Hello everybody! We have some news. We used five wireless MARG sensor (the one described in our last update) in order to animate an arm, a leg and the torso. Further more we put the quaternion Kalman filter on the embedded side, so every single sensor now send his orientation at 100 Hz. At the following link you can see our last demo.

http://www.youtube.com/watch?v=UT7Rg108syk&feature=plcp

Next steps: we want to extend the algorithms in order to track the displacement in the 3 dimensions, not only the orientation. For the next update we also hope to use a new, smaller, MARG sensor that we have developed, with new sensors and  more computing power.

2013/07/23: Hello all, it's been a long time since our last update...we've started to work on new systems for orientation estimation and motion tracking applications with the Microelectronics Laboratory of University of Bergamo:

http://www.unibg.it/struttura/en_struttura.asp?cerca=en_ing_microlab_intro

Together, we have developed "neMEMSi", an advanced wireless and ultra low power platform with an embedded orientation estimation algorithm:

https://www.youtube.com/watch?v=hQidXh_ohIU

If you want to collaborate with us or you are interested in using our systems, don't hesitate to contact us.

See ya!