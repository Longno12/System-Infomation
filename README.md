When you run this script, it will print detailed information about your system, including Windows version, CPU name, and GPU details, along with previously included information.

# PC Specs Viewer

This Python script gathers and displays your PC's specifications, such as CPU, memory, disk usage, and GPU information. It uses the `psutil` and `GPUtil` libraries to retrieve the relevant system details.

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
    ```

## Usage

1. Clone the repository or download the script to your local machine.

    ```sh
    git clone https://github.com/yourusername/pc-specs-viewer.git
    cd pc-specs-viewer
    ```

2. Run the script:

    ```sh
    python pc_specs_viewer.py
    ```

3. The script will print your PC's specifications in the terminal.

## Example Output

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



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

If you have suggestions for improving this script, please submit an issue or a pull request. Contributions are welcome!

## Acknowledgements

- [psutil](https://github.com/giampaolo/psutil)
- [GPUtil](https://github.com/anderskm/gputil)


