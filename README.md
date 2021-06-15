## SEIVAgent Distribution
This application is described in *Getz, et. al, Adaptive vaccination may be needed to extirpate COVID-19: results from a runtime-alterable strain-drift and waning-immunity model*. The current version is 1.071 beta. It installs with its own Java runtime (JRE 8_202).
To install and run under **MacOS**:
* Download and unzip the [zip](https://github.com/rmsalter/SEIVAgent_distribution/releases/download/SEIVAgent_v1.071beta_macosx/SEIVAgent1.071macosx.zip) file. The unzipped file will create a folder called *SEIVAgentv1.071macosx*.
* Create or choose a folder as your working folder for this project.
* Double-click on *SEIVAGENT-1.071.dmg* to mount and open the disk image containing the application. You must first accept the end user license agreement.
* Drag the *SEIVAgent* icon to the working folder.
* Drag the rest of the contents of the *SEIVAgentv1.071macosx* folder to the working folder.
* Launch the *SEIVAgent* application. The first time you launch do so by right-clicking the icon and select *Open*. You may see a warning message with an Open override. Select the Open override. Subsequent launches will only require a double-click. If this doesn't work:
  * Open System Preferences / Security & Privacy and click on General.
  * Click on "Allow Anyway" to unblock the launch. This package contains a Java runtime and has been verified as malware free.
  * Any security queries regarding keystrokes can be denied.
* Before inititating a simulation either select the various parameter values for the run or do the following: 
  * Press the "Open settings" button at the top left-hand side of the application and in the downloaded "SEIVagent_version" folder select the file "BasicParameters.xml."
  * Press the "Open path set" button in the middle of the application and in the downloaded "SEIVagent_version" folder select the file "PathogenParameters.xml."
* Now go to the bottom right-hand corner next to the "Run" button, insert the number of steps for the simulation, and press the "Run" button to initiate the run.
* If you want to run our JavaScript adaptive vaccination driver, then go to the "JS" button, second from the left at the bottom of the app and press it to open the JS window.  Now press the "Open Script" button at the top (in the middle) of this window and select the "vaccadjust.js" file to open this script.  Then press the "Load Script" button at the bottome right-hand corner of the JS window, then press the "Go" button at the bottom middle of this window.  Pressing the "Stop" button will act to stop the run and reset it to the starting point at step (time) 0.

We hope to have a version that runs on **WINDOWS** machines sometime soon

**Using the R example**
* Install the package contained in *seiv_0.2.0.tar.gz* as a source package into your R platform.
* Install any uninstalled dependencies (ggplot2, reshape).
* In R or R Studio, open and load the program *Rdemo.R*.
* Invoke the program form the command line using **go(run=10, sampleSize=165)**
