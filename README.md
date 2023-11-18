# DataLinkGSM: Data Transmission Over GSM Voice Channel 📶📲

DataLinkGSM is a project designed to facilitate data transmission over a GSM voice channel using frequency shift keying (FSK). By modulating the frequency of an audio signal, this project enables data transmission and reception using a Python script on a computer equipped with a sound card and a GSM modem.

## Installation and Usage 🛠️

To use DataLinkGSM:

1. Install `Python 3.x` on your computer.

2. Connect your `sound card` and `GSM modem` to your computer.

3. Install the necessary Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Python script:

   ```bash
   python main.py
   ```

5. Follow the instructions displayed in the console to input your message and phone number for transmission.

## Limitations 🚫

DataLinkGSM has certain limitations:
1. **Compatibility**: It only operates with GSM networks.
2. **Transmission Speed**: The speed is constrained by the bandwidth of the GSM voice channel.
3. **Scale**: It's not intended for large-scale data transmission.

Feel free to explore, contribute, or use DataLinkGSM for transmitting data over GSM voice channels in a convenient and accessible manner.
