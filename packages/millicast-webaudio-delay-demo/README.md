# Millicast WebAudio Delay demo

## Setup
Add a `.env` file in current path. You can find the following example in `.env.sample`:
```sh
# Make a .env file with the following vars
MILLICAST_STREAM_NAME=yourStreamName
MILLICAST_ACCOUNT_ID=yourAccountId
```

Install all dependencies using:
```sh
npm ci
```

## Run
To start running this demo, the following command will publish the app at `http://localhost:10003` and enter in watching mode.
```sh
npm start
```
