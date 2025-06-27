# Advanced System Information GUI

[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)]
[![License](https://img.shields.io/badge/license-MIT-green)]

A comprehensive system information tool with graphical interface that displays real-time PC specifications and performance metrics.

## Features

### System Overview
- Operating system details (name, version, release)
- Machine architecture and processor information
- Real-time performance monitoring

### Hardware Monitoring
- **CPU**: 
  - Name, cores, architecture
  - Frequency (current/min/max)
  - Usage per core (with color coding)
  
- **Memory**:
  - Total/available/used RAM
  - Swap space information
  - Usage percentage with progress bar

- **Storage**:
  - Disk partitions and filesystems
  - Space usage (total/used/free)
  - Usage percentage with warnings

- **GPU**:
  - Model and driver version
  - Memory utilization (total/used/free)
  - Load percentage

- **Network**:
  - Interface list with IP/MAC addresses
  - Connection status indicators

## Requirements

- Python 3.6 or higher
- Required packages:
  pip install pyqt5 psutil gputil

## Installation

1. Clone the repository:
   git clone https://github.com/Longno12/System-Infomation.git
   cd System-Infomation

2. Install dependencies:
   pip install -r requirements.txt

## Usage

Run the application:
python system_info_gui.py

### Interface Guide
- **Summary Tab**: Quick overview of key system components
- **CPU Tab**: Detailed processor information and core usage
- **Memory Tab**: RAM and swap space utilization
- **Disk Tab**: Storage devices and usage statistics
- **GPU Tab**: Graphics card specifications
- **Network Tab**: Network interfaces and status

## Exporting Data

Click the "Export System Info" button to save your system information as:
- JSON (structured data)
- Text file (human-readable format)

## Example Output

{
  "system": {
    "os": "Windows 10",
    "version": "10.0.19045",
    "architecture": "64-bit"
  },
  "cpu": {
    "model": "Intel Core i7-9750H",
    "cores": 6,
    "usage": 15.2
  },
  "memory": {
    "total": "16 GB",
    "used": "8.4 GB",
    "percentage": 52.5
  }
}

## Troubleshooting

- **GPU not detected**: Ensure you have the latest drivers installed
- **Permission errors**: Run as administrator/root if needed
- **Missing dependencies**: Verify all packages are installed correctly

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for:
- Bug fixes
- New features
- Translation improvements
- Documentation updates

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- psutil (https://github.com/giampaolo/psutil) - System monitoring library
- GPUtil (https://github.com/anderskm/gputil) - GPU monitoring library
- PyQt5 (https://www.riverbankcomputing.com/software/pyqt/) - GUI framework
