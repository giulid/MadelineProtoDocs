---
title: phone.toggleGroupCallStartSubscription
description: phone.toggleGroupCallStartSubscription parameters, return type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/phone_toggleGroupCallStartSubscription.html
---
# Method: phone.toggleGroupCallStartSubscription
[Back to methods index](index.md)



### Parameters:

| Name     |    Type       | Required |
|----------|---------------|----------|
|call|[InputGroupCall](../types/InputGroupCall.md) | Yes|
|subscribed|[Bool](../types/Bool.md) | Yes|


### Return type: [Updates](../types/Updates.md)

### Can bots use this method: **YES**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Updates = $MadelineProto->phone->toggleGroupCallStartSubscription(['call' => InputGroupCall, 'subscribed' => Bool, ]);
```

Or, if you're into Lua:

```lua
Updates = phone.toggleGroupCallStartSubscription({call=InputGroupCall, subscribed=Bool, })
```
