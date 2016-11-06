# ip_location_php
获取ip地理位置信息


#demo 

```php
include './src/IpLocation.php';

$ip = '123.125.114.144';

$ipinfo = (new IpLocation)->getlocation($ip);

echo '<pre>';print_r($ipinfo);

<!-- Array
(
    [ip] => 123.125.114.144
    [beginip] => 123.125.112.0
    [endip] => 123.125.115.255
    [country] => 北京市
    [area] => 百度网讯科技联通节点
) -->
```