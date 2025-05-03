# VocalVerse

<div align="center">

  <h3>The AI-Powered Singing Machine for Modern Music Production</h3>
  
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.14+-orange.svg)
  ![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green.svg)
  ![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Latest-blue.svg)
  ![React](https://img.shields.io/badge/React-18.0+-61DAFB.svg)
  ![D3.js](https://img.shields.io/badge/D3.js-7.8+-yellow.svg)
  ![SQLite](https://img.shields.io/badge/SQLite-3.42+-blueviolet.svg)
  ![Docker](https://img.shields.io/badge/Docker-Enabled-blue.svg)
  ![License](https://img.shields.io/badge/License-MIT-green.svg)
</div>

## 🎵 Overview

VocalVerse empowers musicians and producers to generate and manipulate AI-driven vocals with unparalleled control and precision. Built specifically for the Mimi MAMEEN music project, this tool combines the latest in voice synthesis technology with an intuitive interface designed for professional music production workflows.

Unlike generic AI voice tools, VocalVerse provides real-time visualization and manipulation capabilities that give artists the tactile control they need while maintaining the organic feel that's essential for compelling vocal performances.

![VocalVerse Screenshot](assets/screenshot.png)

## ✨ Key Features

### Advanced Voice Synthesis
- **AI-Powered Vocal Generation**: Create realistic singing vocals using cutting-edge machine learning models
- **Style Customization**: Adjust timbre, texture, and emotional qualities of the generated voice
- **Lyric-to-Vocal Conversion**: Transform written lyrics into professionally sung vocal tracks
- **Multi-language Support**: Generate vocals in various languages with proper pronunciation

### Real-time Audio Controls
- **Dynamic Parameter Adjustment**: Fine-tune vocals with intuitive sliders and knobs
- **Performance Modulation**: Add vibrato, breathiness, and other vocal techniques on the fly
- **Pitch and Timing Control**: Precise manipulation of melodic elements
- **Expression Mapping**: Link expressive qualities to controller movements

### Visualization & Feedback
- **Real-time Waveform Display**: See vocal audio rendered as interactive waveforms
- **Spectral Analysis**: Visualize frequency content for precise tonal adjustments
- **Performance Metrics**: Monitor key vocal characteristics with dynamic gauges
- **A/B Comparison**: Compare different vocal takes with visual reference points

### Production Integration
- **Session Management**: Save, load, and organize vocal projects
- **Export Options**: Output in various formats compatible with major DAWs
- **Preset System**: Store and recall your favorite vocal configurations
- **Batch Processing**: Apply vocal styles to multiple tracks

## 🛠️ Technology Stack

VocalVerse is built on a modern, robust technology stack designed for performance and flexibility:

### Backend Components
- **TensorFlow**: Powers the vocal synthesis neural networks
- **FastAPI**: Provides high-performance API endpoints for the vocal processing engine
- **SQLite**: Lightweight database for storing vocal presets and session information

### Frontend Components
- **React**: Responsive and interactive user interface framework
- **Web Audio API**: Low-latency audio processing and playback
- **D3.js**: Advanced data visualization for audio waveforms and controls

### Infrastructure
- **Docker**: Containerized deployment for consistent performance across environments
- **Nginx**: Efficient web server configuration for optimized asset delivery
- **WebSockets**: Real-time communication between frontend and backend components

## 🚀 Getting Started

### Prerequisites
- Docker and Docker Compose
- Modern web browser (Chrome, Firefox, or Edge recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/darbybailey/vocalverse.git
cd vocalverse
```

2. Start the application using Docker Compose:
```bash
docker-compose up
```

3. Access the application:
   - Frontend interface: [http://localhost:3000](http://localhost:3000)
   - API documentation: [http://localhost:8000/docs](http://localhost:8000/docs)

### Quick Tour

After launching VocalVerse, you'll be presented with the main dashboard containing:

1. **Vocal Synthesis Panel**: Controls for generating and shaping the AI voice
2. **Waveform Display**: Real-time visualization of the audio output
3. **Parameter Controls**: Sliders and knobs for fine-tuning the vocal performance
4. **Session Manager**: Tools for saving and loading your work

## 📊 Vocal Synthesis Workflow

VocalVerse streamlines the process of creating AI-powered vocals:

### 1. Voice Design
- Select base vocal characteristics (gender, age, tone)
- Adjust timbre and texture parameters
- Define stylistic elements (genre, emotional quality)

### 2. Lyric Input
- Type or paste lyrics directly into the interface
- Import lyrics from text files
- Apply phonetic adjustments for precise pronunciation

### 3. Performance Shaping
- Set melodic parameters (pitch range, intervals)
- Define rhythmic elements (tempo, phrasing)
- Add expressive qualities (vibrato, dynamics, breathiness)

### 4. Real-time Manipulation
- Use interactive controls to adjust the performance while listening
- Visualize changes in the waveform display
- Fine-tune until the desired vocal quality is achieved

### 5. Export & Integration
- Save the vocal track in various audio formats
- Export with or without effects
- Integrate directly with your DAW workflow

## 🎛️ Advanced Controls

VocalVerse provides deep control over vocal characteristics:

### Tonal Parameters
- **Formant Shift**: Adjust the vocal tract resonance
- **Brightness**: Control the high-frequency content
- **Warmth**: Shape the mid-range frequencies
- **Body**: Manage low-frequency resonance

### Dynamic Controls
- **Attack**: Adjust the onset of vocal phrases
- **Sustain**: Control the stability of held notes
- **Release**: Shape the decay of vocal phrases
- **Compression**: Balance the dynamic range

### Expressive Elements
- **Vibrato Rate**: Set the speed of pitch fluctuation
- **Vibrato Depth**: Control the intensity of pitch variation
- **Breathiness**: Add air noise to the vocal tone
- **Emotion Intensity**: Scale the emotional expressiveness

## 🧩 Use Cases

### Songwriting & Composition
Perfect for quickly testing melodies and lyrical ideas without needing to record scratch vocals.

### Production & Arrangement
Generate backing vocals, harmonies, and vocal layers to enhance your productions.

### Vocal Prototyping
Test different vocal approaches before committing to a particular style or performance.

### Creative Experimentation
Explore unique vocal textures and techniques that may be difficult to achieve with traditional recording.

## 📈 Performance Insights

The built-in analysis tools provide valuable feedback on your vocal creations:

### Spectral Analysis
- View the frequency distribution of your vocals
- Identify and address problematic frequencies
- Ensure proper tonal balance

### Dynamic Representation
- Monitor the amplitude envelope
- Visualize the energy distribution over time
- Ensure consistent levels across phrases

### Timbral Mapping
- See how vocal characteristics map across different dimensions
- Compare against reference vocals
- Optimize for specific genres or styles

## 🔌 Integration Options

VocalVerse is designed to work seamlessly with your existing music production workflow:

### DAW Integration
- Export directly to popular digital audio workstations
- Sync with your project tempo and key
- Maintain full editability of vocal parameters

### Collaboration Features
- Export share-friendly project files
- Import collaborator adjustments
- Track version history across team members

### Extended Ecosystem
- Connect with other vocal processing tools
- Interface with MIDI controllers for tactile control
- Export to various cloud storage solutions

## 🧠 The Technology Behind VocalVerse

VocalVerse leverages several key technologies to deliver its unique capabilities:

### Neural Voice Synthesis
- Deep learning models trained on diverse vocal performances
- Specialized architecture for singing voice generation
- Real-time inference engine for responsive feedback

### Acoustic Modeling
- Physical modeling of the human vocal tract
- Spectral processing for natural timbral characteristics
- Articulatory simulation for realistic phoneme production

### Interactive Visualization
- Custom D3.js visualizations for audio representation
- WebGL acceleration for smooth waveform rendering
- Responsive design for optimal use across devices

## 🗃️ Project Structure

```
vocalverse/
├── backend/                # FastAPI server and AI models
│   ├── api/                # API endpoints
│   ├── models/             # TensorFlow vocal models
│   └── utils/              # Helper functions
├── frontend/               # React application
│   ├── components/         # UI components
│   ├── hooks/              # Custom React hooks
│   └── visualizations/     # D3.js visualization code
├── data/                   # SQLite database and training data
├── docker/                 # Docker configuration
└── docs/                   # Documentation
```

## 🤝 Contributing

Contributions to VocalVerse are welcome! This is a personal project for creating music, but if you're interested in collaborating, please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- The open source voice synthesis community
- The TensorFlow and FastAPI development teams
- The D3.js visualization library community
- All musicians who have shared their voices and expertise

---

<div align="center">
  <p>Created by Dr. Darby Bailey McDonough | Mimi MAMEEN Music Project</p>
  <p>For inquiries: darbmcd@mail.regent.edu</p>
</div>