# FieldKit 📱

Cross-platform mobile field data collection app for water utility operations.

## 🎯 Overview

Unified mobile application providing offline-first field data collection across all Trident Systems modules. Built for water operators who work in areas with poor connectivity.

## 🚀 MVP Scope

### Core Features
- **Offline-First Architecture**: Work without internet, sync when connected
- **Cross-Product Forms**: Dynamic form engine supporting all Trident modules
- **Media Capture**: Photos, videos, audio notes with GPS tagging
- **QR/Barcode Scanning**: Asset identification and data lookup
- **GPS Integration**: Automatic location capture and mapping

### Supported Operations
- **Hydrant Testing**: NFPA 291 flow tests with pitot pressure capture
- **Pipeline Inspections**: Valve operations, leak detection, condition assessments
- **Asset Surveys**: GPS coordinate collection and photo documentation
- **Work Orders**: Field completion and status updates

## 📱 Platform Support

- **iOS**: Native Swift/SwiftUI application
- **Android**: Native Kotlin/Jetpack Compose application
- **Shared Logic**: React Native with platform-specific modules

## 🛣️ Roadmap

### Phase 1 (Q1 2026)
- React Native foundation with offline SQLite
- Basic form engine and photo capture
- GPS coordinate collection
- Sync engine with conflict resolution

### Phase 2 (Q2 2026)
- QR/barcode scanning integration
- Advanced camera features (measurement, annotation)
- Voice-to-text note capture
- Bluetooth device integration (pressure gauges, flow meters)

### Phase 3 (Q3 2026)
- Augmented reality (AR) asset overlay
- Machine learning asset recognition
- Advanced analytics and field insights
- Team collaboration features

## 🏗️ Technology Stack

- **Framework**: React Native 0.72+
- **Database**: SQLite with WatermelonDB
- **Maps**: React Native Maps with offline tiles
- **Camera**: React Native Vision Camera
- **Sync**: Custom sync engine with PostgreSQL backend
- **State Management**: Zustand

## 🔗 Integration Points

- **HydrantHub**: Flow testing data collection and photo documentation
- **Pipeline Manager**: Valve inspections and main condition assessments
- **GIS Service**: Coordinate capture and spatial data validation
- **Compliance Engine**: Inspection checklists and regulatory documentation

## 📊 Key Features

### Offline Capabilities
- Complete app functionality without internet
- Local data storage with encryption
- Automatic sync when connectivity returns
- Conflict resolution for concurrent edits

### Field-Optimized UX
- Large touch targets for gloved hands
- High contrast mode for bright sunlight
- Voice commands and audio feedback
- Quick data entry workflows

### Data Quality
- Real-time validation and error checking
- Mandatory field enforcement
- Photo quality assessment
- GPS accuracy indicators

---

*Part of the Trident Systems water utility platform ecosystem*