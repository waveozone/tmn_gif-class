# TrueWallet Gift PHP CLASS

## Installation

```php
include "library/tmn_gif.class.php";
$tw = new phaiwan_tmn_gif();
```

## Example
```php
$redeem = json_decode($tw->redeem($_GET['link'], $_GET['phone']),true);
if ($xxx['status']['code'] == "SUCCESS") {
    $amount = str_replace(',', '', $xxx['data']['voucher']['amount_baht']);
    echo $amount." บาท";
    //code here 
} else {
    //error here
}
```
