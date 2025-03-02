# **Helmet-Numberplate-Speed Detection System**

## **Overview**
The **Helmet-Numberplate-Speed Detection System** is an advanced AI-powered solution designed to improve road safety and assist law enforcement. It detects helmet usage, recognizes vehicle number plates, and measures vehicle speed using state-of-the-art deep learning models. The system integrates object detection (YOLOv7, YOLOv8, and YOLOv9), tracking (Deepsort algorithm), and Optical Character Recognition (Tesseract OCR). The frontend is built using HTML and CSS, while Django serves as the backend framework.

## **Features**
- **Helmet Detection**: Identifies whether motorcyclists are wearing helmets using YOLO-based models.
- **Number Plate Recognition**: Uses Tesseract OCR to extract and interpret vehicle number plate details.
- **Speed Measurement**: Employs the Deepsort algorithm to track vehicle movement and calculate speed.
- **User-Friendly Interface**: HTML and CSS power the frontend for easy navigation and interaction.
- **Scalable Backend**: Django ensures smooth server-side processing and database management.

## **Performance Metrics**
- **YOLOv7 Model Performance:**
  - **Precision**: 87%
  - **Recall**: 90.1%
  - **mAP@50**: 90.4%

These metrics indicate high reliability in detecting helmets, identifying number plates, and tracking vehicle speed.

## **Technology Stack**
- **Deep Learning Models**: YOLOv7, YOLOv8, YOLOv9 (for helmet and number plate detection)
- **Tracking Algorithm**: Deepsort (for speed estimation)
- **OCR**: Tesseract OCR (for number plate recognition)
- **Backend**: Django (for processing and database management)
- **Frontend**: HTML, CSS (for user interface design)

## **Use Cases**
- **Traffic Law Enforcement**: Automatically detects helmet violations, identifies vehicle number plates, and tracks speeding vehicles.
- **Road Safety Compliance**: Helps in enforcing helmet usage and speed limits to ensure safe driving.
- **Smart Surveillance**: Integrates into smart city infrastructure for real-time traffic monitoring and automated law enforcement.

## **Installation & Setup**
### **Prerequisites**
Ensure you have the following installed on your system:
- Python 3.x
- Django
- OpenCV
- Tesseract OCR
- YOLOv7, YOLOv8, YOLOv9 models
- Deepsort tracking algorithm

### **Installation Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/helmet-numberplate-speed-detection.git
   cd helmet-numberplate-speed-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Django migrations:
   ```bash
   python manage.py migrate
   ```
4. Start the Django server:
   ```bash
   python manage.py runserver
   ```
5. Access the web application in your browser at:
   ```
   http://127.0.0.1:8000/
   ```

## **Usage Instructions**
1. Upload or stream live video footage.
2. The system will detect helmet usage, recognize number plates, and measure vehicle speed.
3. Violations (e.g., no helmet or overspeeding) will be logged and displayed on the dashboard.
4. Users can generate reports based on recorded violations.

## **Contributing**
We welcome contributions! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m "Added new feature"`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request.


## **Contact**
For queries or support, feel free to contact us at [misra.abhishek1238@gmail.com](mailto:misra.abhishek1238@gmail.com).
