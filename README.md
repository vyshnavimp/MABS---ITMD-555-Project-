# 🩺 MABS: Medical Appointment Booking System

## 🧾 Abstract
MABS is a streamlined mobile application designed to simplify scheduling medical appointments. Users can select a doctor, pick an available date and time slot, and enter their personal details to book appointments easily. The system tracks upcoming visits and sends reminders to help users stay on top of their healthcare schedules. Built with Firebase backend services and integrated with Google APIs, MABS aims to improve access and management of medical appointments efficiently.

---

## 🚀 Key Features

- 📱 **User Interface**: Intuitive sign-in, sign-up, splash, and home screens for easy navigation  
- 📅 **Appointment Scheduling**: Select doctors, choose dates and preset time slots  
- 🔔 **Reminders**: Automated notifications for upcoming appointments  
- 🔗 **Backend Services**:  
  - Firebase Authentication for secure login  
  - Firebase Realtime Database and Storage for data management  
  - Google Calendar API integration for syncing appointments  
  - Google Maps API for location services  
- 🏥 **Additional Modules**:  
  - Quick Care services  
  - Inpatient room reservation  
  - Service classification and management

---

## 🛠️ Methodology

### 1. User Authentication
- Firebase Authentication used to manage user sign-in and sign-up securely.

### 2. Appointment Management
- Users select doctors and book appointments by choosing from available slots.
- Appointment data is stored and synced using Firebase Realtime Database.
- Reminders are pushed to users for upcoming visits.

### 3. Integration with Google APIs
- Google Calendar API to sync appointments with user calendars.
- Google Maps API to provide location details for clinics and hospitals.

### 4. UI Design
- Android activities created for seamless navigation including splash screen, home screen, appointment reminders, services, and inpatient room reservation.

---

## 📈 Results

| Feature                  | Description                                    |
|--------------------------|------------------------------------------------|
| Appointment Booking      | Simplifies doctor visit scheduling             |
| Reminder Notifications   | Helps reduce missed appointments                |
| Firebase Backend         | Ensures real-time data sync and secure auth    |
| Google API Integration   | Enhances calendar syncing and location services|

---

## 💻 Deployment

- Built as an Android application using Java and Firebase services.
- Firebase project configured for Authentication, Database, and Storage.
- Google APIs enabled and integrated.
- APK can be installed on Android devices (requires Firebase credentials setup).

---

## 👨‍💻 Authors

- **Padmavathi Vyshnavi Madarampalli** – UI design, backend integration  
- **Venkata Sai Gunisetty** – API integration, Firebase configuration  
- **Manideep Satya Posina** – Android app development, testing  

Master’s in Information Technology and Management – ILLINOIS INSTITUTE OF TECHNOLOGY

---

## 📚 References

1. Firebase Documentation – [https://firebase.google.com/docs](https://firebase.google.com/docs)  
2. Google Calendar API – [https://developers.google.com/calendar](https://developers.google.com/calendar)  
3. Google Maps API – [https://developers.google.com/maps](https://developers.google.com/maps)  
4. Android Developer Guide – [https://developer.android.com/guide](https://developer.android.com/guide)

---

## 🔮 Future Work

- Map profile activity and improve user personalization.  
- Add detailed service classification and display features.  
- Implement in-app chat and telemedicine options.  
- Enhance UI with additional polish and responsiveness.  

---

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.
