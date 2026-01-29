# DX-Training
Uniform Cost Search and A* to optimize training for employees
Digital Transformation Training Optimization

Overview:
I wanted to use UCS and A* search for comparison of the best path to optimize a training program at work. I need to know where to invest in training (company location and job function) to make the biggest impact/increase in DXR score in 12 weeks.

Business Problem: My company (Calgon Carbon) is embracing a Digital Transformation set forth by our parent company, Kuraray, and I am tasked with increasing DX readiness across the company with training (increase score from 2 to 5 (max of 10) in 12 weeks total with training).

Goal: This project uses AI Search (Uniform Cost Search and A*) to optimize training across 3 locations to increase DX capability in 12 weeks for employees, using training time (weeks) as the cost metric (using simulated training metrics) to determine where to allocate training resources to make the biggest impact (by increasing overall DXR Score).

This program uses simulation data for training of 3 groups of employees: Operations, Project Managers, and Quality. This includes employees at 3 locations: Headquarters (HQ) and two plants, Big Sandy in KY (BSP) and Pearl River in MS (PRP)

The workforce currently has entry level DX capability across the company (all employees and locations DXR Score 2 out of 10) with limited automation lteracy and inconsistent data skills. Training must be improved across three key roles (Operations, Project Management, Quality) at each location HQ, BSP, PRP within 12 weeks. Each training has a different impact score and time involvement based on location and job function.

Output: Top 5 training roadmap strategies by efficiency (UCS and A*) Value = best path to transform workforce DX skills in 12 weeks. DXR Score (Digital Transformation Readiness Score) improves by minimum 3 pts from 2 to 5 (on scale of 1-10, 10 being the highest). Creates .CSV files for UCS and A* as “DXR Roadmaps” and compares outputs in a Gantt chart. 
