# Smart-Irrigation-System
The Smart Irrigation System is an automated watering system designed to efficiently manage water usage in agricultural fields or gardens by using environmental data. The goal of this project is to reduce water wastage, increase crop yield, and minimize human effort through the use of sensors and microcontrollers.
# 📦 Components Required
- Arduino UNO

- Soil Moisture Sensor (FC-28)

- Relay Module (5V, 1 Channel)

- 9V Battery with clip

- DC Water Pump / DC Motor

- Jumper Wires

- Breadboard (optional)

- USB Cable (for programming Arduino)

# ⚙️ Working Principle
The soil moisture sensor detects the water content in the soil and sends an analog signal to the Arduino.

The Arduino continuously reads the sensor values and checks if the soil moisture falls below a predefined threshold.

If the soil is dry, the Arduino sends a HIGH signal to the relay module, which activates the DC pump.

The pump waters the plants for a specific time or until the moisture reaches the desired level.

If the soil is wet, the pump remains off, saving water and energy.


# 🌟 Features
💧 **Automatic Watering**: Waters plants when soil is dry without manual intervention.

🌱 **Efficient Water Usage**: Prevents overwatering and conserves water.

🔌 **Relay-Controlled Motor**: Allows high-current pump operation via Arduino.

📊 **Real-time Monitoring**: Reads real-time data from the soil sensor.

🧠 **Customizable Thresholds**: Thresholds for dryness can be easily adjusted in the Arduino code.

🔋 **Battery Operated Pump**: Uses external 9V power supply for motor/pump to isolate load from Arduino.

# ✅ Results

- System successfully detects soil moisture and automatically activates the pump when soil is dry.

- Provides consistent and timely watering based on soil needs.

- Demonstrated reduction in manual labor and optimized water usage in tests.

- Works reliably under varying soil conditions and sensor calibration.

