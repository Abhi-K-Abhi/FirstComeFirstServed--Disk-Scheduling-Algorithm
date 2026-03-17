First Come First Served (FCFS) Disk Scheduling Simulator
A high-performance GUI-based simulation tool developed to visualize and analyze the First-Come, First-Served (FCFS) disk scheduling algorithm. This application provides an interactive platform for students and developers to understand disk arm movement, head positioning, and seek time calculations through real-time dynamic graphing.

🚀 Project Overview
In Operating Systems, Disk Scheduling is vital for managing I/O requests. FCFS is the simplest form of disk scheduling where requests are entertained in the order they arrive. This simulator takes raw cylinder requests and translates them into a visual "zigzag" path, calculating technical metrics like Total Seek Count and Average Seek Time.

Core Functionality
Real-Time Dynamic Plotting: Uses a QTimer to animate the disk head movement across cylinders.

Intelligent Data Processing: Supports comma-separated input strings with built-in validation.

Dynamic Range Selection: Users can define cylinder boundaries (Min/Max) to simulate different hardware constraints.

Automated Analytics: Generates a detailed report including step-by-step seek distance and final efficiency metrics.

🛠️ Technical Stack
Language: Python 3.x

GUI Framework: PyQt5 (utilizing QTabWidget, QSpinBox, and QSlider)

Visualization: PyQtGraph (high-performance 2D plotting)

Architectural Pattern: Object-Oriented Programming (OOP) with encapsulated logic within the Ui_MainWindow class.

📈 System Architecture
The application is structured into three primary functional areas:

Setting Tab: Where users input cylinder requests and use "Random Fill" for quick testing.

Control Tab: Allows the configuration of the Initial Head Position and Cylinder Range.

Visualization Engine: A high-performance graphing area that maps the head sequence to a time-series plot.


📥 Installation & Setup
Ensure you have Python installed, then follow these steps:

1. Clone the Repository
git clone https://github.com/Abhi-K-Abhi/FirstComeFirstServed--Disk-Scheduling-Algorithm.git
cd FirstComeFirstServed--Disk-Scheduling-Algorithm

2. Install Dependencies
Install Dependencies

3. Run the Application
python FCFS_DS_Simulator.py

👨‍💻 Author & Developer
Abhibhai Patel Software Engineer | Full-Stack Developer | Data Architecture Enthusiast

GitHub: @Abhi-K-Abhi

LinkedIn: [Your LinkedIn URL Here]

Email: [Your Professional Email Here]

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

Instructions for your features branch:

1. Copy the content above into your README.md.
2. Update the LinkedIn and Email placeholders in the Author section.
3. Commit this to your features branch:

git add README.md
git commit -m "DOCS: Updated README with comprehensive project details and contact info"
git push origin features