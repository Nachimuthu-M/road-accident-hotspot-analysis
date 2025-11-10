🚦 Road Accident Hotspot Analysis

A data-driven project to identify road accident hotspots using clustering (DBSCAN), visualize accident density via heatmaps, and analyze accident trends over time using Python.

📌 Features

✅ Data cleaning and preprocessing
✅ Hotspot detection using DBSCAN clustering
✅ Interactive Folium heatmap with hotspot markers
✅ Accident trend analysis by hour, day, month
✅ Severity distribution visualization
✅ Easy to run and customize

🛠️ Technologies Used
Library	Purpose
Pandas	Data processing
NumPy	Numerical computation
Scikit-Learn	DBSCAN clustering & scaling
Folium	Map visualization & heatmap
Matplotlib	Statistical charts
📂 Project Structure
Road-Accident-Hotspot-Analysis/
│── accidents.csv          # Dataset
│── main.py               # Python analysis script
│── hotspot_map.html      # Generated heatmap output
│── README.md             # Project documentation

📊 Output Preview

Hotspot map saved as: hotspot_map.html

Charts displayed:

Accidents by Hour

Accidents by Day

Severity Distribution

Monthly Accident Trend

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/Road-Accident-Hotspot-Analysis.git
cd Road-Accident-Hotspot-Analysis

2️⃣ Install dependencies
pip install pandas numpy scikit-learn folium matplotlib

3️⃣ Run the script
python main.py

4️⃣ Open the generated map
hotspot_map.html

🧠 Methodology

Load accident data

Clean invalid/missing records

Apply DBSCAN clustering to detect hotspots

Generate heatmap + hotspot markers

Analyze temporal accident patterns

📎 Dataset Requirements

The accidents.csv file must contain at minimum:

Column	Required
latitude	✅
longitude	✅
timestamp	✅
severity	✅ (for pie chart)

Example format:

latitude,longitude,timestamp,severity
11.0168,76.9558,2024-02-12 18:30:00,High

👨‍💻 Author

Your Name

📧 Contact: youremail@example.com

🔗 GitHub: https://github.com/your-username

⭐ If you found this useful

Please give this repository a ⭐ star and share! 😊

🏁 Output Snippet
Data Loaded: (1200, 6)
Cleaned Data: (1180, 6)
Total Hotspot Clusters Found: 5
✅ Heatmap saved as hotspot_map.html
✅ Analysis Completed Successfully
