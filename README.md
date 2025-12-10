<!-- # Flutter-Setup
Flutter setup is just the README for step-by-step set up guide purpose only. -->

<!-- Alignmnent & Top -->
<a name="___top"></a>
<div align="center">

# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=23&weight=500&pause=1000&center=true&vCenter=true&width=550&lines=WELCOME+TO+Flutter+Setup+...;Step-By-Step+Toturial.)](#)
</div>

<!-- Part 1 -->

## Download prerequisite software
For the smoothest Flutter setup, first install the following tools.</br>
### **1** **Install Git for Windows**</br>
Download and Install the latest version of <a href="https://docs.flutter.dev/install/with-vs-code" style="text-decoration: none;">Git for Windows</a>. </br>
For help installing or troubleshooting Git, reference the <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git" style="text-decoration: none;">Git Documentation</a>.
### **2** **Download and Install Visual Studio Code**</br>
To quickly install Flutter, then edit and debug your apps, <a href="https://code.visualstudio.com/docs/setup/setup-overview" style="text-decoration: none;">install and set up Visual Studio Code</a>. </br>

<!-- Part 2 -->

## Install and set up Flutter
Now that you've installed Git and VS Code, follow these steps to use VS Code to install and set up Flutter. </br>

### **1** Launch VS Code </br>
If not already open, open VS Code by searching for it with Spotlight or opening it manually from the directory where it's installed. </br>

### **2** Add the Flutter Extension to VS Code </br>
To add the Dart and Flutter extensions to VS Code, visit the <a href="https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter" style="text-decoration: none;">Flutter extension's marketplace page </a>, and click **Install**. If prompted by your browser, allow it to open VS Code. </br>

### **3** Install Flutter with VS Code
#### **| 1.** Open the command palette in VS Code
Go to **View** > **Command Palette** or press + **Control** + **Shift** + **P**. </br>
#### **| 2.** In the command palette, type **flutter**. </br>
#### **| 3.** Select **Flutter: New Project.** </br>
#### **| 4.** VS Code prompts you to locate the Flutter SDK on your computer. Select **Download SDK.**</br>
#### **| 5.** When the **Select Folder for Flutter SDK** dialog displays, choose where you want to install Flutter. </br>
#### **| 6.** Click **Clone Flutter.** </br>
While downloading Flutter, VS Code displays this pop-up notification: </br>
***Downloading the Flutter SDK. This may take a few minutes.*** </br>
This download takes a few minutes. If you suspect that the download has hung, click **Cancel** then start the installation again.</br>
#### **| 7.** Click **Add SDK to PATH**. </br>
When successful, a notification displays: </br>
***When successful, a notification displays:***</br>
#### **| 8.** VS Code might display a Google Analytics notice.</br>
If you agree, click **OK**. </br>
#### **| 9.** To ensure that Flutter is available in all terminals:</br>
 **> a.** Close, then reopen all terminal windows.</br>
 **> b.** Restart VS Code.</br>
### **4** Validate your setup
To ensure you installed Flutter correctly, run ***flutter doctor -v*** in your preferred terminal.</br>

If the command isn't found or there's an error, check out <a href="https://docs.flutter.dev/install/troubleshoot" style="text-decoration: none;">Flutter installation troubleshooting</a>.

