# bimanual-motor-online-task

The repository contains the tasks scripts for the task described in full in our accompanying paper:

Schoenfeld MJ, Thom J, Williams J, Stagg CJ, Zich C (accepted) _Relationship between skill training and skill transfer through the example of bimanual motor learning_ European Journal of Neuroscience. DOI: 10.1111/ejn.16194.

<br />

The raw data is available at https://data.mrc.ox.ac.uk/bimanual-motor-task and has DOI: 10.5287/ora-jne9aa1z0. <br />
The code for the experimental paradigm is available at: https://github.com/cathazi/bimanual-motor-online-task.

<br />
<br />

**Getting started**

In order to run the script, you need to download PsychoPy builder (https://www.psychopy.org/). Further, you need an account with Pavlovia.org (https://pavlovia.org/) and link it to your PsychoPy builder (https://www.psychopy.org/online/usingPavlovia.html). Once this is established, you can open the script for the experimental task ‘bim_14102020.psychexp’ and synchronise it by pressing ‘sync’ (https://www.psychopy.org/online/fromBuilder.html). This will automatically create a project on Pavlovia and their associated Gitlab page. On Pavlovia, set your project to ‘running’ and you can start testing (https://pavlovia.org/docs/experiments/piloting-running).  

<br />
<br />
 
**How to change conditions**

1. Open Psychopy builder
2. Open the script for the experimental task ‘bim_14102020.psychexp’
3. Go to ‘set_each_block’ and double click it (a dialogue window will open)
4. Go to tab ‘begin_routine’
5. Find the line ‘condInfo’ and change it to a number between 1 and 15 which corresponds to the number of conditions. If you cannot type in the text box, set ‘code type’ to ‘both’ at the top of the dialogue window.
6. Press ‘OK’
7. Save the changes and press ‘Sync’.

Note, that you might have to clear your cached web content or browser cache to see the changes online. In order to clear browser cache, use Ctrl-F5, Ctrl-Shift-R or equivalent. You can also go to your browser settings and to privacy and security settings. For most browsers, you find a section for cookies and site data to clear. See further information for trouble shooting here: https://www.psychopy.org/online/psychoJSCodingDebugging.html
