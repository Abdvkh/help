# BlockIOBot

�1�1�1�8�1�9 �1�9�1�8�1�9�1�2�1�0�1�2�1�2 �1�1�1�2 �1�2�1�4�1�9�1�4�1�0�1�4 �1�8�1�8�1�2�1�7�1�9�1�9�1�8 �1�9�1�7
 [Block.io](https://block.io). 

###�1�9�1�0�1�6�1�9 �1�5�1�4�1�4�1�9 �1�8�1�9�1�2 �1�9�1�8�1�3�1�8�1�1 [Lib](https://help.bots.business/libs/blockio)

### �1�9�1�7 Block.io �1�4�1�9�1�7�1�0�1�7:

 * �1�7�1�0�1�2�1�9�1�3 �1�9�1�5�1�9�1�5�1�6 �1�4�1�7�1�4�1�7�1�1: �1�0�1�4�1�2�1�7�1�2�1�4�1�0 �1�2 Dogecoin �1�2 Litecoin
 * �1�2�1�0�1�7�1�2 �1�9�1�8�1�9�1�7�1�9�1�9�1�8�1�9�1�2
 * �1�6�1�0�1�2�1�8 �1�9�1�8�1�9�1�7�1�5�1�2�1�7�1�9�1�2
 * �1�4�1�7�1�8�1�1�1�9 �1�2�1�0�1�1�1�5�1�0
 * �1�9�1�8�1�6

### �1�0�1�2�1�2 �1�9�1�8�1�6�1�2�1�9�1�8�1�9

�1�9�1�8�1�6�1�9�1�8�1�9�1�1 �1�9�1�8�1�9�1�8�1�4�1�1�1�4�1�1 start/ �1�5�1�4 �1�9�1�9�1�9:

![](../.gitbook/assets/image%20%2852%29.png)

�1�6�1�9�1�8�1�9�1�1 �1�7�1�0�1�9�1�2�1�4�1�0 �1�0�1�2�1�2 �1�5�1�4 �1�9�1�8�1�9�1�1�1�9 �1�9�1�8�1�9�1�1�1�2�1�7�1�9�1�9 "�1�7�1�0�1�9�1�2�1�4�1�0 �1�0�1�2�1�2":

![](../.gitbook/assets/image%20%2815%29.png)

  
�1�6�1�9�1�8�1�9�1�1 �1�9�1�8�1�1�1�5�1�0:

![](../.gitbook/assets/image%20%2848%29.png)

�1�6�1�9�1�8�1�9�1�1 �1�9�1�8�1�5�1�7�1�2�1�9�1�2:

![](../.gitbook/assets/image%20%2827%29.png)

### �1�7�1�4�1�5 �1�4�1�7�1�9�1�8�1�1

�1�4�1�1�1�2�1�6�1�7�1�9 �1�0�1�2�1�2 BlockIo lib. 

�1�9�1�9�1�0 �1�0�1�9�1�2�1�8�1�4�1�4 �1�8�1�8�1�6�1�4�1�9�1�7�1�1 �1�2�1�1�1�2
`/getXXX` :

```java
Libs.BlockIO.Bitcoin.getXXX(
    { onSuccess: "/onGetXXX", onError: "/onerror" }
);
```

`getXXX` - �1�9�1�0 �1�9�1�1�1�9�1�8�1�4�1�0 apk �1�5�1�9�1�0 [https://block.io/api/simple](https://block.io/api/simple/)

�1�5�1�4�1�4�1�9 �1�8�1�7�1�4�1�0�1�9 �1�5�1�2�1�9�1�9�1�9 `onSucc.ess` �1�2 `on.Error`.

All `onSuccess` �1�6�1�4�1�9�1�7�1�1 �1�8�1�1�1�9 �1�9�1�1�1�9`/onGetXXX`

�1�0�1�2�1�2 �1�8�1�7�1�4�1�1�1�9 �1�2�1�9�1�5�1�7 �1�5�1�6�1�5
`onError` command: `/onerror`:

```javascript
Bot.sendMessage("Error");

if(options&&options.data){
  // �1�5�1�4 �1�9�1�8�1�6�1�4�1�9�1�9�1�9�1�2 �1�8�1�7�1�4�1�0�1�9 �1�9�1�1�1�9�1�8�1�1 �1�6�1�5�1�5 �1�9�1�0 Block.io
  // �1�5�1�6�1�5 �1�9�1�9�1�1�1�8�1�1�1�9
  Bot.sendMessage(options.data.error_message);
}
```



#### �1�7�1�8�1�3 �1�1�1�0�1�4�1�8 �1�9�1�8�1�9�1�3�1�9�1�8 - �1�5�1�9�1�9 �1�8�1�8�1�2�1�5�1�6�1�6 �1�9�1�0 �1�3�1�5�1�1 �1�9�1�8�1�7�1�0�1�2�1�9�1�0

 �1�9�1�1�1�9 �1�9�1�8�1�5�1�9�1�9 �1�1�1�2:

```javascript
Libs.BlockIO.Bitcoin.isValidAddress(
  { onSuccess: "/onvalidate",
  onError: "/onerror",
  address: message }
);
```

�1�8�1�7�1�4�1�0�1�9 �1�5�1�4�1�4�1�5�1�9 �1�7�1�0�1�2�1�9�1�0 �1�5�1�4 �1�9�1�2�1�8�1�4�1�9�1�9�1�2 �1�9�1�8�1�9�1�1�1�9�1�8�1�1: �1�9�1�8�1�9�1�9�1�9 �1�8�1�1�1�9 �1�6�1�4�1�9�1�1 "�1�9�1�0�1�2�1�6�1�9 �1�9�1�8�1�7�1�4�1�9�1�0�1�1" �1�9�1�0 �1�9�1�8�1�9�1�1�1�2�1�6�1�7�1�9.

�1�9�1�8�1�9�1�9�1�9:
/onvalidate

�1�0�1�5�1�0 �1�5�1�6�1�5 �1�0�1�9�1�1�1�8 �1�9�1�8�1�9�1�7:

```javascript
// �1�8�1�7�1�4�1�0�1�9 �1�9�1�1�1�2�1�4�1�9�1�0�1�1 json �1�9�1�0 Block.io �1�5�1�4 �1�9�1�8�1�6�1�4�1�9�1�9�1�9�1�2 
Bot.sendMessage(inspect(options));
```



### �1�9�1�8�1�5�1�3�1�2�1�8 �1�7�1�8�1�3 �1�9�1�8�1�7�1�0�1�9�1�2�1�4�1�0

�1�5�1�9�1�9:
`/getMyAddresses`

```javascript
Libs.BlockIO.Bitcoin.getMyAddresses(
  { onSuccess: "/ongetmyadresses", onError: "/onerror" }
);
```

�1�5�1�9�1�9:
`"/onGetMyAdresses"`

```javascript
// �1�9�1�1�1�2�1�4�1�9�1�0�1�1 Block.io �1�5�1�4 �1�9�1�8�1�6�1�4�1�9�1�9�1�9�1�2
�1�2�1�9�1�1�1�9�1�5 �1�8�1�8�1�9�1�5�1�9�1�5�1�6 = �1�9�1�8�1�6�1�4�1�9�1�9�1�9�1�2 �1�7
Bot.sendMessage("Network: " + wallets.network);

let addresses = wallets.addresses;
let answer = "*�1�9�1�5�1�9�1�5�1�6�1�7:*\n"

let counter = 0;
// �1�8�1�7�1�4�1�0�1�9 �1�7�1�7�1�1 �1�7�1�0�1�9�1�2�1�4�1�0.
for(let ind in addresses){
  if(counter>10){ break } // no more then 10 addresses

  counter+=1;
  answer= answer + "#️⃣ `" +  addresses[ind].address + "`" +
      "\n  🏷️Label: `" + 
               addresses[ind].label.split("_").join("") + "`" +
      "\n  💰balance: `" + 
               addresses[ind].available_balance + "`" +
      "\n  ⏳pending received balance: " + 
               addresses[ind].pending_received_balance +
      "\n  ❌Archive: /archive" + 
               addresses[ind].label +
      "\n\n"
}

Bot.sendMessage(answer);
```

### �1�9�1�8�1�9�1�7�1�9�1�9�1�8�1�9�1�2.  �1�9�1�8�1�7�1�6�1�8 �1�2�1�9�1�8�1�9�1�7�1�9�1�9�1�8�1�9�1�2 �1�9�1�8�1�3�1�9�1�7�1�9�1�1

�1�8�1�8�1�9�1�7�1�9�1�9�1�8�1�9�1�2 �1�9�1�8�1�3�1�9�1�7�1�9�1�1:

```javascript
Libs.BlockIO.Bitcoin.getTransactions(
    { type: "sent",
     onSuccess: "/onGetOutTransactions", onError: "/onerror" }
);
```

�1�8�1�9�1�7�1�9�1�9�1�8�1�9�1�2 �1�9�1�8�1�7�1�6�1�8:

```javascript
Libs.BlockIO.Bitcoin.getTransactions(
    { type: "received",
     onSuccess: "/onGetTransactions", onError: "/onerror" }
);
```

`/onGetOutTransactions` and `/onGetTransactions` �1�9�1�8�1�5�1�9�1�9 - �1�9�1�2�1�9�1�0�1�1:

{% tabs %}
{% tab title="/onGetOutTransactions" %}
```javascript
let transactions = options;
let answer = "";

answer+= "Network: " + transactions.network;

function parseOutcoming(tx){
  let sended = tx.amounts_sent;
 
  if(!sended){ return "" }
  let result = ""
  for(let ind in sended){
    result+= "\n  📥recipient: `" + sended[ind].recipient + "`" +
             "\n  💰amount: `" + sended[ind].amount + "`";
  }
  if(result==""){ return "" }
  
  result+="\n  ▪senders: "
  for(let ind in tx.senders){
     result+= "`" + tx.senders[ind] + "` ";
  }
  
  return result;
}

let tx, time;
for(let ind in transactions.txs){
  tx = transactions.txs[ind];
  time = new Date(tx.time*1000);
  time = time.toLocaleString()
  
  answer+= "\n\nTXID:`" + tx.txid + "`";
  answer+= "\n  ⌚time: `" + time + "`";
  answer+= "\n  🔢confirmations: " + tx.confirmations;
  
  answer+= parseOutcoming(tx)
}

Bot.sendMessage(answer);



```
{% endtab %}

{% tab title="/onGetTransactions" %}
```javascript
let transactions = options;
let answer = "";

answer+= "Network: " + transactions.network;

function parseIncoming(tx){
  let received = tx.amounts_received;
 
  if(!received){ return "" }
  let result = ""
  for(let ind in received){
    result+= "\n  📥recipient: `" + received[ind].recipient + "`" +
             "\n  💰amount: `" + received[ind].amount + "`";
  }
  if(result==""){ return "" }
  
  result+="\n  ▪senders: "
  for(let ind in tx.senders){
     result+= "`" + tx.senders[ind] + "` ";
  }
  
  return result;
}

let tx, time;
for(let ind in transactions.txs){
  tx = transactions.txs[ind];
  time = new Date(tx.time*1000);
  time = time.toLocaleString()
  
  answer+= "\n\nTXID:`" + tx.txid + "`";
  answer+= "\n  ⌚time: `" + time + "`";
  answer+= "\n  🔢confirmations: " + tx.confirmations;
  
  answer+= parseIncoming(tx)
}

Bot.sendMessage(answer);



```
{% endtab %}
{% endtabs %}



### �1�9�1�8�1�5�1�9�1�9 �1�9�1�8�1�9�1�8�1�4�1�1�1�4 "*\" �1�8�1�7�1�4�1�9�1�9�1�3�1�9�1�2 �1�9�1�8�1�7�1�0�1�2�1�9�1�0
 �1�0�1�2�1�2 �1�0�1�5�1�9�1�4�1�1 �1�7�1�8�1�3 �1�9�1�8�1�5�1�9�1�9 �1�8�1�5�1�9�1�2�1�5�1�1 �1�9�1�8�1�7�1�0�1�9�1�2�1�4�1�0.

![](../.gitbook/assets/image%20%2828%29.png)

�1�0�1�5�1�2�1�9�1�4 �1�9�1�8�1�6�1�4�1�9�1�7�1�1
/archiveLabel, �1�5�1�4�1�3 �1�9�1�8�1�2�1�1�1�9�1�4�1�1 �1�2�1�1�1�9�1�4�1�1 �1�8�1�8�1�7�1�0�1�2�1�9�1�0

�1�8�1�8�1�8�1�7 �1�8�1�7�1�4�1�0�1�9 �1�9�1�8�1�6�1�4�1�9�1�7�1�1 �1�9�1�8�1�9�1�8�1�4�1�1�1�4�1�1 "*\" �1�9�1�7 BJS. �1�4�1�6�1�2�1�9 �1�0�1�9�1�7�1�9�1�8�1�4�1�1 �1�4�1�9�1�4�1�7 �1�5�1�2�1�9�1�9�1�9
"/ archiveXXX":

```javascript
if(message.substring(0, 8)=="/archive"){
   let arr = message.split("/archive");
   let label = arr[1];
   Libs.BlockIO.Bitcoin.archiveAddresses(
      { onSuccess: "/onarchived", onError: "/onerror", labels:label }
   );
}
```





