# Shaft-Design-Calculation-Automation
# ShaftSFD_BMD
The project focuses on generating shear force and bending moment diagrams for shafts using Python.

<h1>Description:</h1>

The ShaftSFD_BMD project is a Python-based engineering analysis tool developed to assist in the structural analysis and preliminary design of shafts. The project accepts user-defined shaft geometry, support conditions, and applied loads, and computes the resulting support reactions, shear force distribution, and bending moment distribution along the shaft length.

The implementation is provided in a Jupyter Notebook format to allow clear presentation of engineering theory, computational logic, and graphical output in a single interactive environment. The project is suitable for academic use, self-study, and early-stage mechanical design analysis.

<h2>Key Features:</h2>

- Accepts user-defined shaft length, supports, and applied loads
- Computes reaction forces using static equilibrium principles
- Generates shear force diagrams (SFD)
- Generates bending moment diagrams (BMD)
- Visualizes results using Matplotlib
- Modular and well-documented Python functions for easy extension

<h2>Future Improvements:</h2>

- <b>Stress Analysis:</b>  
  - Compute bending stresses using the flexure formula \( \sigma = \frac{My}{I} \)
- <b>Combined Loading:</b>  
  - Incorporate torsional loading and combined stress analysis
- <b>Deflection Analysis:</b>  
  - Calculate shaft deflection and slope along the shaft length
- <b>Design Automation:</b>  
  - Automatic shaft diameter sizing based on strength and stiffness criteria
- <b>Interface Enhancements:</b>  
  - Development of a GUI or web-based interface for easier interaction

<h2>Challenges:</h2>

- Translating engineering theory into accurate computational logic
- Handling multiple load types and boundary conditions
- Ensuring numerical stability and clear visualization for different shaft configurations
- Maintaining clarity and usability within a Jupyter Notebook environment

<h2>Walk Through</h2>
<p align="center">

- Using a question from; https://efficientengineer.com/shear-force-and-bending-moment-diagrams/
 <img src="https://imgur.com/G3fQn6l.png" height ="60%" width="70%"/>
- Defining shaft geometry, supports, and applied loads in the notebook<br />
 <img src="https://imgur.com/HrtSfjY.png" height="60%" width="70%"/>
 <img src="https://imgur.com/UHYGn9U.png" height="60%" width="70%" alt="Input Definition"/>
<br />
<br />

- Automatic computation of reactions, shear force, and bending moment distributions<br/>
<img src="https://imgur.com/nUKNbH5.png" height="60%" width="70%" alt="Computation of Reactions"/>
<br />
<br />

- Generated shear force and bending moment diagrams<br />
<img src="https://imgur.com/K0KLWYu.png" height="60%" width="70%" alt="Shear Force Diagram"/>
<img src="https://imgur.com/kEvPcZP.png" height="60%" width="70%" alt="Bending Moment Diagrams"/>
<br />
- Compare diagrams above to this from the page;
<img src="https://imgur.com/17D0UaH.png" height ="60%" width="70%" alt="Solution From Web"/>
<br />

<b>
This project is intended for educational and preliminary design purposes.
Users are encouraged to verify results independently before applying them
to real-world engineering designs.
</b>
