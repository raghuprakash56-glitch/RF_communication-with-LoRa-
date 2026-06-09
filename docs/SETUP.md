# Setup Guide

## Hardware Requirements

- LoRa Module (SX1276, RFM95W, or compatible)
- Microcontroller or Raspberry Pi
- USB-to-Serial adapter (if needed)
- Antenna suitable for LoRa frequency

## Software Installation

### 1. Clone the Repository

```bash
git clone https://github.com/raghuprakash56-glitch/RF_communication-with-LoRa-.git
cd RF_communication-with-LoRa-
```

### 2. Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Configuration

1. Update configuration files with your LoRa module settings
2. Set serial port settings (baud rate, port name)
3. Configure frequency and other RF parameters

## Testing Installation

```bash
python -m pytest tests/
```

## Troubleshooting

- Ensure LoRa module is properly connected
- Check serial port configuration
- Verify antenna is properly attached
- Review debug logs for detailed error information

## Next Steps

- Check `examples/` directory for sample code
- Read the main README.md for usage examples
- Refer to LoRa module datasheet for specifications
