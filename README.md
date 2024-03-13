# Economic Surveillance Bot

The Economic Surveillance Bot is an innovative solution designed to provide cost-effective economic surveillance. Utilizing an microcontroller programmed in C, this bot responds to hand gestures, enabling precise navigation. Compared to market alternatives, this solution achieves a remarkable 20% cost reduction.

## Usage Instructions

### Client-side Code (final_code_client)

- Ensure your system has Python installed along with the following libraries: OpenCV, dlib, and socket.
- Upload the `final_code_client.py` onto your system. This code enables facial recognition and landmark detection.
- Adjust parameters such as IP address, port number, and directories according to your system requirements.

### Server-side Code (final_code_server)

- Upload the `final_code_server.py` onto your Raspberry Pi.
- This code contains commands for controlling the robot's mobility. Ensure the Raspberry Pi has a constant internet connection and the socket library installed.
- Adjust parameters such as IP address and port number according to your requirements.

### Additional File (shape_predictor_68_face_landmarks.dat.bz2)

- This zipped file contains data for facial landmarks, necessary for facial recognition.
- Ensure this file is available alongside the client Python file for accurate facial recognition.

### Threshold Values

- Threshold values have been determined through trial and error due to varying lighting conditions in different environments.
- Adjust threshold values as needed for optimal performance in your specific environment.

## Getting Started

1. Clone this repository onto your local machine.
2. Set up the client and server-side code as per the instructions provided.
3. Adjust parameters and threshold values according to your system requirements.
4. Test the economic surveillance bot and enjoy its cost-effective functionality!

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it for commercial or non-commercial purposes.

## Acknowledgments

We acknowledge the valuable contributions of the development team in creating this cost-effective solution for economic surveillance. Your efforts have enabled the realization of an efficient and affordable surveillance bot.
