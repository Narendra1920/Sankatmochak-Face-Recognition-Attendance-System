
# Face Recognition-Based Attendance System for Sankatmochak Volunteers

This project is part of the **Sankatmochak Disaster Management System** aimed at automating the attendance process for Sankatmochak volunteers using face recognition technology. The system helps streamline the attendance tracking of volunteers, ensuring an efficient and accurate management process during disaster operations.

## Features

- Real-time face recognition-based attendance system
- Automatically marks attendance upon successful face detection
- Efficient data management and storage using CSV files
- User-friendly interface developed using `tk-tools`
- Secure and easy to deploy

## Tech Stack

- **Programming Language**: Python
- **Libraries Used**:
  - `tk-tools` (for GUI interface)
  - `opencv-contrib-python` (for face recognition and image processing)
  - `datetime` (for date and time operations)
  - `pytest-shutil` (for testing purposes)
  - `python-csv` (for handling CSV files)
  - `numpy` (for numerical operations)
  - `pillow` (for image handling)
  - `pandas` (for data manipulation)
  - `times` (for managing time-related operations)

## Installation

To set up the project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Narendra1920/Sankatmochak-Face-Recognition-Attendance-System
   ```

2. Navigate to the project directory:

   ```bash
   cd Sankatmochak-Face-Recognition-Attendance-System
   ```

3. Install the required Python libraries:

   ```bash
   pip install tk-tools opencv-contrib-python datetime pytest-shutil python-csv numpy pillow pandas times
   ```

## How It Works

1. **Face Registration**: Volunteers register their face in the system. The system stores their facial data for future attendance marking.
2. **Face Recognition**: During attendance, the system captures real-time video and compares the faces in the frame with the stored facial data.
3. **Attendance Logging**: Once the system recognizes a face, it marks attendance and logs it in a CSV file along with the current date and time.

## Usage

1. Run the main script to launch the application:

   ```bash
   python main.py
   ```

2. Use the GUI to register new volunteers, take attendance, and view attendance records.

## Project Structure

```
├── data/
│   └── attendance.csv     # Stores attendance records
├── images/
│   └── registered_faces/  # Stores images of registered volunteers
├── main.py                # Main script to run the system
├── requirements.txt       # List of required libraries
└── README.md              # Project documentation
```

## Future Enhancements

- Integration with the broader **Sankatmochak Disaster Management System** for seamless coordination
- Advanced face recognition using deep learning models
- Improved UI/UX for better user experience

## License

This project is licensed under the MIT License.

## Acknowledgements

This system is developed as a part of the **Sankatmochak Disaster Management System**, a comprehensive project aimed at assisting during disaster recovery operations.

