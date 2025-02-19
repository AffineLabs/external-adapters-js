# @chainlink/ea-bootstrap

## 1.3.5

### Patch Changes

- Add additional logs for Redis

## 1.3.4

### Patch Changes

- 790b2fa4: Add Coinpaprika KNC override

## 1.3.3

### Patch Changes

- 946b778c: Increase default local cache MAX_ITEMS to 1000

## 1.3.2

### Patch Changes

- a212f2cb2: WS bug fixes
- Only set Redis URL when defined as an env var

## 1.3.1

### Patch Changes

- 9e3e1cbb6: Provide fixed feed_id for cache warmer requests
- a3b352bb5: Fix rate limit capacity parsing
- 97bbbfc69: This PR fixes an issue with the cache warmer metrics that was causing them to go into the negatives

## 1.3.0

### Minor Changes

- c93e5654: Add new input parameter configuration in Validator class
- ccff5d7f: Upgrade Redis to V4

### Patch Changes

- b78f8e06: Print out actual used port when bootstrapping server

## 1.2.1

### Patch Changes

- WS deserializer now only returns string if the payload is not JSON

## 1.2.0

### Minor Changes

- 9de168b08: Disable per minute and per second rate limits through env vars

## 1.1.0

### Minor Changes

- e96b85614: Validate empty string required request parameters
- f10887669: Ignore empty string environment variables

### Patch Changes

- 6cddc7e33: send shutdown signal to cache warmer
- 757539a82: Added "WTI" preset for Tiingo
- 4ad7ac890: WS deserializer for string type

## 1.0.2

### Patch Changes

- ** DUMMY VERSION BUMP - Test release pipeline **

## 1.0.1

### Patch Changes

- Add FIL preset for Coingecko

## 1.0.0

### Major Changes

- EAv2 Release. Start of individual EA versioning.
