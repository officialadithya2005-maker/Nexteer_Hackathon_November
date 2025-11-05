# Nexteer_Hackathon_November

---

## 🚗 IntelliPark – Intelligent Parking Solution

### **Concept Overview**

This project reimagines urban parking using **IoT + Computer Vision + Cloud integration**.
The system automatically **detects vehicles**, **reads license plates**, and **logs entry/exit data** in real time.
All data is synced to **Google Sheets** for cloud logging and displayed on a **local web dashboard**, enabling smarter parking management.

---

### **System Components**

1. **ESP32-CAM** – Captures vehicle images at the parking entrance/exit.
3. **Number Plate Recognition (OpenCV + API)** – Extracts and identifies the vehicle number.
4. **Google Sheets (Apps Script Integration)** – Stores timestamp, slot ID, and vehicle number.
5. **Local Web Dashboard** – Displays live parking data and analytics from Sheets (using Google Sheets API or Apps Script web app).

---

### **Data Flow**

```

       [ESP32-CAM Captures Image]
              ↓
 [OpenCV / API Performs Number Plate Detection]
              ↓
 [ESP32 Sends JSON Data → Google Apps Script]
              ↓
 [Apps Script Logs Entry in Google Sheets]
              ↓
 [Local Website Fetches Data from Google Sheets API]
              ↓
 [Dashboard Displays Real-Time Parking Slots + Logs]
```

---

### **Key Features**

* **Automated Number Plate Detection**
* **Live Slot Availability Visualization**
* **Cloud Logging via Google Sheets**
* **Real-Time Dashboard for Admin Monitoring**
* **Modular Design (Scalable to Multiple Slots)**

---

### **Future Enhancements**

* Integration with **payment gateways** for seamless booking
* **Predictive slot availability** using past data
* **Dynamic pricing** based on congestion
* **Mobile app** interface for pre-booking

---

