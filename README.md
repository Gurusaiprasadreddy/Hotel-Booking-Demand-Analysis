# 🏨 Hotel Booking Demand Analysis & Business Insights Dashboard

## 📌 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on hotel booking demand data from City Hotels and Resort Hotels. The objective is to uncover booking patterns, guest behavior, pricing trends, seasonality, market segment performance, and cancellation drivers to support data-driven decision-making in the hospitality industry.

---

## 🎯 Objectives

* Analyze hotel booking demand and guest behavior.
* Identify pricing trends using Average Daily Rate (ADR).
* Understand seasonal demand fluctuations.
* Explore guest preferences and market segments.
* Investigate cancellation patterns and their business impact.
* Generate actionable insights for hotel revenue optimization.

---

## 📊 Dataset

**Dataset:** Hotel Booking Demand Dataset

The dataset contains booking information such as:

* Hotel Type (City Hotel / Resort Hotel)
* Guest Country
* Arrival Date and Month
* Average Daily Rate (ADR)
* Room Type
* Meal Preferences
* Market Segments
* Special Requests
* Length of Stay
* Booking Cancellations

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

---

## 🧹 Data Preparation

The following preprocessing steps were performed:

* Handled missing values
* Removed duplicate records
* Created derived features:

  * `total_nights`
  * `total_guests`
* Built a separate non-cancelled bookings dataset for focused analysis

---

## 📈 Exploratory Data Analysis

The project includes:

### Guest Analysis

* Top guest countries
* Geographic distribution of guests

### Pricing Analysis

* ADR comparison between hotel types
* ADR trends across room types
* Monthly ADR trends

### Guest Preferences

* Meal preference analysis
* Special requests analysis

### Booking Trends

* Monthly booking volume
* Seasonal demand patterns
* Length of stay analysis

### Market Segment Analysis

* Booking distribution by market segment

### Cancellation Analysis

* Overall cancellation rate
* Cancellation by hotel type
* Monthly cancellation trends

---

## 🔍 Key Insights

* Portugal generated the highest number of hotel guests.
* City Hotels achieved higher average ADR than Resort Hotels.
* Resort Hotel ADR peaked significantly during July and August.
* Online Travel Agencies (OTA) contributed the highest booking volume.
* Guests with more special requests showed lower cancellation tendencies.
* August recorded the highest cancellation volume.
* Resort Hotel guests generally stayed longer than City Hotel guests.

---

## 📁 Project Structure

```text
Hotel-Booking-Demand-Analysis/
│
├── Hotel_Booking_EDA.ipynb
├── hotel_bookings.csv
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone <repository-link>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run

Open:

```text
Hotel_Booking_EDA.ipynb
```

and execute all cells.

---

## 🚀 Future Enhancements

* Hotel booking cancellation prediction using Machine Learning
* Demand forecasting for occupancy planning
* Interactive dashboard using Power BI or Streamlit
* Customer segmentation using clustering techniques

---

## 👨‍💻 Author

**Guru Sai Prasad Reddy**

B.Tech – Computer Science and Engineering

Amrita Vishwa Vidyapeetham

2023 – 2027
