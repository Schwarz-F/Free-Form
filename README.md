# A Free Form Tool, with the option for signatures and automatic Email Responses
Introduction
Welcome to Free-Form, a PHP & HTML Form Tool with Signature Functionality! This tool allows you to create simple web forms with the ability to collect user signatures and automatically send email responses. This readme will guide you through setting up and using this tool.
Getting Started
Prerequisites

    A web server with PHP support.
    A web browser.
    Basic knowledge of HTML and PHP.

Installation

    Clone or download the project files to your web server.
    Ensure that PHP is properly configured on your server.

Using the Form Tool

    Open the project folder in your web browser.

    You'll find the following files:
        index.php: The main form page.
        process.php: The PHP script for processing form submissions.
        signature-pad.js: JavaScript for capturing signatures.
        email.php: Configure email settings for responses.

    Customize the form fields in index.php according to your requirements. You can add, remove, or modify form fields as needed.

    To add a signature field, insert the following HTML code where you want the signature field to appear:

    html

<div id="signature-pad" class="signature-pad">
    <canvas></canvas>
    <button type="button" class="clear-button">Clear</button>
</div>
<input type="hidden" name="signature" id="signature" />

Include the necessary JavaScript files at the end of the <body> section in index.php:

html

    <script src="signature-pad.js"></script>
    <script src="app.js"></script>

    Configure the email settings in email.php. Replace the placeholders with your SMTP server details and email addresses.

    Once you have customized the form, save your changes.

    Access the form in your web browser and start filling it out. Users can provide their signatures by using the canvas pad.

    When users submit the form, their responses, including signatures, will be sent to the specified email addresses.

License

This tool is provided under the MIT License. Feel free to use, modify, and distribute it as per the license terms.
Support

If you encounter any issues or have questions, feel free to reach out to the author at your.email@example.com.

Enjoy using the PHP & HTML Form Tool with Signature Functionality!
