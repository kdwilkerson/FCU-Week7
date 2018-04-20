# Week 7 Project: WordPress vs. Kali
Time spent: 5 hours spent in total
 
> Objective: Find, analyze, recreate, and document 3 vulnerabilities affecting an old version of WordPress
 
## PENTESTING REPORT
 
1. XSS
	 - [ ] Summary: 
		The following is a vulnerability that allows anyone to run XSS on a WordPress site by via a post. 
	 -Tested in version: 4.5.3
	 -Fixed in version:  4.6.1
	 - [ ] GIF Walkthrough: 
   <img src="https://imgur.com/QSC5jzl.gif"></br>
 
2. XSS
	- [ ] Summary: 
		If a wordpress admin is tricked into attempting to load a bogus media file exceeding maximum allowed file size through upload.php, a carefully crafted file name will allow the execution of cross site scripting. 
	  -Tested in version: 4.5.3
	  -Fixed in version:  4.5.7
	  - [ ] GIF Walkthrough: 
    <img src="https://imgur.com/6ciYOTk.gif"></br>
	 
3. User Enumeration
	 - [ ] Summary: 
		The following is a vulnerability that allows anyone the ability to enumerate a list of valid user names on a WordPress site. 
	  -Tested in version: 4.2
	  - [ ] GIF Walkthrough: 
   <img src="https://imgur.com/ocnWbEG.gif"></br>
	 
## Notes
 
	I couldn't get any of the xss to work in Wordpress 4.5.3 prior I had 4.2 installed for all assignments.
 
## License
 
    Copyright [2018] [KD Wilkerson]
 
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
 
        http://www.apache.org/licenses/LICENSE-2.0
 
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
