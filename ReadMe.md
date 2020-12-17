# Solarwinds Vulnerablity Info
Repository with all the Solarwinds Vulnerability information I've been tracking and using for communications, review, and technical understanding.

It's devided into four sections: News Reports, Public Information / Alerts, Technical Analysis, Additional IOCs, and Unsubstantiated Conspiracy, FUD, or Selective Manipulation of Information. There is some overlap where a few links may be a long for technical analysis, but may also include IOCs. Others may be advisories that also qualify as news. 

This is all public information and is provided freely for use. 

Previously I was tracking all of this in a Twitter thread located here: https://twitter.com/EanMeyer/status/1338324466808590345?s=20

I will post this GitHub repo to that Twitter thread and ongoing updates will be here.


<h2>News Reports</h2>

<b>SolarWinds Advisory</b>
https://www.solarwinds.com/securityadvisory

<b>KrebsOnSecurity - US Treasury Breach and Solarwinds </b>
https://krebsonsecurity.com/2020/12/u-s-treasury-commerce-depts-hacked-through-solarwinds-compromise/

<b>KrebsOnSecurity - Solarwinds Breach Effects 18k Customers, Microsoft takes control of domains</b> 
https://krebsonsecurity.com/2020/12/solarwinds-hack-could-affect-18k-customers/

<b>Washington Post ties Solarwinds breach to all recent major breaches</b> https://www.washingtonpost.com/national-security/russian-government-spies-are-behind-a-broad-hacking-campaign-that-has-breached-us-agencies-and-a-top-cyber-firm/2020/12/13/d5a53b88-3d7d-11eb-9453-fc36ba051781_story.html

<b>ZDNet reporting on Solarwinds 8K filing </b>
https://www.zdnet.com/article/sec-filings-solarwinds-says-18000-customers-are-impacted-by-recent-hack/

<b>Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"</b>
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

<b>Microsofts role in recent high profile breaches called into question as O365 MFA bypass looked at as intial compromise channel</b> 
https://www.crn.com/news/security/microsoft-s-role-in-solarwinds-breach-comes-under-scrutiny?itc=refresh

<b>TheHackerNews reports on Reversing Labs analysis showing the flaw was likely introduced by a compromised build pipeline</b>
https://thehackernews.com/2020/12/new-evidence-suggests-solarwinds.html

<b>Washington Post reports $280 million in Solarwinds stock was traded days before breach announcement</b>
https://twitter.com/washingtonpost/status/1339059943442419714?s=20

<b>KrebsOnSecurity reports domain takeover of malicious C2 now, in some cases, includes a kill switch</b>
https://krebsonsecurity.com/2020/12/malicious-domain-in-solarwinds-hack-turned-into-killswitch/


<h2> Unsubstantiated Conspiracy, FUD, or Selective Manipulation of Information</h2>

This section was added to help address questions that arise during meetings, etc., from individual with potentially different news sources. This section includes items that are determined to be false or misleading. Hopefully this helps address comments in organizations before they become difficult to remove from internal conversations. 

<b>Gateway Pundit claims there was a raid on Solarwinds headquarters </b>
https://www.thegatewaypundit.com/2020/12/breaking-fbi-texas-rangers-us-marshals-raid-solarwinds-hq-austin/
At the bottom of the article it includes a follow up tweet from the person that made the comment on Hannity's radio show. They say they never used the word raid. Law Enforcement agents going to the headquarters of an organization involved in a breach that could impact national security is a completely normal occurance. There is no evidence this was a raid or the agents going to the headquarter were not there by invitation to cooperate with the breach response. 

<b>Just The News Claims Pentagon imposed emergency shutdown of SIPR (The network used to transmit classified information)</b>
https://justthenews.com/government/security/pentagon-imposed-emergency-shutdown-computer-network-handling-classified
The article cites sources, stating "this never happens during the day". There are several sites reporting the emergency shutdown of SIPR, but link back to this story. Further, other posts conflate the CISA order to remove Solarwinds. There is no evidence actual evidence of confirmation this actually happened currently. Even this did happen there is no evidence it is directly related to Solarwinds. Even if it is related to Solarwinds the article even states it is not unusual for it to be taken offline, just that it was done in the middle of the day. Further, it would seem appropriate to take the system offline until it can be determined there is no impact from the Solarwinds breach and the CISA order can be executed to shutdown Solarwinds systems. These stories misrepresent the availability of facts and make many assumptions about related issues. 

<b>Gateway Pundit claims links to left wing politics, China, and US Elections process tied to Solarwinds Breach</b>
https://www.thegatewaypundit.com/2020/12/breaking-exclusive-owners-solarwinds-related-obama-clintons-china-hong-kong-us-election-process/
This article uses significant circumstantial evidence related to large equity firms and political donations. This article is all speculation with no actual evidence provided showing political influence being used to perpetrate the breach through board members. Further, it links this to Dominion Voting Systems in an attempt to further undermine election results. There is no evidence of this and if there were CISA and Chris Krebs spent significant effort over the last four years making sure something in the area of 95% of precincts were using systems that had manually auditable paper ballots. There is no way to effective hack this and all manual recounts matched the machine counts. 

<b>Gateway Pundit Claims SolarWinds Vulnerability provides Backdoor Access to their Voting Machines<b>
https://www.thegatewaypundit.com/2020/12/dominion-used-version-solarwinds-orion-platform-provides-backdoor-access-voting-machines/
This article takes to facts and tries to connect them via a straight line. Yes, the Solarwinds software allowed a backdoor. Yes, Dominion used Solarwinds software. However, as stated by Solarwinds they are used in 425 of 500 Fortune 500 companies. They are a fairly ubiqitous IT tool. There is absolute zero evidence the Solarwinds software gives any sort if direct access to voting machines or code running on them. An Internet Archive link shows the Solarwinds tool being used as evidence for the assumption s the Serv-U file sharing server - https://web.archive.org/web/20201214093452/http://dvsfileshare.dominionvoting.com/Web%20Client/Mobile/MLogin.htm 
The Solarwinds Security advisory from 12/6 states Serv-U products are believed to be unaffected - https://www.solarwinds.com/securityadvisory
Finally, even if direct code access or backdoors to CISA worked to help advise state and local governments regarding vote security with ~95% of precincts haveing a verifiable paper ballot system along with their electronic voting. Even if voting software manipulated totals a manual recound of the paper records would identify the error. This is covered on the CISA Rumor Control page - https://www.cisa.gov/rumorcontrol#rumor17 There is no evidence of vote manipulation, especially via the Solarwinds breach. 

<b>Washington Post reports $280 million in Solarwinds stock was traded days before breach announcement</b>
This article is included here because this article is being used to defend the trades and call them to task. The vast majority of these trades were completed by Thoma Bravo and Silver Lake Partners venture capital. There are some major concerns here as these to VC firms sit on the board of Solarwinds as they own a majority of the company. An investigation will likely occur to determine if there was insider trading. However, you will see the trades defended for the outgoing CEO, Kevin Thompson. The trades were approximately $15 million, reported, and scheduled as part of a planned sell off. Some articles will conflate the Thoma Bravo and Silver Lake sales with the planned sale by the CEO.  
https://twitter.com/washingtonpost/status/1339059943442419714?s=20

<h2>Public Information / Alerts</h2>

<b>SolarWinds Advisory </b>
https://www.solarwinds.com/securityadvisory

<b>Microsoft now in Control of C2 domains </b>
https://twitter.com/briankrebs/status/1338840527169613824?s=20

<b>CISA Alert </b>
https://us-cert.cisa.gov/ncas/current-activity/2020/12/13/active-exploitation-solarwinds-software

<b>Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"</b>
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

<b>Solarwinds SEC 8K Filings </b>
https://www.sec.gov/ix?doc=/Archives/edgar/data/1739942/000162828020017451/swi-20201214.htm

<b>Solarwinds Best Practice had users disable the folders where the malware resided for all AV and Security products</b>
https://support.solarwinds.com/SuccessCenter/s/login/?language=en_US&startURL=%2FSuccessCenter%2Fs%2Farticle%2FFiles-and-directories-to-exclude-from-antivirus-scanning-for-Orion-Platform-products%3Flanguage%3Den_US&ec=302

<b>Screenshot of Solarwinds Best Practice if you do not have support portal access </b>
https://twitter.com/ffforward/status/1338785034375999491/photo/1

<b>Vinoth Kumar shares information about their responsible disclosure of Solarwinds FTP account password to their CDN password "solarwinds123"</b>
https://twitter.com/vinodsparrow/status/1338431183588188160?s=20

<b>Kyle Hanslovan discovers SolarWinds is still listing the vulnerable package 24 hours after disclosure (Update: Package was removed) </b>
https://twitter.com/KyleHanslovan/status/1338360093767823362?s=20

<b>CISA Directive to shutdown and remove Solarwinds from all Federal Civilian Agencies </b> https://www.cisa.gov/news/2020/12/13/cisa-issues-emergency-directive-mitigate-compromise-solarwinds-orion-network

<b>The actual CISA directive - 21-01 </b>
https://cyber.dhs.gov/ed/21-01/

<b>RedDrip begins mapping Domain Generation Algorithms to compromised sites used by Solarwinds malware</b>
Includes many large companies and universities.
https://twitter.com/RedDrip7/status/1339168187619790848



<h2>Technical Analysis</h2>
 
 <b>FireEye GitHub with Detections </b>
https://github.com/fireeye/sunburst_countermeasures

<b>FireEye Technical Analysis </b>
https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html

<b>Volexity Technical Review of Dark Halo - More detail about O365 DUO MFA Bypass </b>
https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/

<b>Bruce Schneier Write-Up of the Duo MFA Bypass </b>
https://www.schneier.com/blog/archives/2020/12/how-the-solarwinds-hackers-bypassed-duo-multi-factor-authentication.html

<b>Analysis by Kim Zetter </b>
https://twitter.com/KimZetter/status/1338305089597964290

<b>SANS Internet Storm Center Diary </b>
https://isc.sans.edu/diary/rss/26884

<b>Analysis by Kyle Hanslovan </b>
https://twitter.com/KyleHanslovan/status/1338506923642122243

<b>PICUS Analysis Map of TTPs to MITRE ATT&CK includes additional hashes </b>
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach

<b>Che331o's Summary Thread of Jake Williams SANS slides related to the breach </b>
https://twitter.com/Ch33r10/status/1338612270033670144

<b>TrendMicro Analysis </b>
https://www.trendmicro.com/en_us/research/20/l/overview-of-recent-sunburst-targeted-attacks.html

<b>Reversing Labs analysis of the malcious file build</b>
https://blog.reversinglabs.com/blog/sunburst-the-next-level-of-stealth
 
<h2>Additional IOCs</h2>

<b>DLL Locations where the Malicious DLL has been discovered in the file structure </b>
https://gist.github.com/KyleHanslovan/0c8a491104cc55d6e4bd9bff7214a99e

<b>Additional Sunburst Hashes </b>
https://gist.github.com/olafhartong/71ffdd4cab4b6acd5cbcd1a0691ff82f

<b>PICUS Analysis - Map of TTPs to MITRE ATT&CK includes additional hashes </b>
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach​​​​​​​​​​​​​​

<b>Microsoft Security Response Center Blog Post </b>
https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/

<b>subdomain & DGA domain names used with Solarwinds Backdoor</b>
https://twitter.com/0xrb/status/1339199268146442241?s=20
https://pastebin.com/6EDgCKxd

<b>IPv4, Ipv6, and DGA domain names useed with Sunburst</b>
https://github.com/bambenek/research/tree/main/sunburst

<h2> Unsubstantiated Conspiracy, FUD, or Selective Manipulation of Information</h2>

This section was added to help address questions that arise during meetings, etc., from individual with potentially different news sources. This section includes items that are determined to be false or misleading. Hopefully this helps address comments in organizations before they become difficult to remove from internal conversations. 

<b>Gateway Pundit claims there was a raid on Solarwinds headquarters </b>
https://www.thegatewaypundit.com/2020/12/breaking-fbi-texas-rangers-us-marshals-raid-solarwinds-hq-austin/
At the bottom of the article it includes a follow up tweet from the person that made the comment on Hannity's radio show. They say they never used the word raid. Law Enforcement agents going to the headquarters of an organization involved in a breach that could impact national security is a completely normal occurance. There is no evidence this was a raid or the agents going to the headquarter were not there by invitation to cooperate with the breach response. 

<b>Just The News Claims Pentagon imposed emergency shutdown of SIPR (The network used to transmit classified information)</b>
https://justthenews.com/government/security/pentagon-imposed-emergency-shutdown-computer-network-handling-classified
The article cites sources, stating "this never happens during the day". There are several sites reporting the emergency shutdown of SIPR, but link back to this story. Further, other posts conflate the CISA order to remove Solarwinds. There is no evidence actual evidence of confirmation this actually happened currently. Even this did happen there is no evidence it is directly related to Solarwinds. Even if it is related to Solarwinds the article even states it is not unusual for it to be taken offline, just that it was done in the middle of the day. Further, it would seem appropriate to take the system offline until it can be determined there is no impact from the Solarwinds breach and the CISA order can be executed to shutdown Solarwinds systems. These stories misrepresent the availability of facts and make many assumptions about related issues. 

<b>Gateway Pundit claims links to left wing politics, China, and US Elections process tied to Solarwinds Breach</b>
https://www.thegatewaypundit.com/2020/12/breaking-exclusive-owners-solarwinds-related-obama-clintons-china-hong-kong-us-election-process/
This article uses significant circumstantial evidence related to large equity firms and political donations. This article is all speculation with no actual evidence provided showing political influence being used to perpetrate the breach through board members. Further, it links this to Dominion Voting Systems in an attempt to further undermine election results. There is no evidence of this and if there were CISA and Chris Krebs spent significant effort over the last four years making sure something in the area of 95% of precincts were using systems that had manually auditable paper ballots. There is no way to effective hack this and all manual recounts matched the machine counts. 

<b>Gateway Pundit Claims SolarWinds Vulnerability provides Backdoor Access to their Voting Machines<b>
https://www.thegatewaypundit.com/2020/12/dominion-used-version-solarwinds-orion-platform-provides-backdoor-access-voting-machines/
This article takes to facts and tries to connect them via a straight line. Yes, the Solarwinds software allowed a backdoor. Yes, Dominion used Solarwinds software. However, as stated by Solarwinds they are used in 425 of 500 Fortune 500 companies. They are a fairly ubiqitous IT tool. There is absolute zero evidence the Solarwinds software gives any sort if direct access to voting machines or code running on them. An Internet Archive link shows the Solarwinds tool being used as evidence for the assumption s the Serv-U file sharing server - https://web.archive.org/web/20201214093452/http://dvsfileshare.dominionvoting.com/Web%20Client/Mobile/MLogin.htm 
The Solarwinds Security advisory from 12/6 states Serv-U products are believed to be unaffected - https://www.solarwinds.com/securityadvisory
Finally, even if direct code access or backdoors to CISA worked to help advise state and local governments regarding vote security with ~95% of precincts haveing a verifiable paper ballot system along with their electronic voting. Even if voting software manipulated totals a manual recound of the paper records would identify the error. This is covered on the CISA Rumor Control page - https://www.cisa.gov/rumorcontrol#rumor17 There is no evidence of vote manipulation, especially via the Solarwinds breach. 

<b>Washington Post reports $280 million in Solarwinds stock was traded days before breach announcement</b>
This article is included here because this article is being used to defend the trades and call them to task. The vast majority of these trades were completed by Thoma Bravo and Silver Lake Partners venture capital. There are some major concerns here as these to VC firms sit on the board of Solarwinds as they own a majority of the company. An investigation will likely occur to determine if there was insider trading. However, you will see the trades defended for the outgoing CEO, Kevin Thompson. The trades were approximately $15 million, reported, and scheduled as part of a planned sell off. Some articles will conflate the Thoma Bravo and Silver Lake sales with the planned sale by the CEO.  
https://twitter.com/washingtonpost/status/1339059943442419714?s=20
