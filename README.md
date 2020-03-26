## wamsg - WhatsApp Message

### Challenge
When we want to send WhatsApp msg to a number not in our contacts, we have to add to our contacts, then wait for WhatsApp refresh, search for contact and send message.

### Solution
wamsg simple CLI tool which takes number and msg as inputs on your command line, helps you to send out msg (optional) from your WhatsApp web or desktop app.



### Build it
go build wamsg.go

wamsg binary is built

### Send message
./wamsg 919012345678 hello

- opens WhatsApp web, either continue with WhatsApp web version or with prompted WhatsApp Desktop App