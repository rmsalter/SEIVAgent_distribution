## SEIVAgent Distribution
This application is described in *Getz, et. al, Adaptive vaccination may be needed to extirpate COVID-19: results from a runtime-alterable strain-drift and waning-immunity model*. The current version is 1.069 beta. To install and run:
* To run this under **MacOS**, download and unzip the [zip](https://github.com/rmsalter/SEIVAgent_distribution/releases/download/1.069_beta/SEIVAgent_1.069beta.zip) file.
* Launch the application **SEIVAgent-1069**
* On first launch you will probably get an error message regarding security: i.e., "Move to Trash" or "Cancel". Press "Cancel" and then right click on the app and choose "Open."  This should work.  However, if there is no way to launch the application:
  * Open System Preferences / Security & Privacy and click on General.
  * Click on "Allow Anyway" to unblock "jdk1.8.0_202.jdk". This package is a Java runtime and has been verified as malware free.
  * Any security queries regarding keystrokes can be denied.
* Before inititating a simulation either select the various parameter values for the run or do the following: 
  * Press the "Open settings" button at the top left-hand side of the application and in the downloaded "SEIVagent_version" folder select the file "BasicParameters.xml."
  * Press the "Open path set" button in the middle of the application and in the downloaded "SEIVagent_version" folder select the file "PathogenParameters.xml."
* Now go to the bottom right-hand corner next to the "Run" button, insert the number of steps for the simulation, and press the "Run" button to initiate the run.
* If you want to run our JavaScript adaptive vaccination driver, then go to the "JS" button, second from the left at the bottom of the app and press it to open the JS window.  Now press the "Open Script" button at the top (in the middle) of this window and select the "vaccadjust.js" file to open this script.  Then press the "Load Script" button at the bottome right-hand corner of the JS window, then press the "Go" button at the bottom middle of this window.  Pressing the "Stop" button will act to stop the run and reset it to the starting point at step (time) 0.
## We hope to have a version that runs on **WINDOWS** machines sometime soon
