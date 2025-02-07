## **Hand Gesture Recognition with MediaPipe and OpenCV**

This project demonstrates **real-time hand gesture recognition** using **MediaPipe** and **OpenCV**. It detects hand gestures through webcam input, counts the number of raised fingers, and displays the result on-screen. This system can be used for applications requiring gesture-based interaction, such as controlling devices or interacting with user interfaces.

---

## **Features**

### **1. Real-time Hand Detection**
- Uses **MediaPipe** to detect hand landmarks in real-time from the webcam feed.
- Provides accurate hand detection for multiple hands simultaneously.
  
### **2. Finger Counting**
- Identifies raised fingers based on the position of hand landmarks.
- Counts the number of raised fingers and displays the result on the screen.

### **3. Interactive Webcam Feed**
- The webcam feed is displayed with the detected hand landmarks and finger count.
- The feed is flipped horizontally for a mirror effect, simulating interaction.

### **4. Gesture-Based Control**
- Recognizes different gestures based on the number of raised fingers (e.g., open hand, fist, etc.).
- The system can be extended to trigger actions based on specific gestures.

---

## **Libraries Used**

### **1. MediaPipe**
- **MediaPipe** is used for hand landmark detection. It provides a reliable and efficient way to track hand movements and gestures.

### **2. OpenCV**
- **OpenCV** is used for capturing the webcam feed, processing frames, and displaying the output.

### **3. NumPy**
- **NumPy** is used for numerical operations when working with hand landmarks.

---

## **Installation**

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
