# OpenCartAPI

### A list of all available methods

```php
OpenCart->cart->add($product, $quantity = 1, $option = array());
OpenCart->cart->edit($key, $quantity);
OpenCart->cart->remove($key);
OpenCart->cart->products();

OpenCart->order->add($shipping_method = '', $comment = '', $affiliate_id = '', $order_satus_id = '')
OpenCart->order->edit($order_id, $shipping_method = '', $comment = '', $affiliate_id = '', $order_status_id = '')
OpenCart->order->delete($order_id)
OpenCart->order->history($order_id, $order_status_id = '', $notify = '', $append = '', $comment = '')

OpenCart->payment->address($firstname = '', $lastname = '', $company = '', $address_1 = '', $address_2 = '', $postcode = '', $city = '', $zone_id = '', $country_id = '')
OpenCart->payment->methods()
OpenCart->payment->method($payment_method)

OpenCart->shipping->address($firstname = '', $lastname = '', $company = '', $address_1 = '', $address_2 = '', $postcode = '', $city = '', $zone_id = '', $country_id = '')
OpenCart->shipping->methods()
OpenCart->shipping->method($shipping_method)

OpenCart->reward->add($reward)
OpenCart->reward->maximum()
OpenCart->reward->available()

OpenCart->voucher->apply($voucher)
OpenCart->voucher->add($voucher_from_name = '', $from_email = '', $to_name = '', $to_email = '', $voucher_theme_id = '', $message = '', $amount = '')

OpenCart($url, $sessionFile = '')
OpenCart->getUrl($method)
OpenCart->getCookie()
OpenCart->getLastError()
OpenCart->login($username, $password)
OpenCart->coupon($coupon)
OpenCart->customer($customer_id = 0, $customer_group_id = 0, $firstname = '', $lastname = '', $email = '', $telephone = '', $fax = '')
```
