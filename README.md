# Multi-Device Audio Route

## Description
Multi-Device Audio Router is a C# application that captures system audio and routes it to multiple output devices simultaneously. The application leverages **NAudio** and **WASAPI** to provide real-time audio routing, independent volume control, and adjustable delay for each output device. It is built with **.NET 6** and features a **WPF-based UI** for seamless user interaction.

## Features
- 🎵 **Real-time System Audio Capture**: Captures system audio using **WASAPI loopback**.
- 🔊 **Multi-Device Output Support**: Play system audio on multiple output devices at the same time.
- 🎚 **Independent Volume Control**: Adjust volume separately for each output device.
- ⏳ **Customizable Audio Delay**: Add different delays to different devices for synchronization.
- 🖥 **Intuitive WPF UI**: User-friendly graphical interface for easy control.
- 🛠 **Lightweight & Efficient**: Optimized for minimal latency and efficient CPU usage.

## Installation
### Prerequisites
- Windows 10/11
- .NET 6 or later
- Visual Studio (Recommended)

### Steps to Install and Run
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/MultiDeviceAudio.git
   cd MultiDeviceAudio
   ```
2. **Open the project**: Open `MultiDeviceAudio.sln` in Visual Studio.
3. **Install dependencies**:
   ```sh
   dotnet restore
   ```
4. **Build and run the application**:
   ```sh
   dotnet run
   ```

## Usage
1. **Launch the application**.
2. **Select output devices** from the list of available audio devices.
3. **Adjust volume and delay** for each device individually.
4. **Press Start** to begin routing system audio.
5. **Modify settings** in real-time as needed.

## Project Structure
```
MultiDeviceAudio
│── src/
│   ├── MultiDeviceAudio.sln               # Solution file
│   ├── MultiDeviceAudio/
│   │   ├── MultiDeviceAudio.csproj        # Project file
│   │   ├── Program.cs                     # Main application logic
│   │   ├── AudioProcessor.cs              # Handles audio processing
│   │   ├── AudioCapture.cs                # Captures audio from system
│   │   ├── DeviceManager.cs               # Manages audio devices
│   │   ├── UI/
│   │   │   ├── MainWindow.xaml            # UI Layout (WPF)
│   │   │   ├── MainWindow.xaml.cs         # UI Logic
│   │   │   ├── VolumeControl.xaml         # UI for volume control
│   │   │   ├── DelayControl.xaml          # UI for delay settings
│   ├── Dependencies/
│   │   ├── NAudio.dll                      # External Audio Library
│   │   ├── Newtonsoft.Json.dll             # JSON Handling
│── docs/                                   # Documentation
│   ├── README.md
│   ├── CONTRIBUTING.md
│   ├── LICENSE
│── .gitignore                              # Ignore unnecessary files
│── README.md                               # Project Overview
│── LICENSE                                 # License Information
```

## Technologies Used
- **C# .NET 6+** – Core application logic
- **NAudio** – Audio processing and routing
- **WASAPI (Windows Audio Session API)** – Capturing system audio
- **WPF (XAML)** – UI Design
- **GitHub Actions** – CI/CD Pipeline (Optional)

## Contribution
We welcome contributions! Follow these steps:
1. **Fork the repository**.
2. **Create a new branch**:
   ```sh
   git checkout -b feature-branch
   ```
3. **Commit your changes**:
   ```sh
   git commit -m "Added new feature"
   ```
4. **Push to GitHub**:
   ```sh
   git push origin feature-branch
   ```
5. **Open a Pull Request**.

## License
This project is licensed under the **MIT License** – You are free to use and modify it.

## Contact
For any issues or feature requests, please open an issue on **GitHub Issues** or contact **your_email@example.com**.

