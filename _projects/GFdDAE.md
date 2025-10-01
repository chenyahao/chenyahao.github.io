---
title: "ANR-25-CE48-4916: GFdDAE"
collection: projects
type: "ANR JCJC"
permalink: /projects/GFdDAE
venue: " "
date: 2025-10-01
location: "INRIA Rennes"
---

Differential-algebraic equations (DAEs) arise naturally when modeling dynamical systems from first principles. In many cases, physical laws are expressed as combinations of differential and algebraic equations. This modeling approach is common in constrained mechanics, chemical and biological processes, power systems, and especially analog circuit design—where idealized components (e.g., resistors, capacitors, inductors) and Kirchhoff’s laws define the system dynamics. When these systems experience abrupt changes—such as switching in electric circuits, mechanical contacts, or discontinuous control inputs—discontinuous DAEs emerge. However, there is currently no comprehensive theoretical foundation for studying such systems. Challenges include:

Their hybrid behaviors, which differ significantly from ODE counterparts,
The inconsistent initialization problem caused by switching and algebraic constraints,
The occurrence of Dirac impulses due to state jumps.
Without a rigorous solution concept, tasks such as simulation, stability analysis, and control design lack solid justification.

Discontinuous DAEs are relevant across many research areas, including systems and control, hybrid systems, and computer-aided simulation. A notable example is switched DAEs. While time-dependent switching has been extensively studied [2-5], progress on state-dependent switching, a subclass of discontinuous DAEs, remains limited.

The Hycomes team at Inria Rennes has contributed to related research through the concept of multi-mode DAEs, in the context of the Modelica language [6-7]. Despite these advancements, challenges persist, including:

Computing consistent initial values and jumps,
Managing sliding and chattering behaviors,
Addressing scalability for large-scale, high-dimensional systems.
These issues emphasize the need for refined mathematical foundations and advanced control methods compatible with Modelica-based simulation platforms.

 

[1] D. Liberzon. Switching in Systems and Control. Systems and Control: Found. and Appl. Boston: Birkhäuser, 2003.

[2] D. Liberzon and S. Trenn. “On stability of linear switched differential algebraic equations”. In: Proc. IEEE CDC 2009, pp. 2156–2161.

[3] D. Liberzon and S. Trenn. “Switched nonlinear differential algebraic equations: Solution theory, Lyapunov functions, and stability”. In: Automatica 48.5, pp. 954–963.

[4] Y. Chen and S. Trenn. “Impulse-free jump solution of nonlinear differential algebraic equation”. In: Nonlinear Analysis: Hybrid Systems 46 (2022), p. 101238.

[5] Y. Chen and S. Trenn. “On impulse-free solutions and stability of switched nonlinear differential–algebraic equations”. In: Automatica 156 (2023), p. 111208

[6] A. Benveniste, B. Caillaud, and M. Malandain. “The mathematical foundations of physical systems modeling languages”. In: Ann. Rev. in Control 50 (2020), pp. 72–118.

[7] A. Benveniste, B. Caillaud, M. Malandain, and J. Thibault. “Algorithms for the structural analysis of multimode modelica models”. In: Electronics 11.17 (2022), p. 2755.

[8] A.F. Filippov. Differential Equations with Discontinuous Right-hand Sides. English (Transl. from the Russian). Mathematics and Its Applications: Soviet Series, 18. Dordrecht etc.: Kluwer Academic Publishers, 1988.

[9] Y. Shtessel, C. Edwards, L. Fridman, A. Levant, et al. Sliding Mode Control and Observation. Vol. 10. Springer, 2014