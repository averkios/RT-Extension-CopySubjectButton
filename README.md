### NAME  
  RT-Extension-CopySubjectButton - Button that copies the subject in proper format for mail client reply

### DESCRIPTION  
  Adds a button next to the subject header, of a ticket, that copies the subject in proper format to reply using a mail client. Just paste it in the subject line of your mail reply.
  
  ![alt text](https://raw.githubusercontent.com/averkios/RT-Extension-CopySubjectButton/master/CopySubjectButtonDemo.gif?raw=true)

### RT VERSION  
  Works with RT 5.0.2, 5.0.3

### INSTALLATION  
    perl Makefile.PL
    make
    make install
        May need root permissions

    Edit your /opt/rt5/etc/RT_SiteConfig.pm
        Add this line:

            Plugin('RT::Extension::CopySubjectButton');

    Clear your mason cache
            rm -rf /opt/rt5/var/mason_data/obj

    Restart your webserver

### AUTHOR  
    Averkios

    All bugs should be reported via email to
        bug-RT-Extension-CopySubjectButton@rt.cpan.org
    or via the web at
        http://rt.cpan.org/Public/Dist/Display.html?Name=RT-Extension-CopySubjectButton
### LICENSE AND COPYRIGHT  
    This software is Copyright (c) 2023 by Averkios

    This is free software, licensed under:

      The GNU General Public License, Version 2, June 1991
