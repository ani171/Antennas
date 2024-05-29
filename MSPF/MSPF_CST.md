`https://youtu.be/ZZ5kaidwm5M?si=Dw1-5YAjhdRrN52L`

1. Select microwaves and RF opticals and antennas sub-options in that
![image](https://github.com/ani171/Antennas/assets/97838595/33e1faec-2d6a-44b6-b73d-9abe946d85c4)
2. As MSPF is a patch antenna, select the planar option
![image](https://github.com/ani171/Antennas/assets/97838595/8aadee5d-48ec-4616-8560-6343076ee305)
3. For operating frequency of 1 to 3GHz
![image](https://github.com/ani171/Antennas/assets/97838595/c7f23f5a-6e9c-4712-b735-c9f6539e3c65)
4. Now you will have this on your screen
![image](https://github.com/ani171/Antennas/assets/97838595/caa8374e-92b8-43bf-ad9b-32a275744970)
5. `https://www.everythingrf.com/rf-calculators/microstrip-patch-antenna-calculator` Using this website for a given specific dielectric constant and frequency the length and width of the patch antenna can be found <br>
![image](https://github.com/ani171/Antennas/assets/97838595/8c111aad-cb28-4ce3-93d0-0c686c4a1132)
6. Define the parameters in CST
![image](https://github.com/ani171/Antennas/assets/97838595/e332ed6c-a1dc-4959-bd32-0e4ad7ff8617)
7. To create the ground plane (Copper annealed material)
![image](https://github.com/ani171/Antennas/assets/97838595/d59b5fed-7056-4242-901c-98606937a98d) <br>
![image](https://github.com/ani171/Antennas/assets/97838595/3da79f9d-0459-469d-9414-6a7c049688db) <br>
8. To create substrate (FR-4 lossy material)
![image](https://github.com/ani171/Antennas/assets/97838595/ce33dac1-63ba-46b5-8540-499656f0618a)
9. Creating patch
![image](https://github.com/ani171/Antennas/assets/97838595/bf19d860-1bb2-4a4e-b1d8-b08da45ab321) <br>
<br>
<br>
10. Creating the feed-line for excitation
![image](https://github.com/ani171/Antennas/assets/97838595/af29a8b1-40e2-48ed-8dd5-2b7b79310574) <br>
![image](https://github.com/ani171/Antennas/assets/97838595/f7187856-26f4-4273-aa0f-b4d931a8c6b1) <br>
11. Now join the patch and the feed line using the boolean option
![image](https://github.com/ani171/Antennas/assets/97838595/30a96c23-a897-44b6-900f-d19746f5ca44)
12. To pick a face for excitation (face is the red section area)
![image](https://github.com/ani171/Antennas/assets/97838595/c98a6e99-a120-4bdd-8f1d-bc9b674040aa)
13. Now in home, select the macros option and solver to create a port
![image](https://github.com/ani171/Antennas/assets/97838595/366b80d9-79cd-4e9b-92cc-e43101b5c842) <br>
![image](https://github.com/ani171/Antennas/assets/97838595/40ef0e61-0b08-44c9-8c0a-311f75add468) <br>
14. Now start the simulation, once the simulation is done s11 parameter of the antenna can be observed
![image](https://github.com/ani171/Antennas/assets/97838595/2b731089-dc85-448b-bf88-0a977b34eba7)
### S11 parameter
* The S11 parameter in antennas, also known as the reflection coefficient or return loss, specifies how well an antenna matches the impedance of the transmission line feeding it
* All signals that are received by the antenna are passed, and to detect the passed signal out of the noise caused by all the other signals. So ideally we want an antenna that has a low S11 (below -10dB) at the operating frequency, but a high (close to 0dB) at any other frequency.
![image](https://github.com/ani171/Antennas/assets/97838595/676334df-fc8b-4086-8dd9-1ded0bcf11d7) <br>
Here we can observe that it is not very ideal <br>
15. So on changing the parameters to avoid noise at operating frequency
![image](https://github.com/ani171/Antennas/assets/97838595/a94838db-ae80-46d1-9b04-e11b5d197178)
16. On re-running the simulation
![image](https://github.com/ani171/Antennas/assets/97838595/c13e079e-c4b2-467a-a376-c8740c2e3067)
The new s11 graph can be observed via the green line
17. Similarly E-field and H-field patterns can be observed in the 2D/3D results
