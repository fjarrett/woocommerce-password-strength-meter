=== WooCommerce Password Strength Meter ===
Contributors: fjarrett
Tags: account, checkout, ecommerce, passwords, security, shop, shopping, store, woocommerce
Requires at least: 4.0
Tested up to: 4.2
Stable tag: 1.0.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html
WC requires at least: 2.1.0
WC tested up to: 2.3.8

Display a password strength meter when customers register during checkout.

== Description ==

The first line of defense for securing any WooCommerce store is to ensure that customers are using strong passwords.

This plugin encourages the use of strong passwords by showing customers a live strength meter that measures the complexity of their password.

The password strength meter is displayed when customers register during checkout and when they change their password from the account page.

== Frequently Asked Questions ==

= Are users forced to choose a strong password? =

No, it simply makes users aware of their password "score" to encourage them to use a strong one, it does not block them from completing the checkout process in any way.

= How is password strength determined? =

Password strength is measured using Dropbox's [zxcvbn library](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/) that is able to smartly measure password entropy.

It is the same library that WordPress core has used for checking password strength in the WordPress Admin [since version 3.7](https://codex.wordpress.org/Version_3.7#Highlights).

== Screenshots ==

1. Customers can see their password's strength when registering for an account during checkout.
2. Password strength is also displayed when customers change their password from the account page.

== Changelog ==

= 1.0.0 - May 21, 2015 =

* Initial release

Props [fjarrett](https://github.com/fjarrett)
