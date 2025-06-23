# MQTT-chat-box
A real-time group chat web application built using MQTT protocol for message exchange. This app mimics the behavior of popular group messaging apps like WhatsApp by allowing multiple users to join a public chat room and exchange messages in real-time.

 Features
Real-time messaging using MQTT protocol

Multiple users can join via a public URL

Messages instantly appear for all participants

 Supports group chat style interface

 Works with public MQTT brokers or MQTT.Cool

Tech Stack 

Frontend: HTML, CSS, JavaScript (Vanilla or React)

Messaging Protocol: MQTT

Broker: MQTT.Cool / HiveMQ / Mosquitto (public broker)

Hosting: Netlify / GitHub Pages / Vercel


How It Works
When a user joins, they subscribe to a topic (e.g., chat/global).

Messages sent are published to the same topic.

All subscribed clients receive the published messages instantly.

Uses unique client IDs to differentiate users.

