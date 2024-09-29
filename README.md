# Employee Activity Tracking Agent

## Project Overview
This Python-based desktop agent application tracks employee activity and uploads screenshots to firebase storage. The application is designed to provide robust tracking features, manage configuration changes, and follow best practices in software development.

## Features
- **Activity Tracking**: Tracks employee activity by capturing screenshots at regular intervals.
- **Cloud Upload**: Automatically uploads captured screenshots to firebase storage.
- **Detect Time Zone Change**: Detect time zone changes on the user's system and adjust the timestamps.
- **Instance Management**: Ensures that only one instance of application is running.
- **Configuration Management**: Allows dynamic configuration changes, such as modifying screenshot intervals, upload schedules, and cloud storage preferences.
- **Secure and Efficient**: Uses encryption to securely transfer data and ensures minimal resource consumption on the client machine.
- **Error Handling & Logging**: Includes robust error handling and logging mechanisms to ensure reliable performance.
- **Cross-platform Compatibility**: Works on major operating systems (Windows, macOS, Linux).

## Installation

To install and run the application, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Suyash-Singh25/tracking-_agent.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python main.py
    ```

## Configuration

- **Screenshot Interval**: Define how often the screenshots should be taken.
- **Suspicion Threshold**: Enter max speed for mouse movement.
- **Min Randamness**: Threshold value used to determine the level of randomness in mouse movement.
- **Key Stroke Intervals**: Min threshold value that should elapse between keystrokes for the activity to be considered normal.

