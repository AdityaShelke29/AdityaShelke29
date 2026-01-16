# Hi, I'm Aditya! 👋
I'm a senior at the University of Maryland, College Park, studying computer science and mathematics with an additional minor in robotics and autonomous systems. 

In my free time, I love to play the guitar, draw, watch anime, or go to the gym. Favorite animes are Attack on Titan and Steins;Gate. Also a big Star Wars fan.

**What am I up to?**
- I am currently working on a P2P (peer to peer) live streaming application that uses WebRTC for medium sized group calls. Think Discord or Zoom calls, implemented with WebRTC without the need for a centralized server for stream data propagation. The interesting technical challenge with this project is scale. In naive implementations of a P2P video conferencing application, each peer must send its stream to all (n-1) other peers, and must download a stream from all (n-1) other peers. This is called a fully connected mesh or a fully connected network, and is highly inefficient at scale.
- Instead, this project will use a central signaling server to coordinate peers such that they only send their stream to a minimal (< n-1) number of peers, and download streams from a minimal (< n-1) number of peers. With this approach, peer A can send its stream to peer B, which will forward it to peer C, without peers A or C being connected. This is called a hybrid mesh. Additionally, by automatically scaling resolution depending on peer bandwidth and updating the hybrid mesh accordingly, it is possible to scale the system to a larger number of peers while still propagating streams between peers in a P2P fashion. 

**Past Experiences: **
- Bloomberg (Summer 2025): Designed and built a distributed system of controllers for infrastructure autoscaling with Golang, Postgres, Azure.
- Bank of America (Summer 2024): Built software to automate trade order management and modification with Python and NLU. Developed socket - based API orchestration software.
- Metron, Inc. (Summer 2023): Developed a multithreaded Bayesian sampling system in Java improving SONAR tracking efficiency by 50%. Implemented modern MCMC and adaptive rejection techniques, cutting sampling errors by 75%.
- New Jersey Institute of Technology: Co-authored a paper on a model nanoparticle anticancer drug delivery system. Utilized MATLAB and differential equations to simulate the motion of superparamagnetic nanoparticles in the bloodstream.
-   (https://journals.aps.org/pre/abstract/10.1103/PhysRevE.106.015104)
