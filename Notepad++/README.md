# Notepad++ Fabric Engine KL Syntax Highlighter  #
**Version 1.1** Released June 23, 2014  
by Andrew Hazelden

![This is a sample show script that has syntax highlighting](screenshots/kl_notepad++_bulge.png)

## Overview ##
I would like to present a new Notepad++ syntax highlighting module that works with code from [Fabric Engine's KL language](http://documentation.fabric-engine.com/FabricEngine/1.11.0/HTML/KLProgrammingGuide/index.html). The new module makes it easier for a VFX Artist or Technical Director to edit a KL script.

**Update:** Version 1.1 improves Hex number highlighting and adds a Notepad++ `Compare.ini` preference file for improved text legibility when using the Notepad++ file comparison features.

**Note:** The free program Notepad++ is required to use the syntax highlighter.

## Download ##

The Fabric Engine KL Syntax Highlighter module is a free download.

You can download the latest version here:   
[http://www.andrewhazelden.com/blog/2014/03/fabric-engine-kl-syntax-highlighter/](http://www.andrewhazelden.com/blog/2014/03/fabric-engine-kl-syntax-highlighter)

## Installation ##

**Step 1.**  [Download Notepad++](http://notepad-plus-plus.org/download/v6.4.5.html) and install it on your system. After you start Notepad++ you will see a blank text editing window.

![Starting up Notepad++](screenshots/1_notepad++_UI_start.png)

**Step 2.**  The syntax highlighting module has been customized to work with the dark background based **Obsidian** theme. To load the Obsidian theme in Notepad++, go to the **Settings** menu and select **"Style Configurator..."**

![Open the Style Configurator](screenshots/2_style_configurator.png)

In the Style Configurator window select the **Obsidian** theme and click the **Save and Close** button. 

![Choose the Obsidian Theme](screenshots/3_style_configurator_obsidian.png)

**Step 3.** Let's load the custom "Fabric KL" syntax highlighting module. Open the **Language** menu in Notepad++ and select the **"Define your language..."** menu item. The **User Defined Language** window will load.

![Load the Define Your Language Window](screenshots/4_define_your_language.png)


**Step 4.** In the **User Defined Language** window, click on the **Import** button to load the XML based language file.

![Click the "Import" button](screenshots/5_import_a_language.png)

In the open dialog select the **"userDefine_FabricEngineKL.xml"** file and click **open**.

![Select the userDefine_FabricEngineKL.xml file ](screenshots/6_select_the_language_file.png)

If the file was loaded correctly an "Import Successful" notice will appear.  Click the **OK** button to continue. At this point you should close the "User Defined Language" widow by clicking on the window's **X** shaped close button.

![You will see a "Import Successful" notice](screenshots/7_import_success.png)

**Step 5.**  We need to restart Notepad++ for the new language module to be listed in the Notepad++ language menu.

![This is an unformatted script](screenshots/8_unstyled_text.png)

If you open a Fabric Engine .kl script at this point you will see formatted text. If you are working on an script file without the .kl extension you can select the language manually.

Open the **Language** menu and select **Fabric KL**. This will turn on syntax highlighting and make it easier to develop complex include files.
 
![Select the Mental Ray Language](screenshots/9_select_the_language.png)


Here is an example Fabric Engine .kl script called "swirleyMovementOp.kl" with Notepad++ based syntax highlighting enabled:

![This is a sample show script that has syntax highlighting](screenshots/10_highlighted_fabric_kl.png)

**Bonus Step** If you use the Notepad++ Compare module you can load the new Obsidian theme compatible color palette file "Compare.ini" from the Fabric Engine KL Syntax Highlighter install folder by copying "Compare.ini" to your Notepad++ preferences folder:

    C:\Users\<Your User Account>\AppData\Roaming\Notepad++

![Compare.ini theme update](screenshots/compare-color-update.png)


* * *

I hope this tool improves your coding workflow as you develop new .kl files using the Notepad++ text editor.

Cheers,  
Andrew Hazelden

eMail: [andrew@andrewhazelden.com](mailto:andrew@andrewhazelden.com)   
Blog: [http://www.andrewhazelden.com](http://www.andrewhazelden.com)  
Twitter: [@andrewhazelden](https://twitter.com/andrewhazelden)  
Google+: [https://plus.google.com/u/0/105694670378845894137](https://plus.google.com/u/0/105694670378845894137)


