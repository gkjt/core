# FAQ

## Looks like a fun society, how do I join?
We are not a society, we are just a group of people in ECS who are trying to revive a project that has come and gone in many different shapes.
We are open to people helping out though, and would love to have you on board! If you have an idea, see "Who can help out?" in our page on 'How to Contribute'!

## Who can help out?
We're open to contributions from any University of Southampton member.

## I need a Virtual Machine! What do?
Great!
We have a nice web interface at [services.cslib.org](https://services.cslib.org), go take a look (you'll need to be on the Uni VPN).
You'll need an account to spin up one of our standard templates, which includes Ubuntu, Arch, and Windows.
You can get one of those [here](https://services.cslib.org/signup) (also requires VPN).

## What am I allowed to do?
Largely there is one major rule: *Don't be a dick*.
If you start messing with the infrastructure and cause problems, you could cause the whole project to shut down permanently.
If there is any doubt, talk to an admin first, because any infringement will result in your VMs being destroyed and your account disabled.

When you first created an account with us, you agreed to our terms and conditions, also available in this repo.
Anything you do here is governed by them and we reserve the right to update them at any time.
They don't exist just to restrict people and prevent you from doing things, they're there for the safety of us and others.

## What's this `cslman` user on my VM?
That's our management and monitoring user, so we can remotely manage hosted machines.
Please do not mess with this, if you do we may just delete the machine and you will lose any right to have VMs on our infrastructure.
We have automated scripts which rely on it which will alert us of any tampering.
Read our [terms and conditions](https://github.com/CSLib/core/blob/master/terms.md) for more info.

## I have an idea, but it needs a few VMs....
Ok, if they're only small you might still be able to use our Services portal to provision them.
Else, think about making a template instead that can be spun up on demand, or talk to one of the admins and see if something can be arranged, although be aware that our resources are limited!

## I need more resources!
Our resources are limited, so you if you need a 100GB of RAM and 20TB of disk you might be out of luck, but talk to one of our admins and we might be able to sort something out.
Please bear in mind though that these are limited, and that we have to be fair for everyone.
We'll only allow bigger VMs for short amounts of time, or if it is for something that will benefit the rest of the university in some way.

## But what if I just provisioned my own VMs? (or: I want root on vSphere!)
*Whoa there!* Now we would like to give people access to our management interface, but we are limited.
*We want to let you do cool things.*
But, we can't just give anyone that sort of access, and we are in a position where a small problem could cause us issues to the extent the entire project gets shut down.
So we _may_ give _select_ people access to manage VMs and provision them manually, but that is only once they have demonstrated that they are trustworthy, knowledgable, fit our values to share expertise in the field, and most importantly have consistently followed the don't be a dick rules!
