Install Tools:
Kali Linux: Use it as your primary OS or as a VM.
Burp Suite: Install the Community or Professional edition.


OWASP Juice Shop: Run it using Docker:
docker pull bkimminich/juice-shop
docker run -d -p 3000:3000 bkimminich/juice-shop

Search for products using SQLi payloads like ' OR 1=1--.
Inject a script like <script>alert('XSS')</script>.
Use Burp Suite to intercept and modify requests.

Take screenshot of XSS popup

![WhatsApp Image 2025-09-13 at 20 21 34_9af57624](https://github.com/user-attachments/assets/cc9d27a9-536a-42d9-ba73-8734f0c4da1a)
