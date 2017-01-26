# Credera Cup Example Python Client

An example client for the [Credera Cup](http://www.crederacup.com) written in Python.

Requires the [websocket-client](https://pypi.python.org/pypi/websocket-client/) library.

You must have a Credera Cup token before playing the game. Go to www.crederacup.com and sign up
for an account to receive a token.

There are two required parameters: URL for the websocket to connect to and your user token.

    python client.py wss://play.crederacup.com/season/I/practice <user-token>
