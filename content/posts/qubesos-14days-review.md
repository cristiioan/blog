---
title: "QubesOS 14 days review"
date: 2022-02-28T21:03:13+02:00
slug: 2022-02-28-qubesos-14days-review
type: posts
draft: true
categories:
  - default
tags:
  - default
---

# QubesOS 14 days review

One week ago, I switched back to Arch Linux after using QubesOS for about 2 weeks. While the reasons where less technical, it was still a good experience.

### GUI

QubesOS is using as a desktop environment XFCE4. While XFCE is a good choice for a desktop environment, the lack of customization due to security concerns makes it a bit difficult to use. Qubes special apps are made using GTK and are pretty easy to use.
I would give a **2/5** for the GUI as it is hard to customize and it is not easy to use.

### Applications

Qubes special apps are easy to use for managing the system. I would give a **3/5** for the applications as they are easy to use and they are not easy to use.

Other applications is not so easy to install but it has the benefits of supporting multiple packages from other linux distros, thus making it perfect for people who need to use software available only on specific distros.

One more benefit is the possibility to separate applications making it really great for working on multiple projects without interfering with each other.

### Security

Qubes OS is probably the most secure linux distro(technically XEN) I have used. From start you realize that some actions you where doing normally without thinking about theme are huge issues. Like opening a random PDF file. Or that USB devices can be infected with malware. Achievements like this are made by using VM isolation for most of the actions (Browsing the internet is made from specific VMs, while others are for storing data securely).

There are 4 types of VMs in Qubes OS:

- Disposable VMs - VMs that are destroyed after the session is closed. Thus removing everything bad that can happen on it. As an example, it is the best way to watch torrents as they are removed after the session is closed.
- Normals VMs - This are your standard VMs that you have and with tools like VirtualBox.
- Qubes - This are VMs that are used to run applications. They are not destroyed after the session is closed. Thus you can use them to store data.
- Templates - This are VMs that are used to create new VMs. Mostly we open them just to install new software that can be then used on a Disposable VM or Qube.

I would give a **5/5** for the security. But remember that even the developers of Qubes OS are still working on it.

### Am I going to use QubesOS again?

Yes, I will. The reasons is that while it has lots of inconveniences, its security is better than nothing. Currently I don't plan to move back to Qubes due to hardware issues and thinks that are impossible to use right now on Qubes(Wayland, Nvidia dGPU on laptops, etc).

# Conclusion

Qubes OS is a great linux distro. Even if you don't plan to use it, I recommend checking it out every few months.
