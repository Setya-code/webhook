# webhook

WebHook setup:
sudo apt update; sudo apt install webhooks

edit file /home/setya/webhooks/hooks-local.json
edit file /home/setya/webhooks/project-site/deploy.sh

run command:
/usr/bin/webhook -hooks /home/setya/webhooks/hooks-local.json -ip "localhost" --port 9010 -verbose &
