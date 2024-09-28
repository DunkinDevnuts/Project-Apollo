# Project-Apollo

Project Apollo strives to explore the transient metrics advertised by an OBD II scanner by reading data over bluetooth from an ESP32. The data is displayed visually and dynamically in a dashboard. Created by engineers with an interest in cars, control systems, software, and data, Apollo is a project of curiosity fittingly named after the Greek God of knowledge and grandson of the Greek Titan of curiosity, Coeus.

## 🔄 Data Flow

The data is read from the ECU via an OBD II which has bluetooth broadcasting capabilities. An ESP32 connects to the scanner and receives the stream of packets, extracts metrics of interest, performs calculations, and generates plots.
