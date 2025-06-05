# WhatsApp Direct Message Generator 🚀

A simple, client-side web tool to quickly generate WhatsApp direct message links without needing to save the contact. It also keeps a history of recently generated links for easy reuse, all stored locally in your browser.

## ✨ Features

*   **Country Selection**: Easily select the country code from a comprehensive dropdown list featuring country names, flags, and dial codes.
*   **Phone Number Input**: Enter the recipient's phone number (national format).
*   **Optional Pre-filled Message**: Add a message that will be pre-filled in the WhatsApp chat window.
*   **Instant Link Generation**: Automatically generates the WhatsApp `api.whatsapp.com` link as you type.
*   **Copy to Clipboard**: One-click button to copy the generated link.
*   **Direct Send**: Button to open the link directly in WhatsApp (web or desktop app, depending on your system).
*   **Recent Links History**:
    *   Automatically saves recently generated/used links (up to 10) in your browser's local storage.
    *   Displays recent links with phone number (including flag), and a preview of the message.
    *   **Reuse**: Quickly populate the form with data from a recent link.
    *   **Copy**: Copy the link directly from the recent items list.
    *   **Delete**: Remove individual links from the history.
    *   **Clear All**: Option to clear all saved recent links.
*   **Responsive Design**: Adapts to different screen sizes for a good experience on desktop and mobile.
*   **User-Friendly Interface**: Clean, modern, and intuitive design inspired by WhatsApp's aesthetics.
*   **Self-Contained**: Runs entirely in the browser with no server-side dependencies.

## 🛠️ How to Use

1.  **Save the Code**:
    *   Copy the entire HTML, CSS, and JavaScript code provided.
    *   Save it as an `index.html` file (or any name with an `.html` extension) on your computer.

2.  **Open in Browser**:
    *   Open this `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge, Safari).

3.  **Generate Link**:
    *   **Select Country**: Choose the recipient's country from the dropdown. The country code will be automatically selected.
    *   **Enter Phone Number**: Type the recipient's phone number *without* the country code or any special characters (e.g., for a US number +1 (555) 123-4567, select "United States +1" and enter `5551234567`).
    *   **Add Message (Optional)**: Type the message you want to pre-fill.
    *   The WhatsApp link will be generated automatically in the "Generated WhatsApp Link" section.

4.  **Use the Link**:
    *   **Copy**: Click the "📋 Copy" button to copy the link to your clipboard.
    *   **Send**: Click the "📱 Send WhatsApp Message" button to open WhatsApp with the pre-filled number and message.

5.  **Recent Links**:
    *   Generated or sent links will appear in the "Recent Links" section.
    *   You can reuse, copy, or delete them from there.

## 💻 Technology Stack

*   **HTML**: For the structure of the web page.
*   **CSS**: For styling and layout.
*   **JavaScript**: For all the dynamic functionality:
    *   Populating country codes.
    *   Generating the WhatsApp link.
    *   Handling copy-to-clipboard.
    *   Managing recent links using `localStorage`.
    *   DOM manipulation.

## 📢 Looking for Bulk WhatsApp Marketing?

If you need to send messages in bulk for marketing, notifications, or large-scale communication, our WhatsApp Direct Message Generator is designed for individual, ad-hoc messages.

For robust bulk messaging capabilities, check out our powerful **WA Sender Pro** tool from LeadsFunda:

👉 **[Discover WA Sender Pro for Bulk WhatsApp Marketing!](https://leadsfunda.com/service/wa-sender-pro-bulk-whatsapp-marketing-made-easy/)**

WA Sender Pro offers features like:
*   Sending messages to multiple contacts.
*   Importing contacts from files.
*   Message scheduling.
*   And much more to streamline your WhatsApp marketing efforts!
