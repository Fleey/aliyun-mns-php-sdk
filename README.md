# MNS SDK for PHP    

> 此包来由：因为aliyun那边已经没有人维护mns sdk php 包，所以只能够自行维护。如您有发现任何此包 bug 均可提交pull request 进行合并修复。

Aliyun MNS Documents: https://www.aliyun.com/product/mns

Aliyun MNS Console: https://mns.console.aliyun.com

## Intall Composer

To install composer by following commands, or see [composer](https://docs.phpcomposer.com/00-intro.html)
```bash
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```

## Install & Use

Add require to your `composer.json`
```json
{
  "require": {
     "fleey/aliyun-mns-php-sdk": ">=1.0.0"
  }
}
```
Use Composer to install requires
```bash
composer install
```

*Note: php version>=5.5.0, and xml extension of php is required.*

## Samples

[Queue Sample](https://github.com/aliyun/aliyun-mns-php-sdk/blob/master/Samples/Queue/CreateQueueAndSendMessage.php)
[Topic Sample](https://github.com/aliyun/aliyun-mns-php-sdk/blob/master/Samples/Topic/CreateTopicAndPublishMessage.php) 
