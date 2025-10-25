# 🎨 OpenCV Cartoon Webcam Project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv&logoColor=white)

A **Data Science project** that cartoonizes your webcam feed in real-time using **OpenCV** in Python. Transform your live video into a fun cartoon-style animation! 🖼️

---

## 🖥️ Features

- **Cartoonify** your live webcam feed  
- **Real-time processing** with adjustable smoothing and edge detection  
- **Optional**: Save the cartoonized video output  

---

## ⚙️ Requirements

- **Python 3.x**  
- **OpenCV library**  

Install OpenCV using pip:

```bash
pip install opencv-python
🛠️ Setup & Usage
Clone the repository:
git clone https://github.com/pandeymehak217-lab/OpenCV-Cartoon-Webcam.git
cd OpenCV-Cartoon-Webcam
Run the script:
python cartoon.py
Controls:
Webcam feed will open in a new window
Press q to exit
Optional: Save Cartoonized Video
Uncomment or add the following in your script:
# Define video writer
fourcc = cv2.VideoWriter_fourcc(*'XVID')
out = cv2.VideoWriter('cartoon_output.avi', fourcc, 20.0, (width, height))

# Inside the loop, write frames
out.write(cartoon_frame)

# Release the writer at the end
out.release()
This saves the cartoonized webcam feed as cartoon_output.avi.
🧠 About
This project demonstrates computer vision techniques to process live video and apply cartoon effects. It’s a fun way to explore Python and OpenCV capabilities while learning real-time image processing.
📂 Repository Structure
OpenCV-Cartoon-Webcam/
├─ cartoon.py        # Main script to process webcam feed
├─ README.md         # Project documentation
📸 Preview
⚡ Tips
Adjust smoothing and edge detection parameters in cartoon.py to customize the cartoon effect
Works best with a well-lit environment for clearer output
