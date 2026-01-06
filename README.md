# Other-Configs
Here are some other random configs I've made that aren't in my ESPHome repo - stuff for Home Assistant, Genmon, etc.

# Genmon-MQTT YAML
You can either copy and paste the config directly into your configuration.yaml, or you can copy the entire file itself next to the configuration.yaml file and simply add
```
homeassistant:
  packages:
    genmon_mqtt: !include genmon_mqtt.yaml
```
to your configuration.yaml.
