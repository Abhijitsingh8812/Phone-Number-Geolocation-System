# Phone-Number-Geolocation-System
This project, “Phone Number Geolocation System using NumVerify and OpenCage APIs”, is designed to fetch and display the geographical location of a mobile number. The system works in three steps: Validation, Location Extraction, Geocoding  

📱 Phone Number Geolocation System

A Python-based tool to fetch and display the approximate location of a mobile number using NumVerify and OpenCage APIs.

🚀 Features

Validate phone number (country, carrier, line type).

Fetch the registered location of the number.

Convert location into latitude & longitude.

Display all details in a clean output.

🛠️ Technologies Used

Python 3.x

Requests (API calls)

NumVerify API (phone number validation)

OpenCage Geocoding API (location → coordinates)

📂 Project Structure
phone-number-geolocation/
├── main.py          # Main Python script
├── requirements.txt # Required libraries
└── README.md        # Project documentation

⚡ Installation & Setup

Clone this repo

git clone https://github.com/your-username/phone-number-geolocation.git
cd phone-number-geolocation


Install dependencies

pip install -r requirements.txt


Run the script

python main.py

🔑 API Keys Setup

This project requires two API keys:

NumVerify API

OpenCage API

In main.py, replace the placeholders with your API keys:

numverify_key = "YOUR_NUMVERIFY_KEY"
opencage_key = "YOUR_OPENCAGE_KEY"

🖥️ Example Output
📱 Phone number entered: +919999951150
✅ Valid phone number
Carrier: Airtel
Country: India
📍 Location (from carrier info): Delhi
🌍 Coordinates: Latitude = 28.7041, Longitude = 77.1025

⚠️ Limitations

Provides approximate registered carrier location, not live GPS tracking.

Accuracy depends on the data provided by APIs.

🚀 Future Improvements

Add Google Maps visualization.

Build a simple web interface (Flask/Streamlit).

Support bulk lookups for analytics.

👨‍💻 Author

Developed by Abhijit Kumar as a Personal project.
