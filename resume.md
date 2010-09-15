---
layout: post
title: Peter Resume
--- 
<img src="./images/peter.jpg" alt="Peter Face" />
# Personal Info

**Name**: Peter Wang

**Birth Date:** Jan 2nd 1983

**Nationality:** China

**Address:** Beijing, P.R.China

**Mobile:** (+86) 134-2608-3580

**Email**: happypeter1983@gmail.com

**HomePage:** <http://happypeter.github.com>

### Sentence Bio

Peter Wang is a [Open Source Software][oss] developer. 

[oss]:http://en.wikipedia.org/wiki/Open_source

## Skill Summary

### Programming Languages

 - C
 - C++
 - Python
 - PHP
 - elisp
 - bash

## Education


__2001.9~2005.7:__ Hebei University of Science & Technology

During my under graduate study, my major was [_Electrical
Engineering_][electricalengineering]. To do [motor contol][motor] and
[automation][automation], we had a course on _C languange_ (2002) and later
learned two assembles, one for [MSC-51][mcs51](2004), the other
[8086][8086](2008) I also learned [PLC][plc] programming(2003).  During my
undergraduate study, I only concerned about single thread programming, stay
close to the hardware. But this changed when I start my postgraduate lift in:

__2006.9~2009.3:__ North China Electric Power University

I did reserch on developing a _Vibration data acquisition instrumant_, we
start with _80c51F_, linking against the C lib that came with it. That did
not satisfied anybody, so we switched to 32-bit ARM chip S3C2410, then we
wanted  Multithreading and GUI support, we need a real kernel to
settle the chaos, I picked Linux(while some guys chose WinCE), and that
changed my life. I spent most of my time on two things:

 - Linux driver for ARM(s3c24x0) chips.  
 - UI implemented with [Qt](http://qt.nokia.com/)

## Me in real world

__2009.3~2009.12:__ [Asianux Ltd][asianux]

System Updaters Based on rpm, (AXTU and YUM), chief maintainer of AXTU
and was responsible for writing a authentication plugin for YUM, in
order to implement it in Asianux4.0.

__2008.7 ~ present:__ [Beijing Linux User Group][blug]

 - manager of [Embedded Linux Group][elg]
 - manager of [GitBeijing][gitbeijing]
 - member of  [Quadcopter Group][quad]

__2008.8 ~ 2008.9:__ [Lenovo Co.Ltd][lenovo]

I participated in the smart phone project _Cixtone_ mainly worked on the
_Officeviewer_ part developed with Qt, as a tester. 

## Project Summary

__2009.3~2009.10:__ [AXTU][axtu]

I worked in Asianux as _AXTU_ developer, and for a few month as the chief
maintainer. AXTU is a Linux system updater, based on RPM, it has similiar work
flow as YUM, but implemented in C++, it was created by Hansoft engineers, long
time before I joined the development. What I added was:
 
 - epoch handling
 - obsolete tag handling

__2006.12~present:__ Tinylion

I am the founder of this project.
contains open source hardware as well as software. The software
contains driver and apps.
 
__2008.8 ~ 2008.12:__ Linux Device Driver (tinylion)
The driver is designed to control Sensor->ADC->SPI It is finally
compiled into a kernel module spi.ko, and loaded dynamically. 

__2008.8 ~ 2008.9:__ Hardware Design and Implementation (tinylion)
The hardware platform is based on S3C2410 ARM chip. I bought a 6 layer
core board and designed a 2-layer extented board for it. 

__2008.8 ~ 2008.9:__ User Application Design and Implementation (tinylion)
Tata is the PC version of this part.

__2008.12 ~ present:__ Tata

Tata is a Qt project aiming at developing a data analysis program for
scientific use. It contains wave form display and other data analysis
functions. It is a SF.net hosted open source project. I am the founder
and the administrator of Tata, working with developers from many
countries. 

__2008.8 ~ 2008.9:__ Nokia N810

As a student researcher in Lenovo, I  estimated the Nokia
N810 development platform to figure out whether it is suitable for
Lenovo's next generation smart phone development. Thus I installed
maemo on my own machine, and tried to run some Helloworld examples. 

__2008.12 ~ 2009.1:__ Porting Qt4.4.3 to S3C2410 Platform

Formerly Tinylion user app part was written under a older version of
Qt/embedded, but now I am able to port the latest version of
Qt/embedded to my own hardware platform.  

[asianux]: http://www.asianux.com
[plc]: http://en.wikipedia.org/wiki/Programmable_logic_controller
[blug]: http://www.beijinglug.org/en/index.php
[lenovo]: http://www.lenovo.com/us/en/#ss
[elg]:http://www.beijinglug.org/en/index.php?option=com_groupjive&action=gj.core.groups.showgroup&groupid=22&Itemid=134
[gitbeijing]: http://happypeter.github.com/GitBeijing/
[quad]:http://www.beijinglug.org/en/index.php?option=com_groupjive&action=gj.core.groups.showgroup&groupid=8&Itemid=134
[electricalengineering]:http://en.wikipedia.org/wiki/Electrical_engineering
[automation]:http://en.wikipedia.org/wiki/Automation
[mcs51]:http://en.wikipedia.org/wiki/Intel_MCS-51
[8086]:http://en.wikipedia.org/wiki/Intel_8086
[motor]:http://en.wikipedia.org/wiki/Electric_motor
[axtu]:http://happypeter.github.com/axtu/
