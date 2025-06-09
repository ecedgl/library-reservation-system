Library Reservation System – CMPE331 Group Project

This is a full-stack web application developed for the CMPE331 Software Engineering course at Istanbul Bilgi University. Our team's goal was to build a university library reservation platform where students can book time slots at specific libraries, with built-in validation and conflict handling.

> This was a group project developed by;  
> Ece Doğa Gül, Cem Akçiçek, Berkay Özdelice, Muhammed Ali Akdoğan, and Emirhan İnan.

---

## Tech Stack

- **Frontend**: HTML, Bootstrap 5, Font Awesome
- **Backend**: Python Flask
- **Data Handling**: JSON file for storage
- **Deployment**: ngrok for temporary public links
- **Tools**: Google Colab / VS Code

---

## Features

- Users can:
  - View all reservations
  - Make new reservations
  - Delete existing ones
- Input validation:
  - Only allows `@edu.tr` or `@edunet` emails
  - Prevents past-date bookings
  - Avoids time conflicts at the same library
- Flash messages show errors or success feedback
- Clean UI with responsive design

---

## How to Run the Project

### Run via Google Colab:
1. Upload `library_reservation_app.ipynb` to Google Colab
2. Run all cells
3. Click the **ngrok public link** printed in the output
4. Start making reservations 

Note: The link will expire when the Colab session ends — just rerun to get a new one.

---

## Project Files

| File | Description |
|------|-------------|
| `library_reservation_app.ipynb` | Flask app with full backend + embedded HTML |
| `Library_Reservation_Final_Report.pdf` | Final technical report with screenshots and UI description |
| `Library_Reservation_SRS.pdf` | Software Requirements Specification |
| `Library_Reservation_UML_Diagrams.pdf` | UML diagrams: use case, class, activity, sequence |

---

## UML Diagrams

The following diagrams are included in the UML PDF:
- Use Case Diagram
- Class Diagram
- Activity Diagram
- Sequence Diagram

---

## Notes

- This app does not require a database or separate frontend directory. Everything is self-contained in the notebook.
- Designed for educational purposes and rapid prototyping.
- Scalable to production-level architecture with Flask + PostgreSQL + Docker.

---

## Contributors

- Ece Doğa Gül 
- Cem Akçiçek 
- Berkay Özdelice 
- Muhammed Ali Akdoğan 
- Emirhan İnan

---

## License

For academic showcase purposes. Not for commercial use.