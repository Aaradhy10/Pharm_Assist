# **PharmAssist**  

#### Participant name: Aaradhy Jain
#### Project name : PharmAssist

## **Overview**
PharmAssist is a prototype designed to showcase how AI can revolutionize pharmacy workflows by automating prescription processing, inventory management, and order fulfillment.

## **Demo Pages**
#### 1. Landing page
![image](https://github.com/user-attachments/assets/b17cadbb-6250-4200-a820-913745cc69d5)
#### 2. Sales & Analytics Dashboard
![image](https://github.com/user-attachments/assets/e2323e74-7d35-4fdc-965b-ba1478cc4792)
#### 3. QR Generation to place order
![image](https://github.com/user-attachments/assets/d4b017e0-073e-4eac-bf9d-cc123ca1a634)

#### 4. Prescription upload page
![image](https://github.com/user-attachments/assets/78fc50f1-fd08-4d42-84d4-df52a07bc222)
#### 5. Order generation from prescription
![image](https://github.com/user-attachments/assets/7091f824-a6dc-4d2f-aa8d-417efd9ae459)

#### 6. Order management for pharmacist
![image](https://github.com/user-attachments/assets/acd5c047-00e3-437d-babe-e37bb404a3cd)
#### 7. Inventory management for pharmacist
![image](https://github.com/user-attachments/assets/bfa27fa1-bfda-4f3f-8475-9bad024b0bfd)


## **Problem Statement**  

Pharmacists handle a high volume of prescriptions daily, often dealing with handwritten notes, manual order processing, and inventory management challenges. These inefficiencies can lead to errors, delays, and stock mismanagement, impacting both pharmacists and patients. **PharmAssist** aims to automate these processes using AI and machine learning, ensuring accuracy, efficiency, and seamless pharmacy operations.  

## **Solution**  

PharmAssist is an **AI-powered prescription management system** designed to simplify pharmacy workflows:  

- **Optical Character Recognition (OCR)**: Leverages **EasyOCR and DeepSeek Vision R1** to accurately extract and validate text from handwritten prescriptions.  
- **QR-Based Ordering**: Patients can scan a **QR code, upload their prescription**, and place orders directly from their phones.  
- **Automated Inventory & Order Management**: Tracks stock levels, streamlines order fulfillment, and prevents shortages or overstocking.  
- **Pharmacist Dashboard**: Provides real-time insights into **sales, stock levels, and revenue analytics** for better decision-making.

   ![image](https://github.com/user-attachments/assets/9912f679-f72a-4b01-8fb4-5a8064ead5fc)


## **Technologies Used**  

- **AI & OCR**: EasyOCR, DeepSeek Vision R1 for handwriting recognition.  
- **Backend**: Node.js, Express.js for API development.  
- **Frontend**: React.js for an interactive and user-friendly interface.  
- **Database**: MongoDB for efficient data storage and retrieval.  
- **Deployment**: Hosted on **AWS**, with secure API tunneling via **Ngrok** for remote accessibility.  
- **Security**: Encrypted prescription data, authentication mechanisms, and compliance with industry standards.  

By automating **prescription processing, inventory tracking, and revenue management**, **PharmAssist enhances efficiency, reduces errors, and improves pharmacy operations**, ultimately benefiting both pharmacists and patients.  

## Requirements

### Frontend
- Node.js (v14 or higher)
- npm (v6 or higher)

### Backend
- Python 3.8 or higher
- Flask

## Getting Started- How to run this project on your local machine

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The frontend will be available at `http://localhost:5173` (or the port shown in your terminal).

### Backend Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On Windows:
  ```bash
  .\venv\Scripts\activate
  ```
- On macOS/Linux: 
  ```bash
  source venv/bin/activate
  ```

3. Install Python dependencies:
```bash
pip install flask
```

4. Start the Flask server:
```bash
python app.py
```

The backend will be available at `http://localhost:5000`.

## Development

- Frontend code is in the `frontend/` directory
- Backend Flask application is in `app.py`
- Make sure both frontend and backend servers are running for full functionality

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

 
