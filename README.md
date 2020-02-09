# express-rate-gateway-polli-headers

An example repo with express-gateway plus express-rate-limit plugin for new rate limit headers conforming to the [rate limit standardization proposal](https://tools.ietf.org/id/draft-polli-ratelimit-headers-01.html).

## Step 1
Install the dependacies.

`npm install`

## Step 2
Start express-gateway server.

` npm start`

## Step 3
You will get your IP as response with the new headers.

` curl http://localhost:8080/ip`
