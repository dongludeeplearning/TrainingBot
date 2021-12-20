Our group complete two parts:

TrainingBot-Part1 completed by Lu Dong 

open terminal and run the following command;
source evn/bin/activate
python3 app.py
open local http://127.0.0.1:5000


TrainingBot-Part2 completed by 
Adhesh Garg and Aparna Ananthakrishnan

Firstly you can train the custom model state with the dialogues in Data.txt file by the ipy notebook that is given. The notebook has all the steps for training and testing the model.

In order to deploy the model on a server unzip parlay.zip given and run the two commands 
1. python3 parlai/chat_service/services/browser_chat/run.py --config-path parlai/chat_service/tasks/chatbot/config.yml --port 10001
2. python3 parlai/chat_service/services/browser_chat/client.py --port 10001

One server and one client

Deploy on EC2.
Open link http://0.0.0.0:8080

