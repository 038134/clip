-- Summary -- 

Adds support for sending & receiving SMS messages using the RocketSMS gateway.
RocketSMS gateway module for Drupal SMS Framework. Outbound and Inbound. 


-- REQUIREMENTS --

* SMS Framework module


-- INSTALLATION --

Install as usual, see http://drupal.org/node/70151 for further information.


-- CONFIGURATION --

* Configure settings at: SMS Framework > Gateway configuration (admin/smsframework/gateways/rocketsms)

Before you can start sending messages you must enter your username/password and a valid default Sender.

To make inbound SMS work you must set your RocketSMS phone number callback URL to http(s)://yourhost.example.com/rocketsms/receiver

The RocketSMS Android app for incoming messages can be found here https://play.google.com/store/apps/details?id=co.rocketsms


-- CONTACT --

Current maintainer: Marvin Whitfield (rasumo) - https://drupal.org/user/631814