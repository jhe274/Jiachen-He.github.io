---
use_math: true
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Physics, University of Kentucky, 2025
* M.S. in Physics, University of Kentucky, 2019
* B.E. in Measurement Control Technology and Instruments (equivalent to EE), Shenzhen University, 2017

---

Professional Experience
======
* **Graduate Research Assistant**  
  University of Kentucky, August 2019 - Present  

  - **Quantum Sensing**: Expert in polarization modulation ellipsometry, specializing in precise optical alignment, system calibration, and optimization. Developed a system for detecting minute magnetic field variations associated with spin-polarized helium-3 targets using nonlinear magneto-optic effects without magnetic shielding, estimating a shot noise limited sensitivity of $4.8\times10^{-11}\ \text{G}/\sqrt{\text{Hz}}$ under spin-exchange optical pumping operating temperautre ($\sim510\ \text{K}$).

  - **Laser Frequency Stabilization**: Extensive experience in spectroscopic laser locking using PDH and DSAS techniques with cavities and alkali metals (Rb, K), reducing laser frequency drift to $200\ \text{kHz}/\text{h}$ -- over $110$ times more stable than unlocked systems. Implemented sideband locking over $24\ \text{GHz}$ using a $6\ \text{GHz}$ bandwidth EOM for precise frequency control.

  - **Software Development**: Published two Python packages on [GitHub](https://github.com/jhe274/Faraday_DAQ) using object-orientated programming to interface with scientific instruments like wavelength meter and Gaussmeter, eliminating reliance on low-level SCPI commands while optimizing buffer management and communication protocols.

  - **Lab Automation**: Proficient in developing modular Python-based synchronous data acquisition systems for communication with scientific instruments such as wavelength meter, laser controller, lock-in amplifiers, and Gaussmeter. The system efficiently initializes, configures, and synchronizes instruments, sending TTL-level pulse trigger signals and recording data in their buffers with sub-millisecond time differences.
    
  - **Merritt Coil Development and Implementation**: Designed and simulated a compact Merritt coil system to replace Helmholtz coils, reducing the size by 6x while reducing the longitudianl field gradient by a factor of 4 and increasing the uniform field range by 33%. Utilized Python and Autodesk Inventor, collaborating closely with machine shop teams to ensure successful implementation.

  - **Compact Magnetic Field Design**: Independently developed a magnet box prototype using COMSOL and MATLAB Simulink, generating a $7\ \text{G}$ magnetic field with a $20\ \text{mG}/\text{cm}$ gradient over a $10\ \text{cm}$ range. The box, measuring approximately $18\ \text{cm}\times18\ \text{cm}\times33\ \text{cm}$, enhanced my expertise in FEA and involved leveraging concepts like magnetic scalar potential and image fields.

  - **Cryogenic and Vacuum Systems**: Contributed to system calibration and maintenance of a cryogenic system, gaining hands-on experience with vacuum technologies over five years.

  - **Ongoing Projects**: Machine learning algorithms for real-time magnetic field cancellation.
  
* **Graduate Teaching Assistant**  
  University of Kentucky, August 2017 - May 2019  
  - Instructed undergraduate students in Newtonian mechanics, electromagnetism, and physical optics through hands-on lab sessions and interactive recitations, fostering a deeper understanding of core physics concepts.
  - Assisted in preparing teaching materials, grading, and answering student inquiries during lab sessions.

* **Summer Research Assistant**  
  University of Kentucky, May 2018 - August 2018  
  - Conducted research on Etch Track-Directed Growth of Carbon Nanotubes on Graphite.
  - Utilized chemical vapor deposition techniques to create graphene/boron nitride samples.
  - Studied frictional properties on the surface of graphene using a microfluidic probe.
  
* **Grduation Project**
  Shenzhen University, September 2015 - May 2016
  - Research on the Control System of Intelligent Fish Tank Based on Single Chip Microcomputer

* **Open Laboratory Fund Project**
  Shenzhen University, September 2012 - October 2013
  - Research on the Design of Temperature-controlled Automatic Watering Device

---

Skills
======
* **Laser & Optical Systems**: Laser optics, fiber optics, solid-state lasers, polarization modulation ellipsometry, spin-exchange optical pumping (SEOP), polarimetry, interferometry
* **Instrumentation & Electronics**: Lock-in amplifiers, electro-optic modulators, RF signal generators,
spectrum analyzers, oscilloscopes, photodetectors
* **Cryogenic system**: Cryostat, Helium/Nitrogen Management, Temperature Sensors, Vacuum Technology, Thermal Management, Leak Detection, Instrumentation and Control
* **Software & Programming**: Python (scientific computing, hardware automation), C++, MATLAB, Zemax, COMSOL,
Autodesk Inventor, LabVIEW, Mathematica
* **Simulation & Modeling**: Magnetic field design (Merritt coils, finite element analysis), optical metrology, quantum light-matter
interaction
* **Platforms & Systems**: Unix/Linux, Windows, Python based synchronous data acquisition system

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

---

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

Honors & Awards
======
- **Graduate Student Congress (GSC) Conference Award**  
  *University of Kentucky*  
  *April 2024*  

- **Huffaker Travel Scholarship**  
  *Department of Physics & Astronomy, University of Kentucky*  
  *July 2022, April 2024, March 2025*  

- **Departmental Fellowship for Graduate Students with an Outstanding Curriculum**  
  *Department of Physics & Astronomy, University of Kentucky*  
  *August 2017 - May 2019*  

- **Max Steckler Fellowship, Graduate School Fellowship**  
  *Graduate School, University of Kentucky*  
  *August 2018*  

---

Leadership & Collaborations
======
- **Alumni Liaison**  
  *University of Kentucky*  
  *February 2025 - Present*  
  - Foster connections between alumni and current students, facilitating networking and engagement opportunities.

- **Graduate Student Congress (GSC) Representative**  
  *University of Kentucky*  
  *August 2023 - August 2024*  
  - Represented the Physics Department in GSC, advocating for graduate student interests and promoting interdisciplinary collaboration.

- **Undergraduate Mentorship**  
  *University of Kentucky*  
  *2021 - 2025*  
  - Supervised multiple undergraduate students, including a Research Experiences for Undergraduates (REU) participant from MIT, providing theoretical guidance on the resonant Faraday effect in a two-level system. The project culminated in a presentation at the 2024 Division of Nuclear Physics (DNP) Meeting.

- **High School Mentorship**  
  *University of Kentucky*  
  *September 2023 - May 2024*  
  - Guided a high school student in a scientific project exploring light polarization and measuring the speed of light using Herriott-style cavity mirrors and a custom-built rotating mirror.

- **Collaboration with Engineers**  
  *University of Kentucky*  
  *2019 - Present*  
  - Partnered with machine shop engineers with a strong track record of designing custom-made electronic devices and developing a Merritt coil winding system.

---

Professional Affiliations
======
* **American Physical Society (APS)**, 2021 - Present
* **Society of Photo-Optical Instrumentation Engineers (SPIE)**, 2024 - Present

---

Volunteering
======
* **Raleigh International Gorkha, Nepal**, July 2016 - August 2016
  - Created a simple webpage using online tools and successfully raised £2000 within two days to support a charity program aiding the earthquake-affected village of Chuwatar, Nepal.
  - Participated in community development projects, including water purification and sanitation improvements.
* **Intel Developer Forum 2015, Shenzhen, China**, August 15 - August 21 2015
  - Selected as one of the top 10 out of 500 volunteers and recognized as an "Exceptional Volunteer"

---

<p><a href="{{ base_path }}/files/CV_Jiachen_He.pdf" target="_blank">Download my CV</a></p>