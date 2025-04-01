# Facebook Login Page Simulation 


![image](https://github.com/user-attachments/assets/a4fd515e-f888-4f92-963a-d10de1bc9689)

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🌍 **Multi-language** | Supports 5 languages (EN, PL, RU, AR, DE) |
| 📱 **Responsive** | Works perfectly on all devices |
| 🛡️ **Security** | No data collection - purely frontend |
| 🎨 **UI/UX** | Pixel-perfect Facebook-like design |

| Technology | Details |
|------------|---------|
| **HTML5** | Standard markup language |
| **CSS3** | Flexbox, Media Queries |
| **JavaScript** | ES6+ features |


### 🌐 Default View
The page automatically loads in **English** as the default language.

### 🌍 Changing Languages
Easily switch between supported languages:
1. Scroll to the page footer
2. Click any language link (e.g., Polski, Русский, Deutsch)
3. Watch the interface instantly translate

### ⌨️ Form Interaction
Experience the simulated login flow:
+ Try entering test credentials:
  - Email: test@example.com
  - Password: demo123


# Upcoming Updates (In Progress)

## HTML Structure:

- **Authentication Form**: The form contains two fields where the device ID and token information can be entered. The user can enter these details to perform authentication.

- **Success and Error Messages**: A green message is displayed when authentication is successful. A red error message appears if the user enters incorrect information.

## JavaScript Functionality:

- **Authentication**: Upon form submission, the entered device ID and token are verified. If the authentication is successful, the device's data is securely transmitted.

- **Data Security**: If the user attempts to send unencrypted data, a warning message will be shown. Data is securely transmitted using AES encryption.

- **CryptoJS Library**: The CryptoJS library is used for encryption purposes.

## User Interaction:

- When the correct device ID and authentication key are entered, the authentication is successful, and the data transmission from the device is initiated securely.

- A security warning is displayed if unencrypted data is attempted to be sent.

- Using AES encryption, the data from the device is encrypted and transmitted securely.

