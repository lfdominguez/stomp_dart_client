## 0.3.2
 - Added Ack/Nack methods (Thanks @justacid). Note: This does not yet work for 1.0 & 1.1
 - (Minor: Reformatted code according to dartanalyze)

## 0.3.1
 - Changed folder structure to please pana.

## 0.3.0
 - Replaced `IOWebSocketChannel` with `WebSocketChannel` to be platform agnostic. This means it now also should work for flutter_web.
 - Made tests hybrid tests so that they cover all types of platforms

## 0.2.3
 - Fixed `onConnect` being called on inactive StompClient

## 0.2.2
 - Reverted type change on `stompConnectHeaders` because it caused issues on connect

## 0.2.1
 - Fixed a scenario where quick connect/disconnects could cause an exception

## 0.2.0
 - Breaking Change: Renamed `connectHeaders` to `stompConnectHeaders`
 - Added `webSocketConnectHeaders` to `StompConfig` to be passed to the underyling WebSocket on connection

## 0.1.6
 - Fixed a bug where it would not try to reconnect when the WebSocket connection could not be established
 - Added a `connectionTimeout` property to the config, to allow control over when a connection attempt is aborted

## 0.1.5
 - More formatting

## 0.1.4
 - Renamed package
 - Added example
 - Incorperated format suggestions

## 0.1.3
 - Removed dependency on non-hosted package to be able to publish the package