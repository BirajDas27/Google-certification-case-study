# 🚲 Cyclistic Bike-Share Analysis (Case Study)

## 📌 Project Overview
This case study analyzes how **casual riders** and **annual members** use Cyclistic’s bike-share service differently.  
The goal is to uncover **behavioral patterns** that can help design marketing strategies to convert casual riders into annual members.

This project follows the complete **data analysis lifecycle**:
**Ask → Prepare → Process → Analyze → Share → Act**

---

## 🎯 Business Objective
To identify key differences in **ride duration** and **usage frequency** between casual riders and annual members using historical bike-share data.

Key stakeholders:  
▫️Lily Moreno (Director of Marketing)  
▫️Cyclistic Marketing Analytics Team  
▫️Cyclistic Executive Team  

---

## 🛠 Tools Used  
 📊 **Microsoft Excel**  
 🔄 Data Cleaning & Transformation  
 📐 Time-based Calculations  
 📈 Pivot Tables & Charts  
 🧠 Exploratory Data Analysis  

---

## 📂 Dataset  
🔹 Public **Divvy bike-share trip data**  
🔹 Cyclistic is a **fictional company** used for this case study  
🔹 Data spans **multiple months** and includes millions of ride records  
🔹 Personally identifiable information (PII) is excluded  
🔹 ROCCC verified:
    ✅ Reliable → Official provider  
    ✅ Original → First-party data  
    ✅ Comprehensive → Covers multiple months  
    ✅ Current → Recent operational data  
    ✅ Cited → License acknowledged  

---

## 🧪 Step 1: Raw Data
The raw dataset contains individual trip-level records with ride details such as start time, end time, rider type, and station information.

📸 **Raw Data Snapshot**
![ss](raw_data.png)

---

## 🧹 Step 2: Data Processing
Key processing steps performed:
- Merged 13(11-2024 to 11-2025) monthly datasets
- Created `ride_length` and converted it into a **time-based format**
- Added `day_of_week` for behavioral analysis (1 => Sunday, 7 => Saturday)
- Validated critical fields and retained relevant records
- Removed rides with negative or zero duration
- Replaced blank values with `NA`
- Ensured member types are consistent (member, casual)


📸 **Processed Data Snapshot**
![ss](processed_data.png)

---

## 🔍 Step 3: Analysis & Exploration

### ⏱ Average Ride Length (Monthly Trend)
Casual riders consistently take **longer rides** compared to members across all months.

📸 **Average Ride Length by Month**
![ss](avg_ride_length.png)

---

### 📅 Ride Frequency by Day of Week
- **Members** ride more frequently on **weekdays** (commute behavior)
- **Casual riders** peak on **weekends** (leisure behavior)

📸 **Ride Frequency by Day of Week**
![ss](ride_len_DOW.png)

---

### 🔁 Ride Length vs Ride Frequency
This comparison highlights a clear contrast:
- Casual riders → **Fewer rides, longer duration**
- Members → **More rides, shorter duration**

📸 **Ride Length vs Frequency**
![ss](ride_len_vs_freq.png)

---

## 📊 Key Insights  
🔹 Casual riders take **~20 minutes per ride** on average  
🔹 Annual members average **~11–12 minutes per ride**  
🔹 Members ride **more frequently**, especially on weekdays  
🔹 Casual riders are more active during **weekends**  
🔹 Usage patterns suggest **leisure vs commute** behavior differences  

---

## 💡 Recommendations
1️⃣ Launch **weekend-focused membership promotions** targeting casual riders  
2️⃣ Highlight **cost savings** for frequent riders through annual plans  
3️⃣ Use **digital campaigns** (email/app notifications) during peak casual usage periods  
4️⃣ Offer **discounted annual plans** after repeated long-duration rides

---

## 📌 Conclusion
This analysis clearly demonstrates distinct usage behaviors between casual riders and annual members.  
By leveraging these insights, Cyclistic can design **data-driven marketing strategies** to increase annual memberships and drive long-term growth.

---

## 📎 Project Structure
