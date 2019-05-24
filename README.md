#lc-mosquitto

A LiveCode Builder wrapper around libmosquitto. This project was created for the LiveCode Builder Foreign Function Interface Workshop at the LiveCode 2019 conference in San Jose, California. 

## Mosquitto Information

https://mosquitto.org

API docs: https://mosquitto.org/api/files/mosquitto-h.html

## Testing

To test this project in LiveCode:

1. Open the Extension Builder from the Tools menu.
2. Load the mosquitto.lcb file and load it into the IDE. This article shows where the button is for testing an LCB file: http://lessons.livecode.com/m/4071/l/1035188-how-to-use-the-extension-builder
3. Open the mostquitto_test.livecode stack in the IDE.
4. Click the **Check libMosquitto Version** button to verify that the mosquitto extension has been properly loaded.
5. Click **Initialize**
6. Click **Connect**
7. Click **Subscribe**
8. Enter a message in the field next to the **Publish** button and then click **Publish**. You should see the message appear in the field to the right.
9. Get a friend to do the same thing and you can send messages to each other.
10. When you are done click the **Cleanup** button. LiveCode will crash if you quit without cleaning up after the mosquitto extension.
