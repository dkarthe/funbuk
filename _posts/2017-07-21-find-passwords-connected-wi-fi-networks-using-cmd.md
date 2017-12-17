---
id: 6734
title: How To Find Passwords of All Connected Wi-Fi Networks using CMD
date: 2017-07-21T15:11:42+00:00
author: Admin
layout: post
guid: https://techbyte.me/?p=6734
permalink: /2017/07/21/find-passwords-connected-wi-fi-networks-using-cmd/
tdc_dirty_content:
  - "1"
post_views_count:
  - "46"
serpentsoft_post_views_count:
  - "0"
dsq_thread_id:
  - "6273212888"
categories:
  - How-To
---
<span class="dropcap dropcap3">W</span>indows command prompt is a great tool for the people who love command interface rather than Graphical UI. There are a lot of features which are still not implemented in Graphical User Interface can be accessed via CMD. In my previous articles, I’ve talked about a lot of CMD commands. In this article, I am going to share how to find out the password of all connected devices using CMD along with suitable screenshots for clear understanding.

Before going further, you should know one thing that whenever you connect to a Wi-Fi network and enter the password,  Windows creates a WLAN profile of that Wi-Fi network. These WLAN profiles are stored in the computer alongside other required details of the Wi-Fi profile.

<div></div>

We can uncover these WLAN profiles later by simply using Windows CMD. You can find out all the connected networks and their passwords by using simple commands. These commands can also uncover the Wi-Fi passwords of the networks which are not connected at the moment but were connected before. So it works even when you are offline or when you are connected to any other networks. The trick just has no limitations and it’s reliable enough.

There are a lot more things you can do with CMD for Wi-Fi networks. For example, you can turn on MAC randomization, change radio type of your Wi-Fi and much more.

<h2>How to know Wi-Fi passwords using CMD?</h2>

You can open the CMD in Windows 10 by right-clicking on Windows icon.

<strong>1. Open command prompt and run it as administrator</strong>

Once you open the Command Prompt as Admin, you will have to type this command without quotes “<strong>netsh wlan show profile</strong>”

<div></div>

<figure id="attachment_12197" class="wp-caption aligncenter"><img class="wp-image-12197 size-large" src="https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-1024x610.jpg" sizes="(max-width: 696px) 100vw, 696px" srcset="https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-1024x610.jpg 1024w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-300x179.jpg 300w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-500x298.jpg 500w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-696x415.jpg 696w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-1068x637.jpg 1068w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed-705x420.jpg 705w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-1-compressed.jpg 1072w" alt="Find Wi-Fi passwords of all networks using CMD - 1-compressed" width="696" height="415" />

<figcaption class="wp-caption-text">This command will return the list of all the Wi-Fi networks that you have ever connected to.</figcaption>

</figure>
From the following list, Let’s find Wi-Fi password for network “<strong>virus</strong>”.

<strong>2. </strong>Type this command without quotes<strong> “netsh wlan show profile virus key=clear”</strong>
<figure id="attachment_12198" class="wp-caption aligncenter"><img class="wp-image-12198 size-large" src="https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-1024x745.jpg" sizes="(max-width: 696px) 100vw, 696px" srcset="https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-1024x745.jpg 1024w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-300x218.jpg 300w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-500x364.jpg 500w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-324x235.jpg 324w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-696x506.jpg 696w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-1068x777.jpg 1068w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed-577x420.jpg 577w, https://www.technotification.com/wp-content/uploads/2017/06/Find-Wi-Fi-passwords-of-all-networks-using-CMD-2-compressed.jpg 1072w" alt="Find Wi-Fi passwords of all networks using CMD - 2-compressed" width="696" height="506" />

<figcaption class="wp-caption-text">This command will show you the complete profile of wireless network along with its password</figcaption>

</figure>

<div></div>

Under security settings, in key content, you can see the Wi-Fi password for that network. I hope you found it useful. If you’ve any problem, you can comment down below.