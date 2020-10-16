---
title: danog\MadelineProto\Stream\Common\UdpBufferedStream: UDP stream wrapper.
description: 

---
# `danog\MadelineProto\Stream\Common\UdpBufferedStream`
[Back to index](../../../../index.md)

> Author: Daniil Gentili <daniil@daniil.it>  
  

UDP stream wrapper.  




---
Generated by [danog/phpdoc](https://phpdoc.daniil.it).  
## Method list:
* `connect(\danog\MadelineProto\Stream\ConnectionContext $ctx): \Generator`
* `disconnect(): \Amp\Promise`
* `getReadBufferGenerator(int $length): \Generator`
* `getWriteBuffer(int $length): \Amp\Promise`
* `getSocket(): \Amp\Socket\EncryptableSocket`
* `getStream(): \danog\MadelineProto\Stream\RawStreamInterface`
* `read(): \Amp\Promise`
* `write(string $data): \Amp\Promise`
* `close(): void`
* `getReadBuffer(int $length): \Amp\Promise`

## Methods:
### `connect(\danog\MadelineProto\Stream\ConnectionContext $ctx): \Generator`

Connect to stream.


Parameters:
* `$ctx`: `\danog\MadelineProto\Stream\ConnectionContext` The connection context  


#### See also: 
* [`\danog\MadelineProto\Stream\ConnectionContext`: Connection context class.](../ConnectionContext.md)
* `\Generator`




### `disconnect(): \Amp\Promise`

Async close.


#### See also: 
* `\Amp\Promise`




### `getReadBufferGenerator(int $length): \Generator`

Get read buffer asynchronously.


Parameters:
* `$length`: `int` Length of payload, as detected by this layer  


Fully typed return value:
```
\Generator<int, \Amp\Promise, mixed, \Amp\Failure<mixed>|\Amp\Success<object>>
```
#### See also: 
* `\Amp\Promise`
* `\Amp\Failure`
* `\Amp\Success`
* `\Generator`




### `getWriteBuffer(int $length): \Amp\Promise`

Get write buffer asynchronously.


Parameters:
* `$length`: `int` Total length of data that is going to be piped in the buffer  


#### See also: 
* `\Amp\Promise`




### `getSocket(): \Amp\Socket\EncryptableSocket`

{@inheritdoc}


#### See also: 
* `\Amp\Socket\EncryptableSocket`




### `getStream(): \danog\MadelineProto\Stream\RawStreamInterface`

{@inheritDoc}


#### See also: 
* [`\danog\MadelineProto\Stream\RawStreamInterface`: Raw stream interface.](../RawStreamInterface.md)




### `read(): \Amp\Promise`

Async chunked read.


#### See also: 
* `\Amp\Promise`




### `write(string $data): \Amp\Promise`

Async write.


Parameters:
* `$data`: `string` Data to write  


#### See also: 
* `\Amp\Promise`




### `close(): void`

Close.



### `getReadBuffer(int $length): \Amp\Promise`

Get read buffer asynchronously.


Parameters:
* `$length`: `int` Length of payload, as detected by this layer  


#### See also: 
* `\Amp\Promise`



