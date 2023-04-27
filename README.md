## ArsonV1

Arson should be able to do the following things :

1. Chat and greet through messages
2. Should be connected with a data base
3. Able to listen and understand
4. Able to both speak to me or chat, based on my command
5. Recognise me from others based on voice recognition(only respond to my commands)
6. Should be able to maintain my schedule/todo list
7. Send mails
8. Send messages
9. Make calls
10. Automate File System
11. Should be able to connect to my phone

assistant/
├── data/
│ ├── model/
│ ├── audio/
│ └── database/
├── modules/
│ ├── speech_recognition/
│ ├── natural_language_processing/
│ ├── task_automation/
│ ├── messaging/
│ ├── calling/
│ ├── scheduling/
│ ├── email/
│ └── voice_recognition/
├── config/
│ ├── config.yaml
│ └── credentials.json
├── logs/
│ ├── assistant.log
│ └── error.log
├── tests/
├── README.md
└── main.py
