# 🛠️ Linux Launcher Creator

You can stop manually crafting `.desktop` files! **Linux Launcher Creator** is a Java GUI application that simplifies adding custom programs to your Linux application menu. With just a few inputs, it builds and installs launchers that appear right alongside your regular apps.

---

## ✨ Features

- **User-Friendly Interface**  
  Built with Swing/AWT via NetBeans for intuitive input and quick launcher creation.

- **Smart File Detection**  
  Automatically prepends execution commands like `java -jar`, `java`, or `python3` based on your file type.

- **Valid .desktop Generation**  
  Generates clean launcher files using your specified path, name, and icon.

- **Seamless Integration**  
  Installs launchers to `~/.local/share/applications/` so they show up system-wide.

- **Permission Handling**  
  Applies executable permissions automatically—no chmod or priviledge-related headaches.

---

## 🧱 Tech Used

| Language | Tools          | Purpose                          |
|----------|----------------|----------------------------------|
| Java     | Swing / AWT    | Core logic and GUI               |

---

## 🏁 Getting Started

### Prerequisites

- Java Development Kit (JDK) installed  
  [Download JDK](https://www.oracle.com/java/technologies/javase-downloads.html) or use OpenJDK.

---

### Installation & Running

**Option 1: NetBeans (Recommended)**  
- Open the project in NetBeans  
- Click “Run Project”

---

## 💡 Usage

1. **Program Path** – Full path to the executable (.jar, .py, or binary)  
2. **Program Name** – The name shown in your application menu  
3. **Icon Path** – Full path to an image file (.png, .svg, .xpm)  

Click **“Create!”** to generate and install your launcher. It’ll be ready to use from your system menu—though some desktops might require a restart or logout to reflect changes.

---

## 📄 License

This project is licensed under the MIT License—see the LICENSE file for details.

