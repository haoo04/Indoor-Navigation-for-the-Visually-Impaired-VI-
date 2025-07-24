# Indoor-Navigation-for-the-Visually-Impaired-VI-

## System Architecture

The system is divided into **four modules**:

1. **QR Code Detection**  
   - Detect red/green/blue QR codes through webcam input.  
   - Determine direction vector between user and QR code.  
   - Give real-time feedback to guide camera alignment.

2. **QR Code Reader**  
   - Decode QR code to obtain current location metadata.  
   - Determine possible exit directions encoded in the QR.

3. **Route Guidance Module**  
   - Map floor layout as a graph data structure.  
   - Compute shortest path from source to destination (e.g., Dijkstra’s algorithm).  
   - Provide step-by-step navigation feedback.

4. **User Interface (UI)**  
   - Voice output via text-to-speech for turn-by-turn navigation.  
   - Optional terminal or GUI display for debugging.

### Clone the Repository

```bash
git clone https://github.com/haoo04/Indoor-Navigation-for-the-Visually-Impaired-VI-.git
