# Antennas

This repository explores various types of antennas used in real-time applications and their respective uses. It includes simulations and analyses conducted using CST software. Detailed documentation and examples cover antenna design, performance metrics, and practical implementations.

## Antenna parameters

1. Radiation pattern - Graphical representation of a radiating antenna
![image](https://github.com/ani171/Antennas/assets/97838595/7f947d00-8271-455c-9e3f-7999f67a8fe5)
  * Directive antenna -  These antennas focus the radiated power in a specific direction, providing high gain and directivity.
  * Omni-directional antenna - These antennas radiate power uniformly in all directions within a plane, typically the horizontal plane.
  * Isotropic antennas -  An idealized theoretical antenna that radiates power equally in all directions in a spherical pattern.

2. Beam solid angle - The beam solid angle (Ω) of an antenna is a crucial parameter that quantifies how the radiated power is distributed in space. It reflects the angular spread of the antenna's radiation pattern and is used to determine the directivity and gain of the antenna.

3. Directivity - Directivity is a key performance metric of an antenna that quantifies how concentrated the radiated power is in a particular direction compared to an isotropic radiator (which radiates uniformly in all directions)
![image](https://github.com/ani171/Antennas/assets/97838595/71320e75-a45c-4273-a3b1-76aaa18ee5c9)
![image](https://github.com/ani171/Antennas/assets/97838595/576b4c7a-d5e2-4ccd-af64-20804e3f7640)

 4. Radiation intensity - The radiation intensity of an antenna is a measure of how much power it radiates in a particular direction. It's not the same as the total power output of the antenna. The radiation intensity of an antenna is usually measured in watts per steradian (W/sr). A steradian is a unit that describes a solid angle, like a square degree measures a flat angle.  There are  4π steradians in a sphere, so if we take the total power radiated by the antenna and divide it by 4π, we get the average radiation intensity.
 5. Aperture of antenna - The aperture (A) of an antenna is a surface, near or on the antenna, chosen such that it's convenient to make assumptions about the electromagnetic field values there. This allows us to calculate the fields at other points, particularly in the far-field region <br>
  a. Physical aperture - This refers to the actual size or dimension of the antenna structure that interacts with the electromagnetic waves. It can be influenced by various factors depending on the antenna type. <br>
  b. Logical aperture - This refers to a theoretical surface associated with the antenna. It's chosen based on convenience for calculating the antenna's radiating properties, like radiation pattern and gain. The aperture itself isn't a physical part of the antenna.<br>
6. Radiation resistance - Radiation resistance describes a part of the antenna's electrical resistance caused by its emission of radio waves. It depends on the antenna's geometry, size, and materials. Ideally, we want to maximize radiation resistance (Rr) and minimize loss resistance (Rl) for efficient antenna operation.
