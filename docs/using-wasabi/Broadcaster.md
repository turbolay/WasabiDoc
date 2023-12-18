---
{
  "title": "Broadcaster",
  "description": "Wasabi has a feature called the Broadcaster than can be use to broadcast a transaction hex to the network."
}
---

### Introuction

The Broadcaster is an advanced feature that takes a transaction hex then broadcasts it to the Bitcoin Network. It's useful in many scenarios, but principally sending transactions signed on hardware wallet or to add a mempool transaction missing from the client.

### Open the Broadcaster

This feature is only accessible through the Search Bar. Please open it, search `Broadcaster` and click on the line.

![Open the Broadcaster](/OpenBroadcaster.png "Open the Broadcaster")

### Use the Broadcaster to add a mempool transaction

This workflow is useful in the case that you think a pending transaction is missing from the client and you want to add it.

- Copy the hex of the missing transaction. You can find the hex in a block explorer like [mempool.space](https://mempool.space/).
- Open the Broadcaster
- Choose "Paste from clipboard" option.
- Re-broadcast the transaction.

### Use the Broadcaster to send a transaction from a hardware wallet

See the [dedicated section](/using-wasabi/ColdWasabi.md#sending-bitcoin)