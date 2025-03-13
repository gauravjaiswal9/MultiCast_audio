
# 🎧 MultiDeviceAudioUi 🎵  
*A feature-rich C# application for capturing and playing audio on multiple output devices with customizable settings.*  

---

## 📌 Features  
✅ **Multi-Device Audio Playback** – Route system audio to multiple output devices.  
✅ **Device Selection** – Choose which output devices should play the audio.  
✅ **Per-Device Volume Control** – Adjust the volume level for each output device.  
✅ **Custom Delay Control ⏳** – Add and modify delay separately for each device.  
✅ **Live Audio Monitoring** – Visualize the current playback status.  
✅ **Low Latency Processing** – Optimized to reduce playback delays.  
✅ **User-Friendly UI 🎨** – Modern interface for an intuitive experience.  

---

### 🛠️ Tech Stack  
🔹 **Language:** C# (.NET)  
🔹 **Framework:** WPF (Windows Presentation Foundation)  
🔹 **Audio Library:** NAudio  
🔹 **UI Framework:** XAML  
🔹 **Build System:** Visual Studio  

---

### 📂 Project Structure  
```
MultiDeviceAudioUI.sln
└── MultiDeviceAudioUI
    ├── App.xaml
    ├── App.xaml.cs
    ├── MainWindow.xaml
    ├── MainWindow.xaml.cs
    ├── Models
    │   └── OutputDeviceSetting.cs
    └── AudioProcessing
        ├── DeviceAudioPipeline.cs
        └── DelaySampleProvider.cs

```

---

## 🚀 Installation & Setup  
### 1️⃣ Prerequisites  
- Install **Visual Studio** (latest version)  
- Install **.NET 6.0 or higher**  
- Install **NAudio NuGet Package** (`Install-Package NAudio`)  

### 2️⃣ Clone Repository  
```bash
git clone https://github.com/yourusername/MultiDeviceAudioUi.git
cd MultiDeviceAudioUi
```

### 3️⃣ Build & Run  
1. Open **MultiDeviceAudioUi.sln** in **Visual Studio**  
2. Restore dependencies  
3. Click **Start** (or press `F5`) to run the application  

---

## 🎨 UI Preview  
🚧 (https://github.com/gauravjaiswal9/MultiCast_audio/blob/2f904481e18491c53fb9e1e77ee7175583dbb505/1.png)

---

## 🤝 Contributing  
🔹 Fork this repository  
🔹 Create a feature branch (`git checkout -b feature-name`)  
🔹 Commit changes (`git commit -m "Add new feature"`)  
🔹 Push to branch (`git push origin feature-name`)  
🔹 Open a pull request  

---

## ⚖️ License  
📜 This project is licensed under the **MIT License** – feel free to modify and use it.  

---
