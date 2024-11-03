# GrassXD

A program designed to help you collect grass points easily.


## Table of Contents

- [Registration](#registration)
- [Warnings and Notes](#warnings-and-notes)
- [About Proxy](#about-proxy)
- [How to Use](#how-to-use)
- [JavaScript Code to Get Data](#javascript-code-to-get-data)
  - [Code to Get User ID](#code-to-get-user-id)
  - [Code to Get Token](#code-to-get-token)
- [Discussion Forum](#discussion-forum)
- [Support](#support)
- [Acknowledgments](#acknowledgments)

---

## Registration

If you haven't registered for Grass yet, you can use the following referral link to sign up: [Grass Registration](https://app.getgrass.io/register/?referralCode=Qj0nK0iL4SRgIT8)

## Warnings and Notes

- **Important**: All risks associated with using this program are the responsibility of the user.
- This program only supports a single account.

## About Proxy

For enhanced privacy or location-specific usage, you may use proxy services. Currently recommended:

- [NST Proxy](https://app.nstproxy.com/register?i=YhCRDQ)

Supported proxy formats include:
```
http://host:port
socks5://host:port
http://user:password@host:port
socks5://user:password@host:port
```

## How to Use

1. **Prerequisites**: Ensure Python and Git are installed on your computer.
   
2. **Clone the Repository**:
   Open a terminal on your device (CMD/PowerShell/Terminal) and run:
   ```bash
   git clone https://github.com/ShadowScripts1/grass-xd.git
   ```

3. **Navigate to the Project Folder**:
   ```bash
   cd grass-xd
   ```

4. **Install Required Libraries**:
   ```bash
   python -m pip install -r requirements.txt
   ```

5. **Configure Proxies** (Optional):
   Fill in your proxies in `proxies.txt` using the formats shown in [About Proxy](#about-proxy). If left empty, the program will use your public IP by default.

6. **Run Setup for Authentication**:
   Run the `setup.py` file to input your Grass account email and password. This generates your user ID and token automatically. If you encounter issues, manually obtain your user ID and token as described in [JavaScript Code to Get Data](#javascript-code-to-get-data).

7. **Execute the Program**:
   Run the main program by executing `main.py`.

## JavaScript Code to Get Data

### Code to Get User ID

Ensure you're logged into the Grass website. Open your browser's Developer Console (DevTools) and paste the following code:

```javascript
copy(JSON.parse(localStorage.getItem("userId")))
```

This will automatically copy the `userId` to your clipboard, ready for you to paste into the `userid.txt` file.

### Code to Get Token

Similarly, use the following code in the Developer Console to get your token:

```javascript
copy(JSON.parse(localStorage.getItem("accessToken")))
```

The `accessToken` will be copied to your clipboard for easy pasting into the `token.txt` file.

## Discussion Forum

For any questions, join the discussion [here](https://web.telegram.org/k/#@shadowscripters).

## Support

If you need additional support, please reach out through the Telegram channel linked above or open an issue in the GitHub repository.

## Acknowledgments

Thank you for using GrassXD. Your support and feedback are greatly appreciated!

--- 