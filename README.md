# 🌩️ CloudyBridge Add-On

Welcome To The **CloudyBridge** Add-On Integration For Your Minecraft Bedrock Server! This Guide Will Walk You Through The Steps To Get Your Server Connected With Our Bot And Manage Your Community Effectively.

## 🚀 Features

- **Premium Access**: Unlock Premium Features By Registering With Our Bot.
- **Group Management**: Set Up Your Admin And Forum Groups Effortlessly.
- **Minecraft Add-On**: Seamlessly Integrate Your Server With Cloudy WhatsApp Bot.

## 📋 Getting Started

To Get Started With CloudyBridge, Follow These Steps:

1. **Register For Premium Access**:  
   Contact Our Bot At **+62 851-7986-2199** To Register For Premium Access And Unlock The Full Potential Of CloudyBridge.
   Use `?premium` Command And Send Message.

3. **Set Up Groups**:  
   You Will Need To Create Two Groups: An **Admin Group** And A **Forum Group** Whatever Its Name. Invite The Bot To These Groups Via `/join linkGroup` Command.

   <img src="https://github.com/user-attachments/assets/76362f67-cb42-41aa-915e-55cc33897848" width="250px">  <img src="https://github.com/user-attachments/assets/4a50dcb2-38bf-4361-825c-27733f43fda9" width="250px">


5. **Download The Add-On**:  
   Go To The [Releases](#) Section Of This Repository, Download The Minceraft Add-On, And Extract It To Your Desired Location.

6. **Initialize The Groups**:

   - Initialize The **Admin Group** First `/mc init admin`.
   - Then, Initialize The **Forum Group** `/mc init forum`.
  
    <img src="https://github.com/user-attachments/assets/2a5f1ca2-5f17-4237-91ed-ecaff03c872d" width="250px">  <img src="https://github.com/user-attachments/assets/c895158b-78e2-4c03-84b6-53f1d4dc0a37" width="250px">

7. **Generate An Auth Code**:
   Generate The Authentication Code In The Admin Group Using `/mc auth putSomeRandomText` Commands.
   
   <img src="https://github.com/user-attachments/assets/38477627-9daf-40d7-b00c-1f1a427e143f" width="250px">

9. **Configure The Server**:
   - Navigate To The `Scripts` Folder And Edit The `Config.js` File.
   - Match The Server Settings And The Auth Code You Generated Earlier In The Admin Group.
  
  ```javascript
  export default {
      server: "120363309375513096",
      auth: "qwertyuiopasdfghjklzxcvbnm"
  }
  ```
10. **Install The Behavior Pack**:
   Move The `CloudyBridge` Folder Into Your `Behavior_Packs` Directory.

11. **Start Your Server**:  
   Start Your Minecraft Server, And You Should See A Notification In The Console Confirming `[Scripting] </> REST Server Online` That Everything Is Set Up Correctly.

## 🔒 Securing Your Server

- **Enable Allowlist**:  
  Secure Your Server By Using The `allowlist` Command And Setting The Status To `true`.
  
  ![](https://github.com/user-attachments/assets/1000d98e-5297-45b9-8f4d-1ffceab06c1e)

- **Member Registration**:  
  Instruct Your Members To Register On Your Server Using The `/reg` Command. Once Registered, They Can Join And Play.

  ![9](https://github.com/user-attachments/assets/8cefc4b3-b6ad-4c12-80fc-2f5939448125)

- **Ban/Unban Members**:  
  If Any Member Becomes Annoying Or Violates Your Rules, Use The `/ban` Command To Ban Them. If You Wish To Allow Them Back, Use The `/unban` Command.
  
  ![9](https://github.com/user-attachments/assets/f59d8d93-1776-4fd9-80fe-0350aaa15496)

- **Player Info Lookup**:  
  Retrieve Player Information Using The `/mc player` Command, Providing Either Their Gametag Or Phone Number.
  
  <img src="https://github.com/user-attachments/assets/9396a512-5bf6-43c7-a878-39c6e2e6df14" width="250px">

- **Execute In-Game Commands**:  
  You Can Execute Any In-Game Command Via Cloudy Bot, Making Server Management Easier.

  <table style="border-collapse: collapse; width: 100%;">
  <tr>
    <td style="border: none; vertical-align: middle;">
      <img src="https://github.com/user-attachments/assets/e6aea879-22e8-4f89-86da-aed5a95ec816" height="500px" alt="Image 1">
    </td>
    <td style="border: none; vertical-align: middle;">
      <img src="https://github.com/user-attachments/assets/ca6e1cfa-5d0b-4b85-a8b5-ff069767324e" height="400px" alt="Image 2">
    </td>
  </tr>
</table>
  
## 🌐 Setting Server Status

The Last Step Is To Configure Your Server's Ip/Domain And Port Using `/mc server` To Retrieve Server Status Updates Using `/mc status` Without Any Parameter.

 <img src="https://github.com/user-attachments/assets/e997998a-150c-42d1-8dd6-400558a327ae" width="250px">

## 🎉 Enjoy!

You're All Set! Enjoy Managing Your Minecraft Server With CloudyBridge. If You Encounter Any Issues Or Have Questions, Feel Free To Reach Out.

---
