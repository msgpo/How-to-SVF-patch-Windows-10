### How-To SVF patch Windows

The idea of SVF patching is that it creates a single ISO file to include only the differences between two ISO images. This allows you to avoid downloading another ISO which consumes bandwith & your free time. The method works for all Windows Version 7 up to Windows 10. The procedure is always the same.

### Requirements

* [SVF eXtractor](https://www.softpedia.com/get/System/Back-Up-and-Recovery/SVF-eXtractor.shtml) (_svfx_2.1.11.exe_)
* Download the Business image: en_windows_10_business_editions_version_1903_x64_dvd_37200948.iso _example_
* Download the SVF patch: en_windows_10_consumer_editions_version_1903_x64_dvd_b980e68c.svf _example_
* A patch repository e.g. Build 18362.30 [SVF Repository](https://cloud.mail.ru/public/2Rwo/51AwfJ6Wp)
* (_optional_) [Windows and Office Genuine ISO Verifier](https://genuineisoverifier.weebly.com/)


### Tutorial 

Place all 3 files into the same folder and run "svfx_2.1.11.exe" with administrator privileges.

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/1.png)


Make sure that the file name in the tool is identical to the ISO name you downloaded, if that#s not the case, rename it!

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/2.png)


Click the "Path" icon to load the Business image (in our example: `en_windows_10_business_editions_version_1903_x64_dvd_37200948.iso`).

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/3.png)


If the path is not automatically detected, select the ISO image and then click "Open".

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/4.png)


Once all files are loaded click "Extract".

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/5.png)


Wait a little bit until the extraction process is finished.

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/6.png)


When all is finished you will receive a message similar like this:

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/7.png)


Close the tool & will find the new ISO created in the same directory

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/8.png)


Check with Windows and Office Genuine ISO Verifier if your newly created image is a valid MSDN file.

![alt text](https://raw.githubusercontent.com/CHEF-KOCH/How-to-SVF-patch-Windows-10/master/Screenshots/9.png)


### Credits
* GezoeSloog for his SVF Repository
* MDL Forums (_I guess they created the idea first_)
