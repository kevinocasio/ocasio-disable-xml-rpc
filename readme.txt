=== Ocasio Disable XML-RPC ===
Contributors: ocas
Tags: disable xmlrpc, xml-rpc security, brute force protection, pingback, security
Requires at least: 6.0
Tested up to: 7.1
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Blocks the XML-RPC endpoint to protect your website against brute-force login attacks and pingback exploits.

== Description ==

The `xmlrpc.php` file is one of the most heavily targeted files on any WordPress site. Hacker botnets attack it to test thousands of username and password combinations in a single second. This bypasses standard login screen limits and burns up server memory.

Unless you publish posts using older remote desktop tools, you don't need XML-RPC open. Modern WordPress plugins and the official WordPress mobile app use the REST API instead.

Ocasio Disable XML-RPC blocks all XML-RPC requests completely and strips pingback headers from your server responses. It locks down your website against automated attacks with zero configuration required.

= Features =

* **Direct XML-RPC Block:** Kills all incoming requests to `xmlrpc.php` with an instant 403 Forbidden stop sign.
* **Removes Pingback Headers:** Strips `X-Pingback` headers to prevent server scanning and pingback amplification.
* **Stops Password Guessing:** Prevents automated botnets from testing passwords through the back door.
* **Zero Front-End Code:** Runs entirely on backend security hooks with 0 KB of front-end CSS or JavaScript.
* **Instant Dashboard Switch:** Turn the block on or off anytime directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-disable-xml-rpc` folder to your `/wp-content/plugins/` directory, or install the zip file through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Open **Ocasio Plugins -> Dashboard** in your sidebar to verify the Active on Site switch is enabled.

== Frequently Asked Questions ==

= Will this break the official WordPress Mobile App? =
No. The modern WordPress mobile app and Jetpack connect through the REST API, not the legacy XML-RPC interface.

= Will this slow down my website? =
No. It helps your site run faster by blocking malicious bot traffic before it consumes database memory.

== Changelog ==

= 1.0.0 =
* Initial public release.
