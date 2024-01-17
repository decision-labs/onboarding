Welcome to Decision Labs! Before we start, we need to make sure you don’t accidentally cause a massive security incident and flatline the company’s productivity for a few days. 

Please read the following and sign at the bottom. Contact security@decision-labs.com if you have questions.

## Handling a security incident 

If there is any unusual activity on our systems or suspect my system has been compromised in any way, I will email our security team at this address: 
email **shoaib+security@decision-labs.com**
cc **kashif+security@decision-labs.com**

## My company computer can be a target 

If the company gave me a laptop or computer to use or if I use a personal laptop for work, I will follow these simple steps to keep things safe: 
- I will use Chrome because they invest in security. 
- I will encrypt my laptop.
- I will use a screensaver that turns on when I’m away. This screen saver will require a password which… is the whole point! 
- I will install (and use) a password manager (**Bitwarden**).
- I will turn on enhanced safe browsing in Chrome which will hugely reduce my odds of being hacked. 
- I will always use 2FA if I have the option.

## Privacy, security incidents and security retrospectives 

I will assume that if there is a security incident, then someone from the security team has access to my personal data on company equipment, including files on my laptop, email communications, chat, etc. 

### Here are the common reasons why:

During a security breach, my computer might be imaged and stored elsewhere, my browser history would be scoured over, and my emails will be investigated for exploitation. It’s hard to spare my privacy when I’m hacked at work. 

For serious incidents I may become part of a lawsuit. My data would be subject to discovery and the peering eyes of all kinds of lawyers and the public through court proceedings as they figure out what is, and is not, relevant for the incident. 

I realise IT needs to do their job. They might access network traffic to diagnose network downtime while they get to a root cause. 
Since these are all terrible scenarios, I will restrict my usage of company technology to just work-related stuff as best as possible, because it will only make things painful if any of the above situations happened. And I certainly won’t use my personal devices to do sensitive work stuff. This includes storing unencrypted passwords, certificates, API Keys etc.

## Reasonable personal use

The good thing is that I will not be restricted from personal use of my devices, and plan to do some personal necessities at work, anyway. I should have some expectation that whatever personal data I do happen to expose will not be abused. 

As I mentioned above, I expect all my co-workers with administrative access to my data to be held under tight ethical usage standards and be secured from outsider abuse. If a co-worker decides to violate these protections, someone should tell me about it. 

Additionally, if I do illegal stuff on corporate systems, I don’t expect the company to cover me in any way. I just want to be able to read my personal Gmail on my device without someone watching me on my system. 

## My password is not ‘dog’

- I will not reuse passwords or use weak passwords. Instead, I will do the following things to not mess this up: 
- I will use a password manager (Bitwarden) so I don’t blindly fall victim to phishing websites. 
- I will never use the same password in more than one place. 
- Any passwords I can’t use within a manager (like a master password) will be hard to crack, and not be horribly weak like “2hot4u”. 
- Every time it’s offered: I will enable multi-factor authentication to make an attacker's life harder and give my team more peace of mind during a breach, on every system it’s offered on. 
- I will not use my personal email accounts for cloud platforms that support the company. 

## Engineering Policies 

This section is for developers and administrators of systems and data at Decision Labs. 
Logs catch the bad guys

Any systems I design or am reasonably involved with will have centralised and read only usage logs designed for others to look back on a security incident. I am fully aware of how terrible the nightmare would be if the company had a breach and had no records of what actually happened.

## Skeletons are bad 
At the bare minimum, I’ll be sure to document where I’m storing really sensitive data, like a social security number or a credit card number. I’ll make sure that I don’t start logging important information in some location we’ll immediately turn around and forget about, only for someone else to find. Additionally, I’ll send an email to **shoaib+security@decision-labs.com** so that others can handhold me through handling sensitive data.

## Cryptography

I am aware that anything involving cryptography is really hard and requires pairing with a senior engineer. If I’m dealing with any sort of cryptography, I will give a heads up to **shoaib+security@decision-labs.com** to involve others because I will surely break it by myself. This means I will not YOLO-Code when it comes to: 

- Storage of a private key or API token in a place that isn’t so private 
- Broken-For-Years Hashing algorithms like MD5 
- Password Storage so I don’t mess it up like LinkedIn did in 2012 
- Storage of credit card numbers so we’re not breached like every company before us, ever 

If I smell something broken in this area, I will also give shoaib+security@decision-labs.com a shout because it would be a disaster if I screwed this up. 

## Don’t trust other companies 
Whenever a contract turns into a data sharing agreement, I will include shoaib+security@decision-labs.com to make sure I didn’t just jeopardize our entire security posture by putting all our data somewhere else, or by giving another company access to our systems. 

## No voyeurism
If I turn out to be the employee with administrative access to employee data, production systems, user data, etc., I realize I could become the next “GCreep” or LOVEINT if I act selfishly or maliciously. I realise that if I am trusted with sensitive data, I am extra-likely to be in breach of the law or company policy if I’m doing anything with that access that is not my job. 

I read this and won’t ruin our security 

Signed, Muhammad Ahmed Baig 

Date:  18 / 08 / 2021 
 
 
### What is this “security policy” for?

Larger companies have employees sign an information security policy. It’s one of those things you have to eventually do for compliance reasons. After checking a compliance box they are largely forgotten and don’t really contribute to actual security or fix any employee habits. Oh, and they’re huge. 
This is a minimal policy drawing from ISO27002, but articulated in a way that could actually be understood. By being a bare minimum policy, it should be applicable almost everywhere. 
Credit 
Shamelessly adapted from [this](https://medium.com/starting-up-security/starting-up-security-policy-104261d5438a) excellent post by Ryan McGeehan. 
