VoiceDirect/VoiceDirect Professional 3.0 

This file contains last-minute information that is not 
included in the documentation. 
The following information applies to VoiceDirect 3.0 
and VoiceDirect Professional 3.0 UK editions.

Contents
New Features in Version 3.0
Compatibility with Dragon NaturallySpeaking™
VoiceDirect Dictation Hints
Customising VoiceDirect for Recognition Accuracy
Customising VoiceDirect for Hands-Free Use
For Windows® 95 Users
For Windows NT™ Users
Hardware Compatibility List
Technical Support 
Known Problems (by Application)
Documentation Errata

New Features in Version 3.0 

o	Coexistence with Dragon NaturallySpeaking 
1.0. VoiceDirect 3.0 is designed to work together 
with Dragon NaturallySpeaking, so you can switch 
to continuous dictation with a simple voice command: 
"Switch to NaturallySpeaking". When you use that 
command, if you say "Microphone Off" to disable the 
microphone in Dragon NaturallySpeaking, the microphone 
in VoiceDirect turns on automatically.

o	Delayed correction. The Adapt Only on Correction
 item in the Dictation tab of the Options 
dialogue box is now selected by default. This way, you 
can dictate a long document without correcting 
errors right away and if you do not correct errors 
consistently and accurately, your voice files will 
not be corrupted. However, this also means that recognition 
accuracy on untrained voice files will not 
improve as quickly. Also, this may not be the best setting 
for environments in which the noise level 
changes or for accommodating voice changes that result, 
for example, from a cold.

o	Office 97 support. VoiceDirect supports Office 97 
running under Windows 95. However, VoiceDirect does not track 
Office 97 menus on NT 4.0. (For more on Office 97 support, 
see the Known Problems section.)

o	Pronunciation Generator™. Adds a phonetic pronunciation 
for new words that you add to VoiceDirect, so that the words 
adapt to your speech and can be used in continuous phrases 
and commands. Also, most menu commands and application-specific 
macros that you previously had to train now have pronunciations 
generated automatically. 

o	New (restructured, more accurate) VoiceDirect online 
Help file. 

o	New Install Wizard for installing and uninstalling 
VoiceDirect.

o	Improved Audio Wizard for Windows 95 users.

o	New Macro Language Guide and Reference Help file. 
This online Help file tells you how to use the macro language 
and lists and describes all macro language commands.


Compatibility With Dragon NaturallySpeaking 

You can use VoiceDirect's VoiceDirect with Dragon 
NaturallySpeaking 
to get both voice control of your computer and continuous 
dictation. 
The VoiceDirect User Guide Appendix A "Working with Dragon 
NaturallySpeaking" tells you how to use the two programs together. 
To use both programs, your computer must meet the following 
additional system requirements, beyond those required for VoiceDirect:

o	At least a Pentium® 133 MHz Processor IBM®-compatible PC. 

o	32 MB of RAM beyond those required for VoiceDirect 
(for a total of 48 MB RAM).

o	Windows 95 or Windows NT. (See "For Windows NT Users" 
later in this file for VoiceDirect Windows NT limitations.)

o	Approximately 60 MB free hard disk space, plus 
additional space for temporary storage during training 
and other operations.


VoiceDirect Dictation Hints

o	Do not dictate continuous phrases for more than 
10 seconds without pausing.

o	For rapid adaptation, especially if your voice or 
environment changes, create a new user and go through Quick 
Training. Then clear the Adapt Only On Correction checkbox 
in the Dictation tab of the Options dialogue box. Speak 
discretely and slowly into your application for 15-30 minutes 
(200 words) and correct every recognition error that VoiceDirect 
makes. (If you do not correct the errors, VoiceDirect will not 
adapt correctly.) Gradually increase your dictation pace while 
you continue to correct errors. Once you achieve optimal 
recognition performance, select the Adapt Only On Correction 
checkbox in the Dictation tab of the Options dialogue box.

o	For a command that VoiceDirect should recognise, 
if you say it a few times and VoiceDirect does not recognise it 
(that is, {???} appears in the Choice List), say "Command Mode", 
then repeat the command. This should make VoiceDirect recognise 
the command. Note, however, that this information does not  
apply to commands in Dictate Mode that you specified as commands 
not to appear as the first choice in the Choice List.

o	To undo some commands, you must say "Undo" several times 
to completely undo the command. For example, after the "Quote 
Previous Word" command, you must say "Undo" to delete the trailing 
quote, again to delete the word, again to delete the leading quote 
and again to restore the word.


Customising VoiceDirect for Recognition Accuracy

You can do several things right after you start VoiceDirect for the 
first time to be sure VoiceDirect's recognition accuracy is optimal.

1.	Be sure your microphone is positioned correctly and that you 
use the foam covering on the microphone to suppress background noise.

2.	If VoiceDirect is recognising noise in your environment while 
you are dictating, adjust the default setting of the Background Noise 
Level slider (in the Recognition tab of the Options dialogue box) to 
compensate for this noise. 

3.	For some microphone and multimedia sound card combinations, 
the automatic setting in the Microphone Volume dialogue box may not 
be optimal. If you have a multimedia sound card and VoiceDirect does 
not seem to be hearing you, or if VoiceDirect hears too much background 
noise, you can manually change the setting in the Microphone Volume 
dialogue box after the automatic procedure. Select Tools from the Voice 
Menu, then select Microphone Volume Setting and make the adjustments 
you want. Also, you can try using the Audio Setup Wizard. 

You can also try adjusting the hi/low switch (if it exists) on the microphone.

4.	If VoiceDirect seems to have a hard time recognising a 
particular word, even after you correct it, you can train that 
specific word. From the Voice Menu, select Quick Access, then select 
Find Word. Begin typing the word in the Word Name field until the entire 
word appears and is selected, then select Train. If you want to be sure the 
word is well trained, select Options in the Training Console dialogue box and 
then select Intense before training the word.

	Note that VoiceDirect will not recognise some words even with training. 
For example, VoiceDirect will not recognise the phrase "C colon backslash" to 
get "C:\" in your document. For words like this, provide the pronunciation in 
brackets in the Word Name field, for example: "C:\ [C colon backslash]."

5.	Sometimes, common commands, such as What Can I Say, are not recognised 
after you say them several times and your user files are well adapted. Try 
retraining the command and  thereafter consciously say the command the same 
way as you trained it. 

Customising VoiceDirect for Hands-Free Use

If you are strictly a hands-free user, consider setting up your 
system for hands-free use. Refer to chapter 10 in the User Guide 
for helpful information about running VoiceDirect hands free. 
You can also download a file (refer to the next section, "Technical 
Support") called DDWEXIT.ZIP from http://www.imsisoft.com/vd, 
which lets you restart Windows, exit Windows and reboot your computer 
by speaking. If you're using Windows 95, get the file called EXIT95HF.DDX.


For Windows 95 Users

Keep in mind the following as you use VoiceDirect with Windows 95:

1.	Desktop Folders and Shortcuts
VoiceDirect cannot get any information about icons and folders on the 
Windows 95 desktop, so the only way you can select these items by 
speaking is to use the MouseGrid.

Use the Bring Up Task n command to reactivate applications listed in 
the taskbar by speaking. You can also use Arrow Movement Commands to 
move to a certain item in a folder, then say "Press Enter" to 
activate the selected item.

2.	Moving Around in Windows Explorer by Speaking
To move around in the hierarchy of folders by speaking, use Cursor 
Movement Commands, such as "Move Left", "Move Right" and so on. 
Refer to the Quick Reference Card for a list of Cursor Movement Commands.

3.	Bring Up
The taskbar and Windows Explorer replace the Windows 3.x Program Manager. 
Also, the VoiceDirect (or VoiceDirect Professional) folder under 
Programs in the Start menu replaces the VoiceDirect (or VoiceDirect 
Professional) group in the Program Manager. Be sure that programs you 
want to start by saying "Bring Up" are in the VoiceDirect (or VoiceDirect 
Professional) folder, the Start menu folder (and therefore appear at the 
top of the Start menu), or in the Programs folder (and therefore appear 
at the bottom of the Programs menu).

Also, if you change the name of the Bring Up group (from Voice Menu, 
Options, Start Up tab, Name of Bring-Up Group field), be sure that this 
name corresponds to the name of the top-level Bring Up folder in the 
Programs folder. Otherwise, VoiceDirect will not recognise any Bring Up 
commands. The Bring Up folder must always be a top-level folder in the 
Programs folder.

4.	System Keystrokes
The SendKeys scripting command does not work with the {Alt+Esc}, 
{Shift+Alt+Esc}, {Alt+Tab} and  {Ctrl+Esc} keystrokes. Instead, 
use the SendSystemKeys scripting command in macros that have these 
keystrokes. For example, SendSystemKeys "{Ctrl+Esc}" opens the Start 
menu. Refer to the macro language Help file for more information.


For Windows NT Users

IMSI provides only limited support for Windows NT 4.0 in VoiceDirect 
3.0, although you should find that its performance is acceptable in 
your particular application. 

Running 16-bit Applications
In Windows NT, any Windows 3.x (16-bit) application can be run in its 
own memory space separate from other Windows 3.x applications. Doing 
so protects other Windows 3.x applications if this application crashes 
or hangs.

However, VoiceDirect cannot correctly identify applications that run 
in a separate memory space. Instead of displaying their names (Microsoft 
Word, Microsoft Excel, and so on), VoiceDirect displays "Generic 16-bit 
application" in the active vocabulary pane of the Voicebar. Therefore, 
all Windows 3.x applications that you want to use by speaking must run 
in the shared Windows 3.x memory space.

To verify that an application is set up to run in the shared memory 
space, select the icon associated with the application from the Program 
Manager, then select Properties from the File menu. If the Run in Separate 
Memory Space option in the Program Item Properties dialogue box is dimmed, 
the application is not a Windows 3.x application and is compatible 
with VoiceDirect. If the option is available, be sure it is not selected.

Screen Savers and Log On Dialogue Boxes
For security reasons, in Windows NT when the screen saver starts, or 
the Log On dialogue box appears, or the Security dialogue box appears, 
all other applications currently running are closed. As a result, if 
you are running VoiceDirect in Windows NT, speech input is disabled 
when the screen saver starts. Therefore, VoiceDirect automatically 
disables the screen saver so that you can still use speech. If you do 
not want VoiceDirect to automatically disable the screen saver, remove 
the following line from the [Defaults] section of the DDWIN.INI file: 
"Internal: Do Not Allow Screen Saver=1".

Additional Problems in Working With Windows NT

Symptom: If VoiceDirect misrecognises a word while you are dictating, 
you typically say "Oops" to bring up the Word History window and 
correct the error. However, after you make the correction and close 
the Word History window, the correction is not always transferred 
back into your document -- the previous text resulting from the 
misrecognition may remain.

Analysis: VoiceDirect may be unable to verify that the window which 
received the input focus when the Word History was closed is the 
same as the window into which you were originally dictating. In this 
case, VoiceDirect aborts the correction rather than risk sending 
keystrokes to the wrong window (which could result in loss of data). 
Note that the attempted correction still results in adaptation.

This problem can occur when dictating into particular 
(for example, some spreadsheets) that create temporary windows for 
text input, then delete these windows when the user leaves input mode. 

In some other, less common circumstances (primarily in Windows NT 4.0), 
VoiceDirect may be unable to determine which window has the input focus. 

Workaround: Select and delete the incorrect text that remained in 
your document, then type or dictate the correct text.

Symptom: If VoiceDirect misrecognises a word while you are dictating, 
you typically say "Oops" to bring up the Word History window and 
correct the error. However, when the corrections are made and the 
Word History window is closed, the corrections may be only partially 
transferred to your document. The incorrect text may not be completely 
deleted, some letters may be missing from the corrected text and /or 
words in the corrected text may not be separated by spaces.

Analysis: The cause of this behaviour is not completely understood. 
It appears that, following the correction, VoiceDirect is sending 
keystrokes faster than the application can process them. This timing 
problem may be worsened due to the large amount of time NT requires 
to switch context from one running application to another.

Workaround: In most cases, reducing the keystroke input speed for 
the application can prevent this problem. To change this configuration:
1.	From the VoiceDirect Voice Menu, select "Options…"
2.	Select the "Compatibility" tab, highlight the application, 
then select the "Options…" 
	button
3.	Adjust the "Input Speed" slider to the left.

Symptom: When you use the [Start Menu] command to access the Start 
menu under Windows NT 4.0, or the [Voice Menu] command to access 
VoiceDirect features, VoiceDirect may recognise the item you select 
from this menu (or one of its submenus) correctly, but select an 
adjacent menu item instead. This is usually limited to cases in which 
another application has the focus when the command is executed.

Analysis: If the Start menu (or other popup menu) is opened by voice 
when another application has the focus, Windows may open the menu without 
selecting a default item. If this happens, VoiceDirect may be unable to 
select a specific item correctly and may instead select an adjacent item. 
This problem may occur more frequently if you have installed a utility 
program (such as the PowerToys utilities from Microsoft®) that modifies 
the Start menu to add nonstandard items that VoiceDirect does not expect.

Workaround: You may find the problem of incorrect Start menu selections 
lessens or disappears when you uninstall the utility that modified your 
Start menu. If this is not applicable or does not fix the problem, you 
can navigate the Start menu by voice and use [Enter Key] command to make 
your selection.

Symptom: Lower-level menu items in Microsoft Office 97 applications are 
not automatically tracked, so you cannot simply "Say What You See" to 
navigate submenus in Windows NT.

Analysis: In Office 97, third-party programs such as VoiceDirect access 
menus through Microsoft's "Active Accessibility" programming interface. 
Unfortunately, this interface is not supported in the current Windows NT 
version.

Workaround: After bringing up the initial menu, use [Move Down xxx] 
and/or alpha-bravo commands to select items within the submenus. You 
can also use the built-in macro scripting language to add commonly used 
commands as needed.

Symptom: WordPerfect® 7 or VoiceDirect may exit or exhibit erratic 
behaviour when VoiceDirect macros are executed. Menu and dialogue 
tracking are also inconsistent. This behaviour has been observed in 
both early and newer (NT-compatible) versions of WordPerfect 7, but 
not in WordPerfect 8.

Analysis: Unpredictable behaviour can occur when VoiceDirect is loaded 
and generating keystrokes that bring up WordPerfect 7 menus and dialogue 
boxes. Due to the nature and extent of these problems, further technical 
analysis was not performed. 

Workaround: IMSI does not recommend using VoiceDirect with WordPerfect 7 
under Windows NT.

Hardware Compatibility List

Refer to the "DragonDictate's VoiceDirect Hardware Compatibility List" 
for the most current list of certified sound cards and microphones. 
To access this list go to http://www.imsisoft.com/voicedirect/index.html.

Technical Support 

The product manual, this README file and online Help can help you 
solve software problems. You can get additional help at:

IMSI Australia P/L
Unit 7, 4 Huntley Street
Alexandria, NSW 2015
Australia

Tel:  +61 (0)2 9319-7533
Fax: +61 (0)2 9319-7625
E-mail: support@imsiaus.com.au
URL: http://www.imsi.com.au

IMSI South Africa (Pty) Ltd.
P.O. Box 1000
Ferndale, 2160
South Africa

Tel:  +27 (0)11 792-9944
Fax: +27 (0)11 792-9952
E-mail: support@imsisa.co.za
URL: http://www.imsisa.co.za

Known Problems (by Application)

VoiceDirect: Installation
o	If you choose to do a Quick Install and you upgrade to a 
new directory, your old version of VoiceDirect, as well as your 
old users, do not get upgraded.

VoiceDirect: Compatibility with Dragon NaturallySpeaking
o	If you are running Dragon NaturallySpeaking and VoiceDirect 
simultaneously and you want to switch to Dragon NaturallySpeaking by 
saying "Switch to NaturallySpeaking", Dragon NaturallySpeaking must 
already be fully installed (that is, you must have already gone 
through the Audio Setup Wizard and general training), so that neither 
the Tip of the Day nor the Quick Tour appear. Otherwise, your system freezes.

o	If the Dragon NaturallySpeaking Tip of the Day dialogue box 
is open, when you use the VoiceDirect "Switch to NaturallySpeaking" 
command, the Dragon NaturallySpeaking Tip of the Day dialogue box 
appears, which you cannot close by voice. As a workaround, when the 
Tip of the Day dialogue box comes up and the Dragon NaturallySpeaking 
microphone goes on, say "Microphone Off", which turns off the Dragon 
NaturallySpeaking microphone and returns control to VoiceDirect. Then, 
say "Close" (the button name, which VoiceDirect tracks) and then say 
"Switch to NaturallySpeaking" again.

Or, you can simply deactivate the Tip of the Day by clearing the 
checkbox in the Tip of the Day dialogue box.

o	By default, both Dragon NaturallySpeaking and VoiceDirect 
use the numeric plus ( + ) key to toggle the microphone and the 
numeric minus ( - ) key to toggle the Choice List. When both 
programs are running, whichever program started later controls 
the hot key. As a workaround, set the Dragon NaturallySpeaking 
and VoiceDirect hot keys to be different from each other.

VoiceDirect: compatibility with DragonXTools 1.0
o	VoiceDirect does not support applications that are 
speech-enabled with DragonXTools 1.0. 

VoiceDirect: tracking Microsoft Office 97 applications
o	If VoiceDirect is not tracking Office 97 menus, it may be 
because you did not specify Office 97 compatibility during Setup. 
Go back to Setup and do so. Microsoft's Active Accessibility tool 
is integrated into VoiceDirect, so that VoiceDirect can track Office 
97 menus. 

Also, because Microsoft's Active Accessibility is not supported on 
NT 4.0, VoiceDirect does not track Office 97 menus on NT 4.0.

VoiceDirect: Audio Setup Wizard
o	You cannot use the pages of the wizard that output sound 
hands-free. However, you can use the pages that contain only text 
hands-free.

VoiceDirect: Hot Keys
o	For some applications running under Windows NT and Windows 95, 
the VoiceDirect hot keys do not work if the mouse pointer is on the 
application's toolbar. For example, if the mouse pointer is on the 
toolbar in WordPerfect and  you press the "+" key on the numeric 
keypad, a plus sign is inserted into your document. The VoiceDirect 
microphone does not  toggle on or off, as it should.

Also, the "+" key does not  work in a DOS box in Windows 95.

VoiceDirect: Word History and Choice List
o	If you say "Oops" to bring up the Word History to correct a 
recognition error, then you correct the error and close the Word 
History window, sometimes the corrected text does not appear in your 
document. As a workaround, select and delete the incorrect text, 
then type or dictate the correct text. Also, you can obtain a file 
called REPLACE2.DDX from Technical Support as listed above or at 
http://www.imsisoft.com/voicedirect/index.html to augment the workaround.

o	If you correct a misrecognition in the Word History and the 
correction does not appear in your document, you may need to change 
the rate at which VoiceDirect sends keystrokes and mouse clicks for 
the application in which you are working. Go to the Voice Menu, 
Options, Compatibility tab, select the application in which you are 
working, click the Options button, move the Input Speed slider 
toward "slower" and click OK. 

o	After correcting a mistake using the Choice List or the 
Word History, VoiceDirect does not  always undo the misunderstood 
word or macro and replace it with the corrected word or action. 
VoiceDirect uses the following rules when deciding whether to undo 
and redo actions after a correction: 

1.	VoiceDirect does not undo or redo commands in Command Mode.
2.	In general, VoiceDirect does not undo or redo macros, except 
for certain built-in macros (such as, Begin Capitalise, No Space 
and Go to Sleep) and macros that type only alphanumeric characters.
3.	If you correct a word in the Word History that was spoken 
before a macro was executed, VoiceDirect will not undo and redo that word.
4.	VoiceDirect does not undo or redo if the active window has 
changed or the focus has moved to a different field since the 
misunderstood word was spoken.

o	With the Choice List's default settings, sometimes the 
Choice List covers a word you need to see or correct in the Word 
History. To fix this, move the Word History out of the way and click 
the tiny box in the upper left corner of the Word History. From the 
Control menu, select Remember Position.

o	In Windows 3.x, when the Choice List is active but not in 
Spell Mode, Alt+Tab is disabled. Press Esc to clear the Choice List 
before using Alt+Tab to change the active window. (You do not need 
to do this in Windows 95 or NT 4.0.)

o	During dictation, the Choice List intercepts keystrokes 
only if the Choice List is visible. If you start typing before 
the Choice List appears, your keystrokes go into your application. 
Similarly, Spell Mode and the Choose commands are only active if 
the Choice List is visible. To make the Choice List appear sooner, 
change the Pop-up Delay in the Dictation tab of the Options dialogue box.

o	When the Choice List is not in Spell Mode, you cannot 
correct a misunderstood word as a Choice List command (for example, 
correct "chooses" to be "[Choose 6]"). However, you can correct a 
misunderstood word as a Choice List dictation word (for example, 
correct "Choose 6" to be "chooses"). Also, when the Choice List is 
in Spell Mode or you are using the Word History, you can correct 
any misunderstood word that does not close the Choice List or the 
Word History by saying "Oops" again (to display a second Word History).

o	Sometimes the words in the Choice List are not quite what 
you said, but you find that as soon as you start to type or spell 
the words they appear in the Choice List. If this happens frequently, 
lengthen the time VoiceDirect takes to recognise what you say, thus 
giving it a bit more time for correct recognition. To do this, move 
the Computation Level slider (in the Recognition Tab of the Options 
dialogue box) to the right, toward "fewer errors". Although this 
slows VoiceDirect's performance a bit, it significantly improves recognition accuracy.

VoiceDirect: Vocabulary Manager
o	If you accidentally delete a vocabulary file, you can get it 
back by: (a) quitting VoiceDirect without saving your user files, 
then restarting VoiceDirect; (b) reverting to the last saved version 
of VoiceDirect. To do this, from the Voice Menu, select Users and in 
the Users dialogue box select Restore User. Select Go Back to Last 
Saved Version and click OK.

VoiceDirect: Mouse and Keyboard Emulation
o	You cannot activate the Scroll Lock key by speaking. Also, 
you cannot use the Scroll Lock key in a speech macro. 

o	When you move the mouse pointer to the title bar of another 
window and say one of the drag commands, the window becomes active 
but does not move as directed. Repeat the drag command to start dragging 
the window.

o	When you move or size a window, Windows does not  redraw the 
screen until you are done. Therefore, the microphone volume metre 
does not reflect any sounds it hears and the Voicebar does not display 
words, but VoiceDirect is still listening and performing the spoken 
actions. When you stop moving or sizing the window (by saying "Cancel" 
or "Enter Key"), normal behaviour returns.

VoiceDirect: Importing Macros
o	After you import a large group of words into a vocabulary in 
the Vocabulary Manager, there may be a long delay (how long of a delay
 depends on the speed of your computer) while VoiceDirect incorporates 
the new words. During this delay, VoiceDirect turns off the microphone. 

VoiceDirect: Capture Keystrokes Dialogue Box
o	The Capture Keystrokes dialogue box, available from the Add 
Word and Modify Word dialogue box, does not capture the Ctrl+Esc key 
combination. If you want to create a macro that includes Ctrl+Esc, 
type or spell {Ctrl+Esc} in the Resulting Action box using the 
alpha-bravo words.

VoiceDirect: Exiting
o	IMSI recommends that you close VoiceDirect before exiting 
Windows 3.x.

VoiceDirect: Microphone Testing
o	In Windows 3.x, the VoiceDirect microphone testing procedure 
may not detect that the microphone is not properly plugged in if, 
as far as VoiceDirect is concerned, you have a "noisy" system.

o	If multiple users who require different microphone settings 
use the same VoiceDirect system, VoiceDirect does not restore each 
user's proper microphone setting when users switch. Instead, only 
the previous user's setting is restored. This means that all other 
users must recalibrate the microphone using the microphone test or 
the Audio Setup Wizard.

Other Dragon Products
o	Do not run VoiceDirect concurrently with other Dragon 
speech-recognition products, except for Dragon NaturallySpeaking. 
Likewise, do not run two different language versions of VoiceDirect 
concurrently. However, different Dragon products can coexist on the 
same computer and be run separately.

o	You can use VoiceDirect with any of the DragonPro Series 
products, such as DragonLaw (specialised language module for legal 
professionals) and DragonMed (specialised language module for 
health care professionals).

Online Help
o	When using Help in any Windows application, it is not 
possible to say the name of a hotspot to select it. Instead, 
say "Tab key" or "Topic 1", "Topic 2", and so on to move to a 
hotspot, then say "Enter key".

Novell GroupWise
o	The GroupWise dialogue box that prompts for the user 
ID causes VoiceDirect to stop responding. As a workaround, you 
can add the "/@U-USER ID" switch to the command line that starts 
GroupWise, so that you are not prompted for your ID. You may also 
need to add the "/LA-NETWORKID" switch. Refer to the GroupWise 
documentation for details.

Windows 95 Start Menu
o	If you are using any Windows 95 shell replacements or 
extenders (for example, if you have Norton Navigator loaded 
and are using any of the "Norton QuickMenus" [Windows Start menu 
add-ons], or Microsoft Power Toys), VoiceDirect will not track 
the Start menu correctly, so you cannot say the names of Start 
menu commands.

As a workaround, select Start menu, Settings, Taskbar, Start 
Menu Programs, Advanced. Then delete Find. This fixes the tracking 
problem.

Windows Program Manager Replacements
o	If you are using an alternative Windows shell, such as 
PCTools Desktop, you have to go to the Start Up tab of the Options 
dialogue box and clear the Name of Bring-Up Group field to use the 
Bring Up command without getting an error message. You can start 
applications by using the Bring Up command if you add macros for 
those particular applications to the Global or Always Active groups 
in the System vocabulary. Use the AppBringUp scripting command in 
your macros. (For other scripting commands that you can use in macros, 
refer to the macro language online Help.)

Windows Screen Savers
o	In Windows 95 and Windows 3.x, VoiceDirect automatically 
clears an active screen saver when you speak or toggle the microphone. 
However, it may not clear some screen savers if you press the minus key 
to display the Word History while the screen saver is active. If the 
Word History displays on top of your screen saver, you can press the 
Esc key to clear your screen saver and then the minus key again to 
reactivate the Word History.

o	VoiceDirect clears an active screen saver by simulating a 
small mouse move if it has been 30 seconds since the last time you 
spoke or pressed a keyboard key. If you do not use a screen saver 
and do not want VoiceDirect to move the mouse every 30 seconds, or 
if you discover that this mouse move is interfering with one of your 
applications, you can disable this feature by adding the following 
line to the DDWIN.INI file in your IMSI\DDWIN directory.

		[UserName's Options]	<- look for this line
		Internal: Cancel Screen Saver=0	<- add this line below it

	In this example, UserName is the name of the user. The 
[UserName's Options] section heading already exists. You should 
add the "Cancel Screen Saver" line after this section heading.

Tracking Toolbars 
o	VoiceDirect does not track floating toolbars in any 
application because a toolbar is not anchored. As a workaround, 
click anywhere in the toolbar. This gives the toolbar the focus, 
which anchors it and therefore allows tracking.

Windows NT
o	VoiceDirect may be slow to respond to some speech commands 
with some applications.

o	VoiceDirect sometimes responds very slowly when you use the 
Mouse Movement Commands when trying to drag a window, such as the 
Voicebar, around the screen. For example, when you say "Stop", the 
time between when you said the command and when the window actually 
stops moving may be long.

o	For Windows NT compatibility information, refer to the above 
section of this Readme called "For Windows NT Users".

WordPerfect 6.1, 7.0 and  8.0
o	The WordPerfect macros supplied with VoiceDirect were 
designed for WordPerfect 6.1, 7.0 and 8.0. If you are using another 
version of WordPerfect you may have to change the keystrokes 
generated by some of the macros.

o	WordPerfect 6.0 keyboard macros may not function properly. 
If you experience a problem, select the CUI (Common User Interface) 
and not the WPDOS compatible keyboard.

o	Some of the menus that appear when you click the right mouse 
button are not visible to VoiceDirect. Commands to control those 
menus are not created automatically. You can still control these 
menus by using key names (down arrow, enter key, alpha, bravo, 
and so on).

o	Some of the coaches do not respond to keyboard or speech 
commands.

o	WordPerfect frequently uses feature bars. VoiceDirect 
can track most of the buttons on these feature bars. However, 
VoiceDirect cannot track many of the buttons that contain drop 
lists or editable fields. You can use the Feature Bar command 
to access any button or field on any feature bar. For example, 
if you use the outline feature and need to access the Options 
button, say "Feature Bar" and then choose Options from the drop list.

o	While in Dictate Mode in WordPerfect 7, if you put the 
cursor between two words and say a command that is misrecognised as a 
dictation word, which you then correct to be the command, VoiceDirect 
inserts an extra backspace when deleting the dictation word. As a 
workaround, disable the WordPerfect 7 "smart" correction feature. Choose 
QuickCorrect from the Tools menu. Click Options, then clear the "Double 
space to single space" checkbox.  

WordPerfect Draw
o	When dragging the mouse or drawing lines in WordPerfect Draw, 
VoiceDirect cannot run. Therefore, VoiceDirect's mouse dragging 
operations are not available in WordPerfect Draw.

Microsoft Excel
o	In Excel 5.0, you cannot use the Quick Preview feature 
(available from the Help menu) by speaking. You must use the mouse.

o	Before entering text into a cell, add Excel-specific 
[Dictate Mode] 
and [Type Word] macros, which send the F2 keystroke (which puts the 
edit cursor in the cell) after putting you in Dictate Mode. If you 
do not do this, VoiceDirect may not transfer corrections you make 
with the Word History to the cell.  

Microsoft Office 97
o	To track Microsoft Office 97 menus, VoiceDirect uses 
Microsoft's Active Accessibility API (application programming 
interface), which you are prompted to select during installation. 
Currently, the API is available only in US Windows 95. Microsoft 
may release other language versions of the API in the future and 
they plan to include the API in all languages in all future 
versions of Windows. If the VoiceDirect installation notifies you 
that it cannot install the API, you can contact Microsoft to 
determine whether a downloadable version of the API (which you 
would install yourself) is available for your version of Windows. 
If so, you must add the following line to the [Defaults] section 
of your DDWIN.INI file to enable Office 97 tracking: 

Compatibility: MSAA=1

Microsoft Word
o	In Word 6.0 and 7.0, you cannot use the WordPerfect User 
features if you want to use VoiceDirect's command-and-control feature. 
To turn off these features, open the Options dialogue box from the 
Tools menu and select the General tab. Then be sure Help for 
WordPerfect Users and Navigation Keys for WordPerfect Users are not selected.

o	The Word macros supplied with VoiceDirect were designed for 
Word 6.0, 7.0 and Word 97 (if you specified Office 97 support 
during Setup). If you are using another version of Word you may 
have to change the keystrokes that some of the macros generate.

o	VoiceDirect cannot read words such as "Close" on the Print 
Preview toolbar, but you can make a macro for this action.

o	There is no speech command to exit Annotations in the Insert menu. 

o	In Word 7.0, VoiceDirect does not  track the Drop Cap 
dialogue box. Therefore, you cannot close this dialogue box by 
saying "OK" or "Cancel". Instead, you must say "Escape" or "Close Window".

Microsoft WordPad
o	Dragging the mouse by speaking does not highlight text in 
WordPad.

Microsoft Paintbrush (Windows 3.x) and Microsoft Paint (Windows 95)
o	VoiceDirect does not perform mouse dragging operations 
in either application. Therefore, VoiceDirect's mouse dragging 
operations are not available in either one.

Microsoft PowerPoint
o	VoiceDirect does not perform mouse dragging operations in PowerPoint. 
Therefore, VoiceDirect's mouse dragging operations are not available in PowerPoint.

Lotus 1-2-3
o	In Lotus 1-2-3, it is not possible to select a menu item while 
you are editing a cell. You must finish editing the cell (by saying 
"Cell OK" or "Cell Cancel") before you can say the name of a menu item.

o	When you drag an object outside the Lotus application window 
you can no longer control the mouse movement by speaking. Use the 
mouse to regain control of the mouse movement.

o	If you have a dialogue box on the screen and  then select a 
group of cells (by moving the mouse over the spreadsheet and saying 
"Drag Down", for example), VoiceDirect exits drag mode as soon as 
the application is activated. You can avoid this by saying "Button Click" first to activate the application and  then saying "Drag Down", or by using a Select command, such as "Select 2 by 3 Block".

o	There are no tracking commands for Range -> Version -> Version Manager.

Lotus Word Pro 96
o	When using the VoiceDirect Select command, be sure the 
insertion point is at the beginning of the word. Also be sure 
that all selections are cleared before you use another Select command.

o	Although Word Pro does not insert blank lines between 
paragraphs by default, you may want to insert them yourself. 
Note, however, that VoiceDirect does not track blank lines.

o	You cannot run the Word Pro guided tour at the same
 time VoiceDirect is running. If you do, a message appears 
asking you to close Lotus ScreenCam first, which, in this case,
 is actually asking you to close VoiceDirect.

o	You cannot use the Word Pro tutorial by speaking.

cc:Mail
o	The cc:Mail macros supplied with VoiceDirect were designed 
for cc:Mail 2.01. If you are using a different version of cc:Mail 
you may have to change the keystrokes used by some of the macros.

o	In cc:Mail 1.0, use the Choice List instead of the Word 
History to make corrections. You can correct misrecognitions 
using the Word History, but VoiceDirect cannot properly correct 
the text in this application.

o	In cc:Mail 2.0, set the "Start Prepare in Text Editor" 
option in the Prepare section of the User Setup dialogue box 
(accessible from the Tools menu). This ensures that, when 
you dictate the body of a message to send, correction is 
possible by using the Word History.

Sound Blaster Sound Card (Creative Labs)
o	If you are using Windows 3.x with a Sound Blaster 
adapter and the Creative Labs Mixer, you must activate the 
"Save Settings on Exit" Mixer option before you create a 
VoiceDirect user. Otherwise, your microphone settings will 
be reset to the Mixer installation default values each time 
you start Windows (which then means that you must run the 
microphone test again).

MS-DOS Applications
o	To use VoiceDirect and DOS applications you must run 
the DOS application in a DOS window (not full screen). There 
are, however, known problems with running DOS applications in 
a window: hot keys do not work as long as the DOS application 
is active and you cannot type in the Choice List unless you are 
in Spell Mode.

o	For an application running in a DOS window, the vocabulary 
name that VoiceDirect uses is the caption of the DOS window, 
rather than the application name. The caption for the DOS 
window is usually the same as the caption on the MS-DOS icon 
in the Program Manager. To use different vocabularies with 
different DOS applications, you can create separate icons in 
the Program Manager for every application that you run in a 
DOS window.

o	Some DOS applications cannot keep up with the rate at 
which VoiceDirect types and corrects and therefore cannot be 
used with VoiceDirect.

Adobe Acrobat Reader
o	The speech commands that you can use with the online  
VoiceDirect User Guide are specific to that guide. The 
commands do not work with other documents that you may 
read with Acrobat Reader.

Schedule+ (Microsoft Office for Windows 95)
o	Because Schedule+ does not yet follow Windows 
programming standards, it is not compatible with VoiceDirect, 
even though it is part of the Dragon-supported Microsoft 
Office for Windows 95 suite.

Prodigy
o	In Prodigy, all non-Prodigy activity is suspended 
when a menu is open, so it is not possible to say menu 
commands in Prodigy. Use the mouse or keyboard to complete menu operations.

McAfee Scan95
o	You cannot start McAfee Scan95 once VoiceDirect is 
running. To use this program with VoiceDirect, start McAfee 
first, then start VoiceDirect.

WinCim (CompuServe)
o	Although the WinCim services have accelerator 
key labels on them, you cannot select them by speaking 
or by pressing the accelerator keys.

Tetris
o	If you use Tetris from the Microsoft Windows 
Entertainment Package, note that its menu formatting does 
not follow standard Windows conventions. When you see a 
Tetris menu that includes both a command and a key, such as 
"Open Enter", VoiceDirect expects you to say "Open Enter", 
rather than just "Open", as you would in other Windows applications.

OS/2
o	VoiceDirect does not run under OS/2.

Star Trek: Klingon 
o	Installing the Star Trek: Klingon CD-ROM after 
VoiceDirect causes a conflict with the DRAGON.INI file in your 
Windows directory because both programs use the same .INI file
and install by default in the Windows directory. There are 
two workarounds: (1) Before you install Klingon, you can rename 
your VoiceDirect DRAGON.INI file, install Klingon, then
copy the renamed file back to overwrite Klingon's DRAGON.INI file.
VoiceDirect's DRAGON.INI file is a superset of Klingon's DRAGON.INI 
file. (2) If you overwrote your DRAGON.INI file during your installation 
of Klingon, you can edit your DRAGON.INI file for VoiceDirect so 
that it contains these lines:

[HARDWARE]
DRAGDEV=DRAGMEDI.DLL

[Installed]
DDWin1=c:\ddwin,409  (Note: This pathname must indicate where you 
chose to install VoiceDirect; C:\IMSI\DDWIN is the default.)

Documentation Errata

A note about the documentation in general: if you are using Windows NT 4.0, 
follow any instructions that pertain to Windows 95. Also, any references to 
text-to-speech do not apply to this version of VoiceDirect.

A note about the User Guide and tutorial, in general: because the Adapt
 Only on Correction checkbox in the Dictation tab of the Options dialogue 
box is now selected by default, the User Guide and tutorial are incorrect 
in stating that you must correct every recognition error or else 
recognition accuracy will worsen. Rather, recognition accuracy does not 
change if you do not correct errors.

The following information is missing from the VoiceDirect documentation:

Active Vocabularies and Recognition
VoiceDirect recognises from competing active vocabularies according to 
priority. For example, if you create a Global Command called "[Print]" 
and a Microsoft Word command called "[Print]" and then you say "print" 
in Dictate Mode, which does VoiceDirect recognise? Read on for an explanation.

Dictate Mode Active Vocabularies
In Dictate Mode, VoiceDirect recognises from the following vocabularies, 
in order of priority. That is, if identical words are in several of these 
groups, VoiceDirect recognises the word from the first group on this 
list that has a match and then lists other matching words in the Choice List. 

1. The current application's active vocabulary(s) [unless the command 
is already set to not appear as the first choice in Dictate Mode, 
because the Do Not Make Word the First Choice checkbox is selected 
in the Properties tab of the Advanced Modify Word dialogue box]
2. The Dictation vocabulary
3. The Always Active vocabulary
4. The Global Commands vocabulary

VoiceDirect disables Tracking groups and Sentence Commands in 
Dictate Mode.

Command Mode Active Vocabularies
In Command Mode, VoiceDirect recognises from the following groups, 
in order of priority.

1. Discrete commands in the current application's active vocabulary(s)
2. The Tracking vocabulary group for the active window
3. The Always Active vocabulary
4. Discrete commands in the Global Commands vocabulary
5. Complete Sentence Commands in the current application's 
active vocabulary(s)
6. Complete Sentence Commands in the Global Commands vocabulary
7. Partial Sentence Commands in the Home vocabulary for the 
active application
8. Partial Sentence Commands in the Global Commands vocabulary

A command is a partial Sentence Command if you pause in the 
middle of it, for example, if you say "Select Next" in WordPad 
and pause before you say "Word". You can complete the Sentence 
Command unless the Sentence Completion Timeout slider on the 
Command tab of the Options menu is set to "start over" (the 
default setting). With this setting, VoiceDirect does not  recognise 
partial sentences.

During certain special modes, including Mouse Movement Mode, 
Arrow Movement Mode, MouseGrid Mode, Bring Up Mode, Enter Letters 
Mode, Zip Code Mode and Phone Number Mode, VoiceDirect deactivates 
the active application's vocabulary and global Commands vocabulary 
and activates mode-specific vocabularies.

Tracking Mode Active Vocabularies
VoiceDirect enters Tracking Mode whenever an application's 
menu bar is highlighted or a pull-down menu is active. In Tracking 
Mode, VoiceDirect recognises from the following groups, in order of 
priority.

1. The Tracking vocabulary for the active window
2. The Always Active vocabulary
3. Discrete commands in the Global Commands vocabulary
4. Complete Sentence Commands in the Global Commands vocabulary
5. Partial Sentence Commands in the Global Commands vocabulary 
(if the Sentence Completion Timeout slider is not set to "start over")

Application Compatibility Options
In the "Changing Compatibility Options" section on page 10-13 of 
the User Guide, the screen capture should have the following check 
box: "Allow Dictation Correction (when Focus changes)". Also, the 
table that follows that screen capture should have the following 
definition of the "Allow Dictation Correction" check box: "Lets 
VoiceDirect remember where it left off when you switch focus from 
the application you are dictating into to another application, then back again".

VoiceDirect's VoiceDirect User Guide
Page 9-6 of the User Guide says that you can use the Next Pane 
command to move between panes in the Vocabulary Manager. This is 
wrong. You must use the Tab Key command.

Also in the User Guide, page 9-18 needs a bit of clarification 
in the "Deleting Words" section. If you use the Find Word dialogue 
box to select a word you want to delete, a VoiceDirect Message box 
appears asking you to confirm your request to delete the word. If 
you answer "yes", the word is deleted. If, however, you use the 
Vocabulary Manager to select a word you want to delete, the 
instructions in the User Guide are correct. 

It should also be documented in the User Guide that you cannot 
dictate continuous phrases for more than 10 seconds without pausing. 

In the Recognition tab of the Options dialogue box, a new checkbox, 
"Generate Pronunciations For New Words", appears. If this checkbox 
is checked, new words that you add to VoiceDirect are automatically 
given a phonetic pronunciation so that the words adapt to your 
speech and can be used in continuous phrases and commands. If the 
checkbox is not checked, you must train each new word that you add 
to VoiceDirect. It is checked by default.

