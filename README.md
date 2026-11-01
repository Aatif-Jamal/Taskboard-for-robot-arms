# Taskboard-for-robot-arms
A unified all-in-one taskboard that shall be used in robotics competitions. It will serve as an easily reproducible, portable and cost-effective design to carry out robotic arms competitions.

# Day 0 - 01/11/26 - Birth
Today, the idea was born.
I was reading the research paper "Dr.J" or "Digital Robot Judge" and realized that the solution put forward was actually quite reproducible, and I wanted to add a twist of modularity to it. I believe this project will be an incredible intermediate to hard project for Fallen, and will really force me to engineer like a true engineer.

I worked a bunch on task selection, documentation, physical constraints and required components.
Ideally, the final version will have 5 tasks, and I tried real hard to ensure each task addressed/covered a different aspect of problem solving for industrial robotics. The shortlisting took a lot of time because I had too many tasks to begin with.
<img width="610" height="816" alt="image" src="https://github.com/user-attachments/assets/76068adc-967b-4865-92a9-7731c59ac2d5" />

1. **Button Start/Stop -** The taskboard has a single button. Presing it once starts the overall timer. Pressing it again marks/checks for completion.

2. **RJ45 insertion -** The taskboard shall have a female RJ-45 socket with a micro-button at the end. The robot will be tasked with picking up the connector, aligning it with the port and inserting it.

3. **Valve Rotation -** The taskboard will have a valve on it. A small oled display will flash how many degrees it's supposed to be rotated, and an AS5600 sensor mounted on the valve will ensure the completion of the task.

For the first prototype, I will only have the above three tasks. I need to prove whether this concept works well enough for expansion, and for task 3, I need to design a pretty complicated custom valve that allows the as5600 sensor to stay stationary while a small neudinium magnet spins around on one edge.

4. **Screw threading -** Pick up a screwdriver, Pick up a screw, align it accurately, correctly thread it in. A microswitch at the end of the hole picks up completion.

5. **Cable Routing -** This is a pretty complicated task. The idea is to have a series of gates with roller switches fitted into them. The robot arm must route a wire accurately through the gates (hence triggering the rolled switches) in a particular order. 

<img width="521" height="823" alt="image" src="https://github.com/user-attachments/assets/8c9d2aee-db39-4f24-b33d-b0640fd23c26" />
