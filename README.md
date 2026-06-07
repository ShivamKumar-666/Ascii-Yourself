# CyberAscii (Ascii Yourself)

**A real-time webcam ASCII art generator with AI image analysis.**

## 👁️ Overview

**CyberAscii** transforms your real-time webcam feed into interactive, customizable ASCII art directly in the browser. Beyond just visual effects, it leverages the **Google Gemini API** to analyze captured frames and provide insightful, cyberpunk-themed descriptions of what it "sees" in the ASCII matrix.

## ✨ Features

- **Real-Time ASCII Rendering**: Transforms live camera feed into high-performance ASCII art.
- **Dynamic Controls**: Adjust font size, brightness, contrast, color modes (e.g., matrix green), and density on the fly.
- **AI Image Analysis**: Capture a frame and send it to the Gemini neural link for instant AI-powered analysis and threat-level assessment.
- **Cyberpunk Aesthetic**: Fully immersive HUD and UI elements built with Tailwind CSS.
- **Audio Feedback**: Immersive sound effects for scanning and analysis completion.

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS, Lucide React (Icons)
- **AI Integration**: Google GenAI SDK (`@google/genai`)

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- A Google Gemini API Key

### Installation

1. **Clone the repository or download the source code:**
   ```bash
   git clone <repository-url>
   cd "Ascii yourself"
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file in the root directory and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3000` (port defined in Vite configuration).

## 🎮 Usage

1. Grant camera permissions when prompted by your browser.
2. Use the **Control Panel** to tweak the ASCII appearance:
   - Change the color mode for different vibes.
   - Adjust resolution and density for more or less detail.
3. Click the **Capture** button to freeze a frame and run an AI analysis on the image.

---