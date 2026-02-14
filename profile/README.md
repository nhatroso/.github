# PROJECT NHATROSO PLATFORM
**Intelligent Rental Management System with Integrated Utility Meter OCR**

---

## 1. Introduction
**NHATROSO PLATFORM** is a modern software solution designed to streamline rental property management. By integrating advanced **OCR (Optical Character Recognition)** technology, the system automates the recording of electricity and water consumption directly from meter images.

Originally developed at **Nha Trang University**, this project addresses critical challenges in property management:
*   Eliminating manual data entry errors.
*   Ensuring transparency between landlords and tenants.
*   Centralizing scattered management data.
*   Automating billing and payment workflows.

The system aims to deliver **Automation – Transparency – Professionalism** in rental operations.

---

## 2. Project Objectives

### 2.1 Technical Goals
*   Build a scalable and maintainable **Microservices Architecture**.
*   Develop a **Machine Learning OCR Model** for accurate utility meter reading.
*   Design a **User-Friendly UI/UX** with responsive web and mobile interfaces.
*   Implement robust **Authentication, Authorization, and Data Security**.

### 2.2 Product Goals
*   Comprehensive management of rooms, contracts, and tenants.
*   **Automated Utility Metering** via image capture.
*   Electronic invoicing and QR code payments.
*   Dynamic dashboards for revenue tracking and occupancy analytics.

---

## 3. Key Innovations
Unlike traditional management software, Nhatroso Platform offers unique advantages:
*   **No Hardware Upgrades Required**: Works with existing mechanical meters; no need for expensive IoT devices.
*   **AI-Powered Automation**: Leverages AI to extract data from photos.
*   **Mobile-First Data Collection**: Transforms any smartphone into an automated data collection tool.
*   **Cost-Effective**: High automation at a fraction of the deployment cost.

---

## 4. Technology Stack

### 4.1 Backend
*   **Node.js (NestJS)** – Core business logic and microservices.
*   **Python (FastAPI/Flask)** – Dedicated OCR service.
*   **PostgreSQL** – Relational database management.
*   **Redis** – Caching and message queuing.
*   **RabbitMQ/Kafka** – Asynchronous event processing.

### 4.2 Frontend
*   **ReactJS / Next.js** – Web Administration Portal.
*   **Tailwind CSS** – Responsive styling framework.
*   **Redux Toolkit / Zustand** – State management.
*   **PWA / React Native** – Mobile experience for tenants.

### 4.3 DevOps & Infrastructure
*   **Docker & Docker Compose** – Containerization.
*   **Nginx** – Reverse proxy, SSL termination, and load balancing.
*   **GitHub Actions** – CI/CD pipelines.

---

## 5. System Architecture

### 5.1 Microservices Model

**Client Layer**
*   Web Admin Dashboard
*   Tenant Mobile App/PWA

**API Gateway**
*   Nginx routing and request management

**Service Layer**
*   Auth Service (JWT Management)
*   Core Business Service (Operations)
*   OCR Service (AI Image Processing)

**Data Layer**
*   Dedicated databases per service context

---

## 6. OCR Pipeline
The image processing pipeline ensures high accuracy:
1.  **Preprocessing**: Cropping, deskewing, grayscale conversion, and noise reduction.
2.  **Text Detection**: Locating digit regions (CRAFT/YOLO).
3.  **Text Recognition**: Decoding characters (CRNN/Tesseract with fine-tuning).
4.  **Validation**: Logic checks against historical data to flag anomalies.

**Result**: High precision with automated error control.

---

## 7. Role-Based Features

### 7.1 Landlord (Owner)
*   Manage property listings, service pricing, and room status.
*   Oversee tenant information and digital contracts.
*   **Automated Billing**: Snap a photo → OCR processing → Auto-calculate bill.
*   Issue electronic invoices and track payment status.
*   View real-time revenue and occupancy reports.

### 7.2 Tenant
*   Transparent billing with **proof-of-reading images**.
*   Quick QR code payments.
*   Access transaction history.
*   Submit maintenance requests and feedback.

---

## 8. Implementation Roadmap (4 Months)
1.  **Analysis & Design**: Requirement gathering and system architecture.
2.  **Development & AI Training**: Core system build and OCR model training.
3.  **Integration & Testing**: System integration and rigorous testing.
4.  **Finalization**: Documentation, reporting, and project defense.

---

## 9. Risks & Future Development

### Potential Risks
*   **Image Quality**: Poor lighting or blur affecting OCR accuracy.
*   **Latency**: Potential delays in AI processing for high-load scenarios.

### Future Enhancements
*   Expand the dataset for broader meter compatibility.
*   **IoT Integration**: Support for autonomous camera modules.
*   **Advanced Analytics**: Anomaly detection for utility consumption patterns.

---

## 10. Conclusion
**PROJECT NHATROSO PLATFORM** bridges the gap between traditional property management and modern AI capability. By digitizing utility monitoring without expensive hardware, it offers a practical, scalable solution for the rental market.

Beyond academic objectives, the platform demonstrates significant **commercial potential**, driving **digital transformation in the rental housing sector**.

---
For detailed documentation and progress, visit the official workspace:
👉 [Project Notion Workspace](https://nhatroso.notion.site/PROJECT-NHATROSO-PLATFORM-e65f0f42c29746adbd3436006753fc3c)
