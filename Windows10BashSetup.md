# Windows 10 Bash Setup

**Installing the Linux Bash Sub-system**
**1) Enable Developer Mode**
  
  * Go to `Settings` and click on `Update & Security`
  * Click on `For Developers`
  * Select `Developer Mode`
  * Now run updates

**2) Enable Linux Bash beta Feature**

  * Go to `Programs and Features`
  * Click `Turn Windows Features on or off`
  * Check `Windows Subsystem for Linux (Beta)`
  * Run updates 
  * Once all updates are finished search for `Bash on Ubuntu on Windows` and start the up
  * Follow setup instructions
  * Once setup update with `sudo apt-get update` and then `sudo apt-get upgrade`

**3) Windows Insider Preview (recommended)**

  * This is recommended because the insider preview provides the most up to date version of Windows 10 Bash. This fixes many problems you can experience with Windows 10 Bash and makes it much easier to use. 

  * Go to `Settings`
  * Click on `Windows Update`
  * Click `Advanced options`
  * Under `Get Insider Preview builds` click `Get Started`
  * Follow on screen prompts
  * After restart run updates again
  * Make sure there are no new updates

**4) Recommended Packages**
 
 * The following packages have been found to make use of the bash shell a lot easier or fix potential problems.

 * `sudo apt-get install realpath` 
