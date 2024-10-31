#sensors-processing ms

This ms has few activities triggered by the system:
1. a job that listens to Kafka and store the sensor's details in mongodb
2. a job that fetch hourly the sensor's temperature and deactivates malfunctioning sensors.
