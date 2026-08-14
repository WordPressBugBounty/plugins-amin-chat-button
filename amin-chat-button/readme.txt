=== Pulsating Chat Button ===
Contributors: Amin Shah
Tags: whatsapp, telegram, whatsapp chat, telegram chat, chat button
Requires at least: 5.6
Tested up to: 7.1
Stable tag: 1.5.10
Requires PHP: 7.0
License: GPLv2 or later
License URI: https://t.me/aminsha/

Adds a pulsating WhatsApp or Telegram chat button to your site. Pre-filled message, Google Tag and Yandex.Metrica goals.

== Description ==

WhatsApp or Telegram Chat. Let's make your Web page visitors contact you through "WhatsApp", "WhatsApp Business" or "Telegram" with a single click (WhatsApp Chat, Group, Share). Adds a pulsating WhatsApp or Telegram button to your website. Fast and easy installation. Setting up target id Google Tag and YandexMetrics. Setting pre-filled Message.

== WhatsApp Chat ==

Add 'WhatsApp', 'WhatsApp Business' or Telegram Number and let your website visitors contact you with a single click.
	
**Mobile:**  Navigate to WhatsApp Mobile App.
**Desktop:** Navigate to the WhatsApp Desktop App or Web WhatsApp page (web.whatsapp.com)

### Plugin Features:
1. Quick and effortless installation of a pulsating WhatsApp or Telegram button on your website.
2. Integration of Google Analytics and Yandex.Metrica goal tracking for the button.
3. Custom CSS support for easy customization and seamless integration with your website's design.
4. Enhance communication with your website visitors, providing them with a convenient way to reach out to you.
5. Improve customer engagement and satisfaction by enabling instant messaging and quick response times.
6. Increase conversion rates and drive more sales by offering a direct and efficient communication channel.
7. Flexible positioning options to place the button in the desired location on your website.
8. Compatible with various website platforms and responsive design for optimal user experience across devices.
9. User-friendly interface and intuitive settings for easy configuration and management of the plugin.
10. Regular updates and reliable support to ensure the plugin remains functional and up-to-date with the latest advancements.
11. Multilingualism in the first text message for Whatsapp in accordance with the localization of the site language.

Experience the benefits of this plugin and enhance your website's communication capabilities with the pulsating WhatsApp or Telegram button.

== Frequently Asked Questions ==

= How do I install the WhatsApp or Telegram button plugin on my website?  =
The installation process is quick and easy. Simply follow the provided instructions or refer to the documentation for step-by-step guidance.

= Can I customize the appearance of the WhatsApp button?  =
Yes, you can customize the button's CSS to match your website's design and branding. The plugin provides options for customizing its appearance.

= Does the plugin support goal tracking with Google Analytics and Yandex.Metrica? =
Yes, the plugin offers integration with both Google Analytics and Yandex.Metrica, allowing you to track goals and monitor the effectiveness of the WhatsApp button.

= Can I position the WhatsApp or Telegram button anywhere on my website? =
Absolutely! The plugin offers flexible positioning options, allowing you to place the button in the desired location on your website.

= Will the WhatsApp or Telegram button help improve customer engagement? =
Yes, by providing a convenient and instant messaging channel, the WhatsApp button enhances customer engagement and facilitates quick communication with your website visitors.

= Can the WhatsApp button or Telegram contribute to increased conversions and sales? =
Definitely! By offering a direct and efficient communication channel, the WhatsApp button can lead to higher conversion rates and drive more sales.

= Is the plugin compatible with different website platforms? =
Yes, the plugin is designed to be compatible with various website platforms, ensuring its seamless integration regardless of your chosen platform.

= Is the plugin responsive and optimized for mobile devices? =
Yes, the plugin is designed with a responsive layout, ensuring optimal user experience and functionality across different devices.

= Is the plugin user-friendly and easy to manage? =
Absolutely! The plugin features a user-friendly interface and intuitive settings, making it easy to configure and manage according to your preferences.

= Can I expect regular updates and support for the plugin? =
Yes, the plugin is regularly updated to stay compatible with the latest advancements, and reliable support is available to assist you with any queries or issues you may encounter.

== Upgrade Notice ==

= 1.5.10 =
Resolves the issues reported by Plugin Check: output escaping on the button click handler, the Domain Path header and the length of the short description.

= 1.5.9 =
Compatibility with WordPress 7.1. Fixes the "Settings" link on the Plugins page, prevents a JavaScript error on click when Google Analytics is missing or blocked, and stops the plugin admin styles from affecting other admin screens.

== Changelog ==

= 1.5.10 =
* The button click handler is now escaped with esc_attr on output, resolving the Plugin Check escaping error.
* Removed the Domain Path header, as the plugin ships no languages folder.
* Shortened the readme short description to the supported 150 characters.

= 1.5.9 =
* Declared compatibility with WordPress 7.1.
* Fixed the "Settings" link on the Plugins page: it used a non-existent hook and pointed at the wrong page.
* Analytics calls on click now go through the safeGtag helper, so a missing or blocked gtag no longer throws a JavaScript error and interrupts the handler.
* Admin styles are now loaded only on the plugin settings screen and scoped to the plugin table, instead of restyling every table in the WordPress admin.
* Message fields are escaped with esc_textarea, so line breaks and quotes in saved messages are preserved.
* The current URL is now built with home_url() instead of raw $_SERVER input.
* Analytics IDs are escaped with esc_js in the click handler, so a quote in a target ID can no longer break the generated JavaScript.
* Added the ABSPATH guard, the missing plugin headers and a single version constant.

= 1.5.8 =
* Pulsation is now controlled by a checkbox in the settings and can be turned off.

= 1.5.7 =
* Minor fixes.

= 1.5.6 =
* Direct links for the button have been added.

= 1.4.1 =
* Security settings check update!

= 1.3.3 =
* Adding the first text for messages and a number in WhatsApp in different localizations.

= 1.2.9 =
* Adding multilingualism in the first text message for Whatsapp in accordance with the localization of the site language.

= 1.2.7 =
* Add Telegram button.

= 1.2.3 =
* CSS Code Adjustment
* Adding Analytics Options.

= 1.2.2 =
* Minor fixes.

= 1.1 =
* CSS Code Adjustment.

= 1.0 =
* First Release of the Plugin.