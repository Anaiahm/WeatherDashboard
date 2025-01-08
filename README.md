# <div align="center" id="logo"> ![WeatherDashboardLogo](https://imgur.com/JicH1Ow.png) </div>

## <div align="center"> A weather data collection system using AWS S3 and OpenWeather API </div>


## ℹ️ Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API)
- Cloud Storage (AWS S3)
- Infrastructure as Code
- Version Control (Git)
- Python Development
- Error Handling
- Environment Management

## ⚡ Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple cities tracking
- Timestamps all data for historical tracking

## 🖥️ Technologies Used
- **Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **External API:** OpenWeather API
- **Dependencies:** 
  - boto3 (AWS SDK)
  - python-dotenv
  - requests


## 🌱 Project Structure
![ProjectStructure](https://imgur.com/bi8w2Vo.png)

## 🚀 Get Started
Want to recreate this project? Instructions are below! <br>

1. Clone the repository:
--bash
git clone https://github.com/Anaiahm/WeatherDashboard.git

2. Install dependencies:
bashCopypip install -r requirements.txt

3. Configure environment variables (.env):
CopyOPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

4. Configure AWS credentials:
bashCopyaws configure

5. Run the application:
python src/weather_dashboard.py

## 🔧 What you will Learn

- AWS S3 bucket creation and management 
- Environment variable management for secure API keys 
- Python best practices for API integration 
- Git workflow for project development 
- Error handling in distributed systems 
- Cloud resource management 

## 🔮 Future Plans

- Add weather forecasting 
- Implement data visualization 
- Add more cities 
- Create automated testing 
- Set up CI/CD pipeline 