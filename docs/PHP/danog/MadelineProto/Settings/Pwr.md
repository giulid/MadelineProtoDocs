---
title: danog\MadelineProto\Settings\Pwr: PWRTelegram settings.
description: 

image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# `danog\MadelineProto\Settings\Pwr`
[Back to index](../../../index.md)

> Author: Daniil Gentili <daniil@daniil.it>  
  

PWRTelegram settings.  




## Method list:
* `getRequests(): bool`
* `setRequests(bool $requests): self`
* `getDbToken(): string`
* `setDbToken(string $dbToken): self`
* `hasChanged(): bool`

## Methods:
### `getRequests(): bool`

Get whether to try resolving usernames using PWRTelegram DB.



### `setRequests(bool $requests): self`

Set whether to try resolving usernames using PWRTelegram DB.


Parameters:
* `$requests`: `bool` Whether to try resolving usernames using PWRTelegram DB.  



### `getDbToken(): string`

Get DB token.



### `setDbToken(string $dbToken): self`

Set DB token.


Parameters:
* `$dbToken`: `string` DB token.  



### `hasChanged(): bool`

Get whether this setting was changed, also applies changes.



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)