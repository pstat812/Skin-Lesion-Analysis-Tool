# Skin Lesion Analysis Tool

## Introduction
The Skin Lesion Analysis Tool is a React Native application powered by machine learning for automated mole classification and skin lesion analysis. The app uses machine learning models to provide users with immediate feedback on potential skin concerns. It features binary classification and OpenAI GPT-4 for detailed evaluation of ABCD criteria, all wrapped in a modern, user-friendly interface with comprehensive history tracking.

## Showcase
- https://skin-lesion-analysis-tool.netlify.app/
  
## Features and Functionality

### 🔍 ** Mole Classification**
- **Binary Classification**: Automated Benign/Malignant classification using machine learning
- **Confidence Scoring**: Percentage confidence levels for each classification result
- **Real-time Processing**: Instant analysis upon image capture or selection

### 🎯 **Advanced ABCD Analysis**
- **Asymmetry Assessment**: Detailed scoring of mole symmetry (1-10 scale)
- **Border Evaluation**: Analysis of border regularity and definition
- **Color Analysis**: Assessment of color uniformity and variation patterns
- **Professional-grade Criteria**: Based on dermatological ABCD diagnostic standards

### 📊 **History Management**
- **Persistent Storage**: Automatic saving of all classification results
- **Smart Cleanup**: Automatic storage management with quota awareness

## Technology Stack
- **Frontend Framework**: React Native with Expo
- **Machine Learning**: TensorFlow.js, Teachable Machine
- **AI Integration**: OpenAI GPT-4 Vision API
- **Navigation**: Expo Router with typed routes
- **Storage**: AsyncStorage with automatic cleanup
