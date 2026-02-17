# Network Behavior Analysis using Python

This project focuses on analyzing network traffic behavior using Python to explore traffic patterns and basic anomaly indicators.  
The objective of this project is learning-based analysis of network datasets and understanding behavioral trends in network communication.

## Project Overview

In this project, exploratory data analysis was performed on network traffic data to:

- Study traffic distribution and behavioral patterns
- Identify unusual network activity through statistical analysis
- Visualize traffic insights using Python libraries

This project was completed as part of learning practice in network analytics and cybersecurity fundamentals.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

Dataset Used: NSL-KDD Dataset  
Reference Source: https://github.com/defcom17/NSL_KDD

## Key Analysis Performed

- Data cleaning and preprocessing
- Traffic pattern exploration
- Basic anomaly pattern visualization
- Statistical analysis of network features

## Reference

Original learning reference:
https://github.com/Ravi-Teja-konda/Network_traffic_analyzer

This repository is used for educational and learning purposes only.




## Future Enhancements

In the future, the Network Traffic Analyzer will include the following features:
- Plotting graphs w.r.t IP
- Calculating latency, packet loss, throughput, jitter, network utilization, and error rates

## Installation

1. Clone the repository:


2. Navigate to the project directory:
cd network-traffic-analyzer

3. Install the required dependencies:
pip install -r requirements.txt


## Usage

To analyze a PCAP file, run the following command:

python Network_traffic_analyzer.py <path_to_pcap_file> <port_scan_threshold>


Replace `<path_to_pcap_file>` with the path to your PCAP file, and `<port_scan_threshold>` with the desired threshold for detecting port scanning activities.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Scapy](https://github.com/secdev/scapy) for packet processing capabilities
- [Pandas](https://github.com/pandas-dev/pandas) for data manipulation and analysis
- [Matplotlib](https://github.com/matplotlib/matplotlib) for creating graphs and visualizations
