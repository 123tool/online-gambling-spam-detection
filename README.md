Online Gambling Spam Detection
This repository provides a bash script for performing keyword-based searches across multiple domains using Lynx, then generating log files that can be integrated with notifications via WhatsApp and Telegram. This script is perfect for detecting illegal content, such as online gambling, and helps maintain digital security.

Advantages
Lightweight and Fast: Lynx is a very lightweight text-based browser, making it suitable for automated searches without consuming a lot of resources. No Ads: Because Lynx doesn't display visual elements, you can focus on the text content without being distracted by ads. Works in CLI: Can be run from the command line, making it perfect for integration into automated scripts. No GUI Required: Lynx can be used on servers that don't have a graphical interface, making it suitable for automation in server environments.

WhatsApp Notifier Integration
Uses the m-pedia endpoint to send WhatsApp messages. Sends a summary of search results via text message. Can be configured to disable message delivery as needed.

Telegram Document
Uses the Telegram Bot API to send search result files to Telegram channels. The search results file is sent as a document with a caption containing information related to the keywords and domains being checked.

Telegram and WhatsApp Configuration:
ENABLE_TELEGRAM and ENABLE_WHATSAPP allow users to control whether search results are sent via Telegram or WhatsApp. TELEGRAM_TOKEN, CHAT_ID, API_KEY, SENDER, and NUMBER can be configured to suit user needs for sending notifications.

Please update the sensitive information I have cleared (DOMAIN, TOKEN, CHAT_ID, API_KEY, etc.) to suit your needs.
