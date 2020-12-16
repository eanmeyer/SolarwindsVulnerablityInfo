# Solarwinds Vulnerablity Info
Repository with all the Solarwinds Vulnerability information I've been tracking and using for communications, review, and technical understanding.

It's devided into four sections: News Reports, Public Information / Alerts, Technical Analysis, and Additional IOCs. There is some overlap where a few links may be a long for technical analysis, but may also include IOCs. Others may be advisories that also qualify as news. 

This is all public information and is provided freely for use. 

Previously I was tracking all of this in a Twitter thread located here: https://twitter.com/EanMeyer/status/1338324466808590345?s=20

I will post this GitHub repo to that Twitter thread and ongoing updates will be here.

<h2>News Reports</h2>

SolarWinds Advisory
https://www.solarwinds.com/securityadvisory

KrebsOnSecurity - US Treasury Breach and Solarwinds 
https://krebsonsecurity.com/2020/12/u-s-treasury-commerce-depts-hacked-through-solarwinds-compromise/

KrebsOnSecurity - Solarwinds Breach Effects 18k Customers, Microsoft takes control of domains 
https://krebsonsecurity.com/2020/12/solarwinds-hack-could-affect-18k-customers/

Washington Post ties Solarwinds breach to all recent major breaches - https://www.washingtonpost.com/national-security/russian-government-spies-are-behind-a-broad-hacking-campaign-that-has-breached-us-agencies-and-a-top-cyber-firm/2020/12/13/d5a53b88-3d7d-11eb-9453-fc36ba051781_story.html

ZDNet reporting on Solarwinds 8K filing 
https://www.zdnet.com/article/sec-filings-solarwinds-says-18000-customers-are-impacted-by-recent-hack/

Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

<h2>Public Information / Alerts</h2>

SolarWinds Advisory 
https://www.solarwinds.com/securityadvisory

Microsoft now in Control of C2 domains 
https://twitter.com/briankrebs/status/1338840527169613824?s=20

CISA Alert 
https://us-cert.cisa.gov/ncas/current-activity/2020/12/13/active-exploitation-solarwinds-software

Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

Solarwinds SEC 8K Filings 
https://www.sec.gov/ix?doc=/Archives/edgar/data/1739942/000162828020017451/swi-20201214.htm

Solarwinds Best Practice had users disable the folders where the malware resided for all AV and Security products
https://support.solarwinds.com/SuccessCenter/s/login/?language=en_US&startURL=%2FSuccessCenter%2Fs%2Farticle%2FFiles-and-directories-to-exclude-from-antivirus-scanning-for-Orion-Platform-products%3Flanguage%3Den_US&ec=302

Screenshot of Solarwinds Best Practice if you do not have support portal access 
https://twitter.com/ffforward/status/1338785034375999491/photo/1

Vinoth Kumar shares information about their responsible disclosure of Solarwinds FTP account password to their CDN password "solarwinds123"
https://twitter.com/vinodsparrow/status/1338431183588188160?s=20

Kyle Hanslovan discovers SolarWinds is still listing the vulnerable package 24 hours after disclosure (Update: Package was removed) 
https://twitter.com/KyleHanslovan/status/1338360093767823362?s=20


<h2>Technical Analysis</h2>
 
FireEye GitHub with Detections 
https://github.com/fireeye/sunburst_countermeasures

FireEye Technical Analysis 
https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html

Volexity Technical Review of Dark Halo - More detail about O365 DUO MFA Bypass 
https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/

Bruce Schneier Write-Up of the Duo MFA Bypass 
https://www.schneier.com/blog/archives/2020/12/how-the-solarwinds-hackers-bypassed-duo-multi-factor-authentication.html

Analysis by Kim Zetter 
https://twitter.com/KimZetter/status/1338305089597964290

SANS Internet Storm Center Diary 
https://isc.sans.edu/diary/rss/26884

Analysis by Kyle Hanslovan 
https://twitter.com/KyleHanslovan/status/1338506923642122243

PICUS Analysis Map of TTPs to MITRE ATT&CK includes additional hashes 
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach

Summary Thread of Jake Williams SANS slides related to the breach 
https://twitter.com/Ch33r10/status/1338612270033670144

TrendMicro Analysis 
https://www.trendmicro.com/en_us/research/20/l/overview-of-recent-sunburst-targeted-attacks.html
 
<h2>Additional IOCs</h2>

DLL Locations where the Malicious DLL has been discovered in the file structure 
https://gist.github.com/KyleHanslovan/0c8a491104cc55d6e4bd9bff7214a99e

Additional Sunburst Hashes 
https://gist.github.com/olafhartong/71ffdd4cab4b6acd5cbcd1a0691ff82f

PICUS Analysis - Map of TTPs to MITRE ATT&CK includes additional hashes 
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach​​​​​​​​​​​​​​

