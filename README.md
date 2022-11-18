# Home lab from scratch

## About this site

My goal is to provide a guide on building up a reasonable homelab with VLAN isolation, a seperate storage environment with backups and self hosting of various services with containerization. Everything will be automated and repeatable with tools such as Ansible, Terraform and Packer. Where possible, I'll provide links to the influences I've had online to set these up.

A homelab is anything you want to make it. From 3 or 4 Raspberry pi's to old throwaway servers you got from you employer.  The goal of your homelab should be about you.  Either you want to host something useful like a media server for you family, or you are learning something new.

## About me

My name is Rick Hernandez. I've been an UNIX sysadmin my entire career and I wouldn't want to work in any field outside of tech. 
I went many years quite content in knowing pure, straight UNIX (later Linux) as a system administrator as it was my entire world on 
the job and didn't really keep up with the new tech as I should have.  When I finally had my "awakening" I discoevered that the entire definition 
of doing what I do had changed dramatically.

A large part of this journey was my homelab. Things are moving ever more to cloud and I am as well. I'm currently working towards my certification 
on the AWS platform.  Had it not been for my homelab, I would be learning most of the concepts for cloud for the first time on AWS. There is something
to be said for setting up a container orchestration environment on your own versus clicking a button on a GUI and 
having a fully redundant, scalable and highly available environment waiting for you. In the lab all that is up to you.

# What I use

One of the biggest complaints I have with most other sites is their use of Ubuntu. I have nothing against Ubuntu for your desktop. It seems ok. As a server OS my work uses Red Hat Enterprise Linux (RHEL). Most every job I've seen uses RHEL. If I'm trying to replicate my work environment at home why would I use a completly different environment?  For that reason I choose Rocky Linux. In the post-CentOS environment we are in, Rocky provides the most RHEL like experience without licensing fees.  For a homelab why would you want to pay for support.

I also virtualize and in the VMs I use docker with docker swarm. I'm getting the hang of kubernetes but there are only so many hours in a day.  My hypervisor of choice is Proxmox. Again, no fees it's just free with no hassle about licensing and it just works.

The first two playbooks here will create a basic Rocky Linux server and then configure it to be ab;e to build all of the Rocky Linux and Proxmox servers you would ever need.

<!---
rickh1965/rickh1965 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
