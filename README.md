# Face Recognition Based Attendance System

This is a Python-based desktop application that uses face recognition to automate the attendance process. It captures facial images, trains a model, and tracks real-time attendance using a webcam. The application features a user-friendly graphical interface built with `Tkinter`.

## 🚀 Features

- 🎥 Face detection using OpenCV Haar cascades
- 🧠 Face recognition using LBPH (Local Binary Pattern Histogram)
- 📝 Secure password-protected access to model training
- 🧍 Student registration with image capture
- 📊 Real-time attendance tracking with date and time
- 🗃️ Stores data in CSV files (attendance & student profiles)
- 🖥️ Easy-to-use GUI for all operations

## 📁 Project Structure

├── Attendance/ # Attendance CSVs
├── StudentDetails/ # Student registration CSV
├── TrainingImage/ # Captured face images
├── TrainingImageLabel/ # Trained model and password file
├── haarcascade_frontalface_default.xml
├── main.py # Main application script


## 🛠️ Requirements

- Python 3.x
- OpenCV (`opencv-contrib-python`)
- dlib
- imutils
- pandas
- Pillow

Install requirements:
```bash
pip install opencv-contrib-python dlib imutils pandas pillow
📸 How It Works
Register New User

Enter ID and Name.

Capture 100 facial images using webcam.

Images saved in TrainingImage/.

Train the Model

Password-protected step.

Trains LBPH face recognizer.

Saves model in TrainingImageLabel/Trainner.yml.

Mark Attendance

Webcam detects and recognizes faces.

Recognized faces are marked present.

Attendance saved in Attendance/Attendance_<DATE>.csv.

🔐 Security
Password required to train model.

Password is stored in plaintext in TrainingImageLabel/psd.txt (⚠️ For demo only — consider hashing for production use).

🖼️ GUI Overview
Left panel: Attendance display

Right panel: New student registration

Top: Date and time

Menu: Change password, contact, exit

✅ To Run the App
bash
Copy
Edit
python main.py
📧 Contact
For any queries, please contact: gamingkeybo@gmail.com

📌 Notes
Works best in well-lit environments.

Press q to stop image capture or attendance recognition.

Make sure your webcam is functional and accessible.

📜 License
This project is open-source and available under the MIT License.
Here’s a clean and professional `README.md` file content tailored for your **Face Recognition Based Attendance System** project:

---

```markdown
# Face Recognition Based Attendance System

This is a Python-based desktop application that uses face recognition to automate the attendance process. It captures facial images, trains a model, and tracks real-time attendance using a webcam. The application features a user-friendly graphical interface built with `Tkinter`.

## 🚀 Features

- 🎥 Face detection using OpenCV Haar cascades
- 🧠 Face recognition using LBPH (Local Binary Pattern Histogram)
- 📝 Secure password-protected access to model training
- 🧍 Student registration with image capture
- 📊 Real-time attendance tracking with date and time
- 🗃️ Stores data in CSV files (attendance & student profiles)
- 🖥️ Easy-to-use GUI for all operations

## 📁 Project Structure

```

├── Attendance/               # Attendance CSVs
├── StudentDetails/          # Student registration CSV
├── TrainingImage/           # Captured face images
├── TrainingImageLabel/      # Trained model and password file
├── haarcascade\_frontalface\_default.xml
├── main.py                  # Main application script

````

## 🛠️ Requirements

- Python 3.x
- OpenCV (`opencv-contrib-python`)
- dlib
- imutils
- pandas
- Pillow

Install requirements:
```bash
pip install opencv-contrib-python dlib imutils pandas pillow
````

## 📸 How It Works

1. **Register New User**

   * Enter ID and Name.
   * Capture 100 facial images using webcam.
   * Images saved in `TrainingImage/`.

2. **Train the Model**

   * Password-protected step.
   * Trains LBPH face recognizer.
   * Saves model in `TrainingImageLabel/Trainner.yml`.

3. **Mark Attendance**

   * Webcam detects and recognizes faces.
   * Recognized faces are marked present.
   * Attendance saved in `Attendance/Attendance_<DATE>.csv`.

## 🔐 Security

* Password required to train model.
* Password is stored in plaintext in `TrainingImageLabel/psd.txt` (⚠️ For demo only — consider hashing for production use).

## 🖼️ GUI Overview

* Left panel: Attendance display
* Right panel: New student registration
* Top: Date and time
* Menu: Change password, contact, exit

## ✅ To Run the App

```bash
python main.py
```

## 📧 Contact

For any queries, please contact: `gamingkeybo@gmail.com`

---

## 📌 Notes

* Works best in well-lit environments.
* Press `q` to stop image capture or attendance recognition.
* Make sure your webcam is functional and accessible.

---

## 📜 License

MIT License

Copyright (c) 2025 [Mohd Uzair]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


