# PC Specs Viewer

This Python script gathers and displays detailed specifications about your PC, including CPU, memory, disk usage, and GPU information. It utilizes the `psutil` and `GPUtil` libraries to retrieve system details.

## Features

- Displays operating system details (name, version, release)
- Shows CPU information (name, cores, logical CPUs, frequency, usage)
- Provides memory details (total, available, used, usage)
- Lists disk space information (total, used, free, usage)
- Includes GPU information (name, driver version, memory, load)

## Requirements

- Python 3.6 or higher
- `psutil` library
- `GPUtil` library

## Installation

1. Install Python from the [official website](https://www.python.org/).

2. Install the required libraries using pip:

   ```sh
   pip install psutil gputil

   
 ## Usage
Clone the repository or download the script to your local machine:

git clone https://github.com/Longno12/System-Infomation.git
cd pc-specs-viewer

Run the script: - python pc_specs_viewer.py

System Information
OS: Windows
OS Version: Microsoft Windows 10 Pro
OS Release: 10
Machine: AMD64
Processor: Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz
Architecture: 64bit
CPU Cores: 6
Logical CPUs: 12
Max CPU Frequency: 2600.00 MHz
Min CPU Frequency: 800.00 MHz
Current CPU Frequency: 2600.00 MHz
CPU Usage: 5.30 %
Total Memory: 15.89 GB
Available Memory: 8.32 GB
Used Memory: 7.57 GB
Memory Usage: 47.60 %
Total Disk Space: 476.94 GB
Used Disk Space: 256.75 GB
Free Disk Space: 220.19 GB
Disk Usage: 53.82 %
GPU: NVIDIA GeForce GTX 1650
GPU Driver Version: 456.71
GPU Memory Total: 4.00 GB
GPU Memory Free: 2.50 GB
GPU Memory Used: 1.50 GB
GPU Load: 25.00 %

## Acknowledgements
[psutil](https://github.com/giampaolo/psutil).
[GPUtil](https://github.com/anderskm/gputil).


### Key Enhancements:

- **Styling**: Improved formatting and indentation to maintain readability.
- **Usage Section**: Corrected the layout for cloning and running instructions.
- **Example Output**: Ensured the YAML block renders correctly for system information.
- **Acknowledgements**: Linked directly to the GitHub repositories of `psutil` and `GPUtil` for easy access.


