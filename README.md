Advanced Disk Scheduling Simulator is an interactive Python application designed to simulate and analyze various disk scheduling algorithms used in operating systems. The simulator allows users to input custom disk access sequences and visualize how algorithms like FCFS, SSTF, SCAN, C-SCAN, LOOK, and C-LOOK handle these requests

With a modern GUI built using Tkinter, users can easily set parameters such as initial head position and maximum track number, and view real-time disk head movement using Matplotlib plots. The simulator also computes key performance metrics like total seek time, average seek time, and system throughput, and logs each run into a CSV file for further analysis.

This project serves as an educational tool for students, instructors, and enthusiasts aiming to understand the behavior and efficiency of different disk scheduling strategies in a hands-on, visual format.
Features
📌 Interactive GUI using Tkinter

🔍 Supports six key scheduling algorithms:

FCFS (First-Come-First-Served)

SSTF (Shortest Seek Time First)

SCAN

C-SCAN

LOOK

C-LOOK

📈 Real-time visualization of disk head movement

📊 Displays performance metrics:

Total Seek Time

Average Seek Time

Throughput (requests/sec)

📁 Logs simulation results to a CSV file

🔁 Compare multiple algorithms in a single run

🚀 Getting Started
Prerequisites
Make sure you have Python 3.x installed. Install the required libraries:

bash
Copy
Edit
pip install matplotlib numpy
Run the Application
bash
Copy
Edit
python main.py
Replace main.py with the filename of your simulator (e.g., disk_simulator_gui.py).
