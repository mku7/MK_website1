# Aerodyanmics Quals Study


# Aerodynamics



* [**Dr. Sankar Aero Website**](https://sankar.gatech.edu/?q=node/12#overlay-context=)

* [**Dr. Sankar Youtube**](https://www.youtube.com/@lakshmisankar6498/videos)

---

## Dr. Sankar Youtube Videos

### Navier-Stokes Equations

[Navier-Stokes Equations pdf](https://www.sankar.gatech.edu/sites/default/files/2D_Navier_Stokes_Equations_Derivations.pdf)

* [Video - 2D Navier-Stokes Equations](https://www.youtube.com/watch?v=aKiBNr9-tCI&t=1929s) (July 16, 2024 Watched)

Keep pressure and viscous forces, neglecting body forces (gravity, electric, magnetic)

[Exact Solutions to Navier-Stokes Equations pdf](https://www.sankar.gatech.edu/sites/default/files/Navier_Stokes_Exact_Solutions.pdf)

* [Video - Exact Solutions to Navier-Stokes Equations](https://www.youtube.com/watch?v=jsBmt4t2Zxo) (July 15, 2024 Watched)


### Full and Linearized Potential Equations


### Transonic

* [Video - Transonic Flow](https://www.youtube.com/watch?v=uTkk97AETco)
   
* [Video - Transonic Flow Part II](https://www.youtube.com/watch?v=--SkqTrIWTE&t=328s)

* [Video - Subsonic Flow Over Finite Wings v2](https://www.youtube.com/watch?v=sU7f-0HKQ5k)


---

### Concepts and Assumptions of Aerodynamics


* [Video - Streamlines, Pathlines, Vorticity](https://www.youtube.com/watch?v=a83fo_dwx1M&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=2&pp=iAQB) (July 22, 2024 Watched)

#### Streamline (Instantaneous Snapshot of Particles)

Velocity is in the same direction as the path, so cross product is equal to zero

$$\vec{V} \times d\vec{s} = 0$$

$$\frac{u}{dx} = \frac{v}{dy} = \frac{w}{dz}$$

Nothing cannot cross normal to the streamline

### Pathline/Streakline (Time-Elapsed Image)


$$\dot{x} = \frac{dx}{dt} = u(x,y,z,t)$$

$$\dot{y} = \frac{dy}{dt} = v(x,y,z,t)$$

$$\dot{z} = \frac{dz}{dt} = w(x,y,z,t)$$


### Angular Velocity


Angular velocity = 1/2 curl of velocity

$$ \vec{\Omega} = \frac{1}{2} \vec{\nabla} \times \vec{V}$$

$$\vec{\Omega} = \left[ \left(\frac{\partial v}{\partial x}-\frac{\partial u}{\partial y}\right)\vec{k} + \left(\frac{\partial w}{\partial y}-\frac{\partial v}{\partial z}\right)\vec{i} + \left(\frac{\partial u}{\partial z}-\frac{\partial w}{\partial x}\right)\vec{j} \right] $$

Vorticity = twice angular velocity = curl of velocity

$$\vec{\zeta} = 2\vec{\Omega} = \vec{\nabla} \times \vec{V}$$


### Conservation of Mass (Incompressible)

Divergence of Velocity

$$\vec{\nabla} \cdot \vec{V} = 0$$

### Irrotationality

Curl of Velocity = Vorticity

$$\vec{\nabla} \times \vec{V} = 0$$


* [Video - Flow Properties, Governing Equations for a Streamtube](https://www.youtube.com/watch?v=zJC-wbuqbNo&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=1&pp=iAQB) (July 24, 2024 Watched)

### Knudsen Number

$$Kn=\frac{\lambda}{L}$$

$\lambda$: mean free path

Low altitutde, small Knudsen Number can consider air as a continuum (using avg properties)

### Equation of State

$$P=\rho R T$$

ideal gases, thermally and calorically perfect gases

### Important Properties of Fluid

5 DOF: 3 translation and 2 rotation (diatomic molecules)

$$\rho, P, T, u, v, w$$

Temperature is a measure of random motion of the particles

### Euler Equation

Steady, Inviscid, No Body Forces

$$\rho V dV + dP = 0$$


### Bernoulli's Equation (Euler Equation + Incompressible)

Steady, Inviscid, Incompressible, No Body Forces

$$P_s + \frac{1}{2} \rho V^2 = Constant = P_0$$

$P_0$ stagnation pressure

---

### Classical Approaches from Incompressible to Supersonic

### Building Blocks

[Building Blocks pdf](http://www.sankar.gatech.edu/sites/default/files/Building_Blocks.pdf)

* [Video - Building Blocks Part 1](https://www.youtube.com/watch?v=O86ln81vxrE) (July 24, 2024 Watched)

### Potential Flow

Irrotational, Inviscid, Incompressible, Steady, No Body Forces

### Velocity Potential $\phi$

$$\vec{V}=\nabla \phi$$

$$\nabla^2\phi = 0$$

curl of gradient is equal to zero

$$\vec{\nabla}\times\vec{\nabla}\phi = 0$$

### Stream Function $\psi$

$$u=\frac{\partial \psi}{\partial y}$$

$$v=-\frac{\partial \psi}{\partial x}$$


* [Video - Building Blocks Part 2](https://www.youtube.com/watch?v=4KFER6Xb5Is) (July 25, 2024 Watched)

### Stokes' Theorem

$$\Gamma = \oint\limits_{C}\vec{V}\cdot d\vec{s} = \iint\vec{\xi}\cdot d\vec{A}$$

### Source/Sink

$$\phi_{source} = \frac{Q}{2\pi r} \ln(r)$$

### Uniform Flow

$$\phi_{uniform flow} = ux + vy$$

* [Video - Building Blocks Part 3](https://www.youtube.com/watch?v=zTnABQyOBzk)

* [Video - Thwaites' Method](https://www.youtube.com/watch?v=FafpT5DwJP0)


### Thin Airfoil Theory

* [Video - Thin Airfoil Theory Part 1](https://www.youtube.com/watch?v=oXfeIMBVEyg) (July 25, 2024 Watched)

* [Video - Thin Airfoil Theory Part 2](https://www.youtube.com/watch?v=p7ZIjZcEiKE) (July 26, 2024 Watched)

- Neglect thickness (symmetric about camber line)
- Small camber (2-4% chord)
- Small angle of attack (negligible disturbance in freestream direction)
- Flow tangency (rotated body slope = new flow velocity slope)
- Airfoil represented by a camber line then rotated to the wind tunnel coordinate system and projected to the wind tunnel x-axis (parallel to freestream velocity)

$$\frac{dz}{dx} = \frac{w}{u}$$

$$d\Gamma = \gamma(\xi) d\xi$$

* [Video - Thin Airfoil Theory Part 3](https://www.youtube.com/watch?v=ZarvNcfQHc4)

* [Video - Thin Airfoil Theory Part 4](https://www.youtube.com/watch?v=0YXUT3NOtks)

* [Video - Thin Airfoil Theory Examples](https://www.youtube.com/watch?v=Mobsg5yn8iU)



### Prandtl's Lifting Line Theory

#### Downwash, Lift, Induced Drag

 [Lifting Line Theory pdf](https://www.sankar.gatech.edu/sites/default/files/Lifting_Line_Theory.pdf)

* [Video - Lifting Line Theory 1](https://www.youtube.com/watch?v=-XFf1P0RpeA&t=3s) (July 16, 2024 Watched)

* [Video - Lifting Line Theory 2](https://www.youtube.com/watch?v=nDbpUFR7jec) (July 16, 2024 Watched)

* [Video - Lifting Line Theory 3](https://www.youtube.com/watch?v=0zAnErFDlmk) (July 17, 2024 Watched)

* [Video - Lifting Line Theory 4](https://www.youtube.com/watch?v=Ryk7KHgdjxI) (July 17, 2024 Watched)

* [Video - Lifting Line Theory 5 (Matlab program prandtl.m)](https://www.youtube.com/watch?v=--1X3fK46A4) (July 18, 2024 Watched)






### Turbulent Flow

15. [Video - Turbulent Flow Video 1](https://www.youtube.com/watch?v=IA0A6KmNQKA&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=15&pp=iAQB)

16. [Video - Turbulent Flow Video 2](https://www.youtube.com/watch?v=C0sVJZoK4zM&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=16&pp=iAQB)

17. [Video - Turbulent Flow Video 3](https://www.youtube.com/watch?v=Nt0Ao53Rg4w&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=17&pp=iAQB)

### 
18. [Video - Flow Transition](https://www.youtube.com/watch?v=Ky9JHh-NrUk&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=14&pp=iAQB)

19. [Video - Worked Out Examples](https://www.youtube.com/watch?v=UOiwy0ZPOGw&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=13&pp=iAQB)

### Boundary Layer Theory


20. [Video - Boundary Layer Theory Video 1](https://www.youtube.com/watch?v=rk5DGgeOIbE&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=8&pp=iAQB)

21. [Video - Boundary Layer Theory Video 2](https://www.youtube.com/watch?v=njcSvmQ81jE&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=9&pp=iAQB)

$$\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y} = 0$$

$$u\frac{\partial u}{\partial x} + v \frac{\partial u}{\partial y} + \frac{1}{\rho} \frac{\partial P}{\partial x} = \nu \frac{\partial^2 u}{\partial y^2}$$

$$\frac{1}{\rho}\frac{\partial P}{\partial y} = 0$$

$$\frac{\delta}{L} = O\left(\frac{1}{\sqrt{Re}}\right)$$

$$\frac{v}{V} = O\left(\frac{\delta}{L}\right) = O\left(\frac{1}{\sqrt{Re}}\right)$$


22. [Video - Boundary Layer Theory Video 3](https://www.youtube.com/watch?v=G7zJLgsaC0k&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=10&pp=iAQB)

23. [Video - Boundary Layer Theory Video 4](https://www.youtube.com/watch?v=mukuJQK3N34&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=11&pp=iAQB)

24. [Video - Boundary Layer Theory Video 5](https://www.youtube.com/watch?v=hnxltkh0gcI&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=12&pp=iAQB)

###
25. [Video - Aerodynamic Forces and Moments](https://www.youtube.com/watch?v=RopA2teL6_0&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=7&pp=iAQB)

26. [Video - NACA Airfoil Numbering Convention](https://www.youtube.com/watch?v=dGKupAkyN0M&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=6&pp=iAQB)

27. [Video - Airfoils](https://www.youtube.com/watch?v=bni1tH5MSv8&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=5&pp=iAQB)






###
32. [Video - Panel Methods](https://www.youtube.com/watch?v=pXpjyYC3yck&list=PL_EkjePoSGXgmXKjByxaPodoRaOLFPv2W&index=32&pp=iAQB)

33. [Video - Reynolds Analogy](https://www.youtube.com/watch?v=_zg7qn58EHU)

### Compressible Flow
34. [Video - Compressible Potential Flow Derivation Video 1](https://www.youtube.com/watch?v=XBH5Fnox-Ak&t=895s)
    
35. [Video - Compressible Governing Equations Video 2](https://www.youtube.com/watch?v=DUT0n8sUOIM)
    
36. [Video - Prandtl Glauert Rule](https://www.youtube.com/watch?v=v2c8efG-BMY)
    
37. [Video - Critical Mach Number](https://www.youtube.com/watch?v=pspjhWb2nqM)



### Supersonic and Hypersonic

41. [Video - 2D Supersonic Flow over Thin Airfoils](https://www.youtube.com/watch?v=qFcg3qoKbHk)

42. [Video - Supersonic Flow over Complete Aircraft](https://www.youtube.com/watch?v=HFgC_yTQx6M&t=1s)

43. [Video - Introduction to Hypersonic Flow](https://www.youtube.com/watch?v=8m5eyw9bQns)


---


## A8 Transonic Flow (June 15, 2024)


[Video - Transonic Flow I](https://www.youtube.com/watch?v=uTkk97AETco) (June 15, 2024 watched)
* [MK PPT - Transonic Flow](https://gtvault-my.sharepoint.com/:p:/g/personal/mku7_gatech_edu/EcTPWctxpX9LiJaMwVWixzkBhRGV4dNKmC1Kln5WvglWUQ?e=fbUe20)

[Video - Transonic Flow II](https://www.youtube.com/watch?v=--SkqTrIWTE)

[Video - 2D Supersonic Flow, Ackert's Rule](https://www.youtube.com/watch?v=qFcg3qoKbHk) (June 15, 2024 watched)

[Video - 3D Supersonic Flow](https://www.youtube.com/watch?v=HFgC_yTQx6M)

---

## MK Notes



[Navier-Stokes Equations](aero/navier_stokes_eqns.html)


[Euler Equations]

[Full Potential Equations]

[Linearized Potential Equations]



<img src="AeroQualTopics.png" alt="Viscous Qual Topics" style="width:50%; height:50%"/>



---

# Viscous Flow

<img src="ViscousQualTopics.png" alt="Aero Qual Topics" style="width:50%; height:50%"/>

---

# Camber Effect on Airfoil Characteristics

[Camber Effect](http://heli-air.net/2016/03/13/camber-and-drag/)
