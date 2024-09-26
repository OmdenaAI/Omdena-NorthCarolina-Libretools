# North-Carolina-Libretools-
North Carolina, USA Chapter" - LibreTools AI Assistant Plugin


#LibreTools AI Assistant Plugin Documentation
The primary goal of LibreTools is to seamlessly integrate a program called LMStudio into LibreOffice, allowing users to run large language models (LLMs) locally on their machines. LMStudio will utilise the local computer's GPU to efficiently process and serve these models. To ensure smooth operation and easy access, LibreTools will feature a user-friendly GUI that connects directly to the LLM's IP address. This connection can be established either through the local intranet or using a service like ngrok for remote access.

        
By leveraging local hardware and providing a straightforward interface, LibreTools aims to make advanced AI capabilities accessible to all users, without the need for expensive cloud services or complex setup procedures. This approach not only enhances the functionality of LibreOffice but also ensures that users maintain control over their data and resources, aligning with the principles of privacy and open-source development.
    
#Installation Instructions
    
Step 1: Install LM Studio
Download and install LM Studio from <a href="https://releases.lmstudio.ai/win32/x86/0.3.2/2/LM-Studio-0.3.2-Setup.exe">this link</a>

Step 2: Download the LLM Model
Download the required LLM model. <a href="https://lmstudio.ai/docs/basics/download-model">this link</a>
Step 3: Download LibreOffice
Download and install LibreOffice from <a href="https://www.libreoffice.org/download/download-libreoffice/">the official LibreOffice website</a>
Step 4: Clone the Repository
Open a Terminal or Command Prompt.
Navigate to the directory where you want to clone the project using the <code>cd</code> command. For example: <code>cd ~</code>
Clone the repository using the following command :
<code>git clone git clone https://dagshub.com/Omdena/NorthCarolinaUSAChapter_LibreToolsAIAssistantPlugin.git</code></li>

Step 5: Copy the Python Script
Run the following command in the command line :
<code>copy "C:\Path\To\Your\scriptlocatepython.py" "C:\Program Files\LibreOffice\share\Scripts\python"</code>

Step 6: Load the Dialog File
Open LibreOffice and create a new file.
In the navigation bar, go to Tools > Macros > Organize Dialogs.
Select "Libraries" and click "Edit".
Go to File (in navbar) > Import Dialog.
      
<img src="1.png" alt="Image 1">
<img src="2.png" alt="Image 2">
<img src="3.png" alt="Image 3">


Step 7: Run LM Studio Server
Open LM Studio and start the server.
<img class="image" src="4.png" alt="Image 4">
        
    

Step 8: Run the Macro
In LibreOffice, go to Tools > Macros > Run Macro > script locate python > Main
<img src="5.png" alt="Image 5">

<img src="6.png" alt="Image 6">


#Note
These instructions are specific for windows . You may need to adjust some steps based on your specific operating system or setup.
