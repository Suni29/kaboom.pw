# Kaboom.pw (Modified)

## NGROK

Ngrok is included to host the server.

Get your auth-token [here](https://dashboard.ngrok.com/get-started/your-authtoken) and paste the following command in the terminal.
(Replace <auth-token> with your auth-token)

```
ngrok config add-authtoken <auth-token>
```

# Start

Execute this command in the terminal to start the minecraft server.

```
java -Xmx3G -jar server.jar
```

Open up a new terminal and execute the following command.

```
ngrok tcp 25565
```

Now copy the text starting with tcp:// (without tcp://) and use it as the server ip to connect to the server.