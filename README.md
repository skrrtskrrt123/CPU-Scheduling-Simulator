# CPU-Scheduling-Simulator (for Google Colab)
This simulator is designed to help users visualize and understand how various CPU scheduling algorithms work. It provides an interactive web-based interface built into Google Colab, allowing users to input process data and view scheduling results in real time using Gantt charts and performance metrics.

# author
Nur Aleesya Najwa Binti Nor Azli

# how to run this project
Ensure you have Python 3.x and Jupyter installed

Option 1:
1. Open the code in Google Colab.
2. Run the cell to initialize the Python backend and load the HTML interface.

Option 2: Run Locally in VS Code with Jupyter
1. Open the notebook using VSC with the Jupyter extension installed.
2. Make sure Python 3.x is installed.
3. Install required packages:
pip install ipython ipywidgets
4. Run the cell in the notebook.

# user instructions
1. Input the number of processes (make sure to press the 'Generate Process Fields' button) and their respective Arrival Time, Burst Time, and Priority values.
2. Select one of the available scheduling algorithms:
   - Round Robin (RR)
   - Shortest Job Next (SJN)
   - Priority (Non-preemptive)
   - Shortest Remaining Time (SRT)
3. If using RR, specify a quantum value.
4. Click “Run Simulation” to generate the Gantt chart and process statistics.
