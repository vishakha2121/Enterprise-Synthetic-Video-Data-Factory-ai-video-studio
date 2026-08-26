# 🎬 SynthVideo Factory

> **AI-Powered Synthetic Video Generation Platform for Physical AI**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![React 18](https://img.shields.io/badge/react-18-61dafb.svg)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.95+-009688.svg)](https://fastapi.tiangolo.com/)
[![Gemini AI](https://img.shields.io/badge/Gemini-AI-4285F4.svg)](https://deepmind.google/technologies/gemini/)

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [System Architecture](#-system-architecture)
- [Installation & Setup](#-installation--setup)
- [Quick Start Guide](#-quick-start-guide)
- [Usage Examples](#-usage-examples)
- [API Documentation](#-api-documentation)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact & Support](#-contact--support)

---

## 🎯 Overview

**SynthVideo Factory** is an end-to-end synthetic video generation platform designed for **Physical AI** applications. It generates high-quality, realistic training videos for:

- 🚗 **Autonomous Driving** - Urban traffic, highway scenarios, pedestrian crossings, adverse weather
- 🎥 **Surveillance Systems** - Crowd monitoring, security incidents, parking lot activities
- 🏭 **Manufacturing Processes** - Assembly lines, quality control, defect detection
- 🤖 **Robotics Training** - Navigation, manipulation, obstacle avoidance

### 🚀 The Problem We Solve

| Challenge | Our Solution |
|-----------|--------------|
| **Data Scarcity** | Unlimited generation of diverse scenarios |
| **Safety Risks** | Generate dangerous scenarios (accidents, malfunctions) safely |
| **High Costs** | 90% cheaper than real-world data collection |
| **Copyright Issues** | Rights-cleared, traceable synthetic data |
| **Rare Edge Cases** | Generate any scenario on-demand |

> **✨ Powered by Diffusion Models + Gemini AI** - Our system uses Gemini as an "intelligent director" to enhance prompt understanding and generate highly relevant, diverse synthetic videos.

---

## 🌟 Key Features

### 🎨 Video Generation
- **Text-to-Video**: Generate videos from natural language descriptions
- **Image-to-Video**: Create motion from static images
- **Video-to-Video**: Transform existing videos with new styles or scenarios
- **Batch Generation**: Generate multiple videos simultaneously

### 🎯 Domain-Specific Scenarios
- **Pre-built Templates**: 50+ scenarios across 4 domains
- **Custom Parameters**: Control duration, resolution, style, complexity
- **Weather Effects**: Rain, snow, fog, night, sunny
- **Dynamic Elements**: Moving objects, changing backgrounds, interactions

### 📊 Dataset Management
- **Production Projects**: Organize and batch generate training datasets
- **Quality Evaluation**: Auto-evaluate semantic consistency, motion quality
- **Metadata Tracking**: Full provenance and lineage of every video
- **Deduplication**: Perceptual hashing for diverse datasets

### 🎨 User Interface
- **Modern Dashboard**: Real-time statistics and quick actions
- **Live Preview**: See generation progress in real-time
- **Interactive Gallery**: Search, filter, and manage generated videos
- **Responsive Design**: Works on all screen sizes

### 🔧 Advanced Features
- **Gemini Prompt Enhancement**: AI-powered scene description expansion
- **Style Transfer**: Apply artistic styles to generated videos
- **Export Options**: MP4, AVI, GIF, and frame sequences
- **REST API**: Complete API for integration with other tools

---

## 🛠️ Technology Stack

### Backend (Python)
```yaml
Framework: FastAPI 0.95+
AI Models: Diffusion Models (Hugging Face Diffusers)
AI Service: Google Gemini API
Database: SQLAlchemy + SQLite/PostgreSQL
Video Processing: OpenCV, MoviePy
Orchestration: Apache Airflow (optional)
Authentication: JWT
Deployment: Docker, Nginx

Framework: React 18
UI Library: TailwindCSS + Material-UI
State Management: Context API + Redux
Animations: Framer Motion
Charts: ApexCharts
HTTP Client: Axios
Video Player: React Player
Routing: React Router v6


Containerization: Docker
Reverse Proxy: Nginx
CI/CD: GitHub Actions
Monitoring: Prometheus + Grafana (optional)
Logging: ELK Stack (optional)

git clone https://github.com/yourusername/synthvideo-factory.git
cd synthvideo-factory


# Create and activate virtual environment
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env and add your Gemini API key


cd ../frontend
npm install
# or
yarn install