idf_component_register(SRCS "Adafruit_Sensor.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino-esp32 Adafruit_BusIO)

project(Adafruit_Sensor)