# Other-Configs
Other random configs that aren't in ESPHome - Home Assistant, Genmon, etc

# Genmon-MQTT YAML
You can copy and paste the config directly to your configuration.yaml, or you can copy the file itself next to the configuration.yaml and add
```
homeassistant:
  packages:
    genmon_mqtt: !include genmon_mqtt.yaml
```
to your configuration.yaml
