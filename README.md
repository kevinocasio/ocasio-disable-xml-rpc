# Ocasio Disable XML-RPC

> Lightweight WordPress plugin to completely disable XML-RPC and protect your website against brute-force attacks and pingback exploits.

## Overview

The `xmlrpc.php` file is a frequent target for automated brute-force attacks and pingback amplification exploits. **Ocasio Disable XML-RPC** turns off the XML-RPC endpoint, blocks incoming direct requests with an immediate 403 Forbidden response, and removes pingback headers from server responses.

## Features

* **Block Direct XML-RPC Requests:** Kills requests to `xmlrpc.php` instantly before they reach your database.
* **Strip Pingback Headers:** Removes `X-Pingback` headers to prevent server reconnaissance and pingback relay exploits.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript loaded on public pages.
* **Ocasio Suite Integration:** Toggle the tool on or off through the centralized **Ocasio Plugins -> Dashboard**.

## Installation

1. Download the latest `ocasio-disable-xml-rpc.zip` file from [Releases](https://github.com/kevinocasio/ocasio-disable-xml-rpc/releases).
2. In your WordPress admin dashboard, go to **Plugins -> Add New Plugin -> Upload Plugin**.
3. Choose the downloaded `.zip` file and click **Install Now**.
4. Click **Activate Plugin**.
5. Confirm protection under **Ocasio Plugins -> Dashboard** in your sidebar.

---

## Author & Resources

* **Author:** [Kevin Ocasio](https://kevinocasio.com/)
* **Plugin Page:** [Ocasio Disable XML-RPC on KevinOcasio.com](https://kevinocasio.com/wordpress-plugins/ocasio-disable-xml-rpc/)
* **WordPress Plugins:** [Free WordPress Plugin Directory](https://kevinocasio.com/wordpress-plugins/)
* **Software Portfolio:** [Live Projects & Digital Assets](https://kevinocasio.com/portfolio/)
* **Tools & Resources:** [Recommended Tech Stack & Tools](https://kevinocasio.com/tools/)
* **License:** GPL-2.0-or-later
