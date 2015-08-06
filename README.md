# Igarape Android Test
This is a code base for one of the question of the Development Test at Igarapé Institute.

If you are a candidate, just fork this project with your Github account, create the solution and send us the link in the form.

We used <a href="https://developer.android.com/sdk/index.html">Android Studio</a> to generate this project.

Good luck!

# Testing

The test requires that you are using emulating device

1. Click on Run and connect to an Android emulator
2. Open a terminal and connect to the phone via telnet

<pre>
$ telnet localhost 5554
Trying 127.0.0.1...
Connected to localhost.
Escape character is '^]'.
Android Console: type 'help' for a list of commands
OK
geo fix -82.411629 28.054553
OK
Connection closed by foreign host.
</pre>

You should see latitude and longitude on phone screen.