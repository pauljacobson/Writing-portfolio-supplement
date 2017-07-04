# Background

I wrote these texts for a security company I applied to. The brief was to write a media release about the outcome of security research conducted by the company. The hypothetical research concerned a vulnerability in IoT security cameras.

I have replaced the company's name with "Beta".

# Text

## Abstract

### Shorter version

Beta security researchers have discovered traces of source code for malware dubbed "Kismet" in a popular, networked security camera range running Linux called AcmeCam.

Roughly two million AcmeCam cameras were sold in 2016, alone, and are available in homes and businesses worldwide.

In Beta's tests, AcmeCam cameras are typically compromised in less than 75 seconds after being connected to a network. The cameras are quickly attacked by a Kismet-based worm and infected by downloading an unsigned malware update over the unsecured http protocol.

When triggered, a Kismet can penetrate any device that shares a network with its host AcmeCam by tunneling through network level security safeguards. Kismet is specifically designed to seek out sensitive personal data and financial information and distribute it to a series of local nodes.

The attack vector is through AcmeCam firmware updates that are inadequately secured with default usernames and passwords that are, in turn, hard coded into all AcmeCam cameras.

### Longer version

Poor security in a popular brand of networked security camera could soon be responsible for one of the biggest data leaks in history. Beta's security researchers have discovered code for a new generation of malware that is likely already present in millions of devices already.

Source code for malware dubbed "Kismet" was released on Hackforums, the same forum the Mirai source code was published on. Similar to Mirai which infected Linux-based IoT devices, Beta's researchers have found Kismet code in a popular, networked security camera range running Linux called AcmeCam.

Roughly two million AcmeCam cameras were sold in 2016, alone, and are available in homes and businesses worldwide. In Beta's tests, AcmeCam cameras are typically compromised in less than 75 seconds after being connected to a network. The cameras are quickly attacked by a Kismet-based worm and infected by downloading an unsigned malware update that slaves the camera to a local node.

When triggered, a Kismet can penetrate any device that shares a network with its host AcmeCam by tunneling through network level security safeguards. Kismet is specifically designed to seek out sensitive personal data and financial information and distribute it to a series of local nodes.

The attack vector is through AcmeCam firmware updates that are inadequately secured with default usernames and passwords that are, in turn, hard coded into all AcmeCam cameras. The AcmeCam update service ignores industry standard authentication best practices and accepts new, unsigned firmware updates over the unsecured http protocol.

According to Beta's lead researcher, Yoni Bloggs, "the prevalence of cheap, networked security cameras continues to present a serious risk to commercial and personal data security for as long as their manufacturers continue to implement sub-standard security to safeguard firmware updates for the sake of expediency and cost savings".

Beta notified AcmeCamCo shortly after discovering the vulnerability in March 2017. AcmeCamCo failed to respond to our notification or take any of our recommended remedial steps. Given the prevalence of AcmeCam cameras, the only responsible course of action was for Beta to release the security team's findings so AcmeCam customers can take steps to mitigate the risk infected camera pose to them.

Beta's full report is available on the Beta website.

## Steps to distribute the report

*Note: I was also asked to outline how I would distribute this hypothetical media release in a format that could be adapted to a presentation*

1. Edit the content to ensure it reads clearly in English
2. Identify key journalists/columnists dealing with infosec themes and reach out to them with a copy of the research and the research abstract
	1. The Hacker News
	2. TechCrunch
	3. Ars Technica
	4. Brian Krebs
	5. CSO (IDG)
	6. Etc …
3. Prepare a blog post summarizing the research findings to be published on the Beta blog based on the media abstract
4. Create an infographic with key data-points from the research and share on Twitter and LinkedIn with a link back to a blog post (incorporate the infographic into the blog) - if possible make the infographic embeddable so journalists and commentators can embed the infographic in their articles and link back to the blog post
5. Share the core findings of the report in newsletter to clients with social sharing links
