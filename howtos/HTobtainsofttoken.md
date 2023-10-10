

# How To: Obtain a Soft Token

Before you start, you will need:

 - The mobile device you will use to retrieve your token, such as a state-issued iPad or iPhone.
 - Your work email address and state PC password available.

## Overview

The state recently started using a security feature called Multi-Factor Authentication (“MFA”). Prior to using MFA, anyone with your username and password could access your account. As MFA requires both your dynamic token code and password, your account remains protected even if your username and password are stolen.

This guide explains how to obtain a token for remote access to secure state applications.

## Background

When using a personal device or a state device not on the state network, a “token” is required to access services including email, WMS, Horizon VDI, and On-Base.

**Software tokens**: A “soft” token uses the RSA SecurID app to generate a numeric passcode code. Each code is valid for 60 seconds. If a code expires, the user may regenerate a new code to access state applications remotely.

**Hardware tokens**: A “hard” token is a physical device that periodically generates passcodes

## Obtain a Soft Token

1. Using the mobile device you will use for your soft token, such as your iPad or smartphone, visit the state token website:

	    https://mytoken.ny.gov/

***IMPORTANT NOTE FOR SOFT TOKEN USERS**: You must complete this task with the actual device you will use to access your token, as the **DeviceSerialNumber** field will be pre-populated. If the **DeviceSerialNumber** field on your token request form does not match the device used for your soft token, your token authentication will fail. You can verify your device’s serial number in the RSA SecurID app.*
\
\
\
2. Log on by entering your work email address as your username.
\
\
\
3. Select “**Password**” for **Authentication Method** and click log on.
\
\
\
4. Enter the password used for your state PC and click log on.

  *Note: You will be prompted to set up security questions and answers the first time you access the state token website.*
\
\
\
5. Select **Request a new token** from the **My Authenticators** section.

  Soft tokens are recommended as they are typically processed and approved by your administrator within 24 hours via email. If you use a state-issued mobile device, you must use a soft token.
  
  You can only obtain hard tokens as a key FOB. After your request is approved, they are typically shipped 2-3 weeks later. To obtain a hard token, please refer to the How-To linked in the “**See also**” section.
\
\
\
6. Select **Software** from the list and click **Submit**.
\
\
\
7. Select the type of device (i.e., iOS, Android, etc.) you will use for your token.

  *Note: **Enterprise iOS – CTKIP** is correct option for a state-issued iPad or iPhone.*
\
\
\
8. Enter a **Nickname** for your token to identify it.
\
\
\
9. Create a **PIN**.

  *Note: The **PIN** must be between 4 and 8 digits. The **PIN** cannot start with “0”. You use this **PIN** to log into the RSA SecurID app to generate a token code.*
\
\
\
10. Enter a **Reason for Token Request**. Common reasons include “need for remote access” and “new phone”.
\
\
\
11. Click **Submit**.


## See also
Consider completing some other common tasks for mobile device users.
- [Quickstart: Soft Tokens](https://github.com/amandax53/knowledgebase/blob/main/quickstarts/QSsofttokens.md)
- [How to: Obtain a Hard Token](https://github.com/amandax53/knowledgebase/blob/main/howtos/HTobtainhardtoken.md)
- [Tutorial: Remote Access of Connections via iPad](https://github.com/amandax53/knowledgebase/blob/main/tutorials/TUTremoteconnectionsIPAD.md)
