# Digital Preservation

![Digital Preservation Pattern Map](https://github.com/CamLib/DigitalPreservationPatternLanguage/blob/Development/Images/DigitalPreservationPatternMap.png)


## Problem

Digital materials such as computer files or pieces of executable software have a short life-span when compared to paper-based or other physical materials that can be preserved for very long periods. How can we ensure that digital materials are still useful and useable, decades or even centuries from now?

## Context

Digital files are different from physical equivalents such as paper because the information they contain is separate from the mechanisms that are used to store and present their information. 

For example, the information in a paper document is formed by the ink printed onto the paper itself in the form of words. In a word-processor file, the physical manifestation of the information is in the form of a sequence of binary information (typically thought of as '1s and 0s'), usually stored on a magnetic or optical disk. This means the usefulness of digital files depends upon the software needed to interpret their binary sequences. This immediately makes the task of preserving the information more complex, as there is a need to also preserve the interpretation software.

Preserving software is more complicated still as software relies upon other software, in particular the lower-level software (often referred to as the Operating System, or sometimes just 'the software environment') required to display it and manage user interaction with it when it runs. This can result in a need to similarly preserve the environments (and in some cases even the hardware - the physical pieces of computer equipment) required to run the software, which is in turn needed to interpret the preserved information.


## Forces

The key forces that causes the Digital Preservation problem are **obsolescence**, **obscurity** and **degradation**. 

**Obsolescence** is caused by the creation of new technology that replaces existing technology. This results in the gradual (or sometimes rapid) loss of knowledge about existing software and hardware as newer versions replace them. When old software is no longer executable, because the technologies it depends upon no longer exist, or the knowledge required to execute it is no longer available, then the information and knowledge contained in files that depend upon that old software is lost.

**Obscurity** is a threat because digital materials do not have a physical manifestation: one cannot see what is stored on a disk just by looking at the disk itself, or even by looking at the '1s and 0s' stored on the disk. Obscurity is therefore caused by the gradual or rapid loss of contextual information that describes files and provides them with key meaning (e.g. the location of the file in question on the disk, or the date the file was created), and may manifest itself by not being able to find the file. Obscurity is also caused by disorganisaton: i.e. the poor management of collections of materials. Obscured files may be perfectly preserved, but are literally lost to the world.

**Degradation** can occur in the underlying binary sequences in which digital information is stored. This is as a result of  imperfections in the way that digital materials are stored, either on magnetic disks or tape, or on optical media such as CDs and DVDs, all of which have short lifespans. 

Digital Preservation is therefore a long-term process of monitoring for the effects of these forces and managing digital materials in order to counteract them. However, the forces interact: for instance, degradation might one day be negated by more robust storage technology that is not prone to issues such as demagnetisation, but this might be at the expense of being able to quickly read through the stored information; hence lessening degradation might increase obscurity. Such future storage might also require new Operating Systems, which could also render existing software obsolete.



## Solution

There are three key aspects to solving the Digital Preservation problem. Firstly, as the solution is an ongoing process that demands constant use of resources, it is important to [source things to preserve](SourceThingsToPreserve.md) as effectively as possible. Secondly, digital materials deemed worthy of preservation must be **brought under control**: this means organising them effectively to prevent obscurity and enable planning that prevents future obsolescence. Thirdly, Digital Preservation involves [maintaining the usefulness](MaintainTheUsefulnessOfThings.md) of digital materials by counteracting obsolescence, obscurity and degradation, in perpetuity.

The above description constitutes an 'elevator pitch' for Digital Preservation.

All three aspects of the Digital Preservation process involve domain-wide processes of monitoring, management, quality checking and process improvement.


## Resulting context

Enacting Digital Preservation results in digital materials that remain useful, useable and valuable to people into the far future. The information these materials contain will still be found, accessed and read (or otherwise interacted with) in ways that are valuable to future users.

## Rationale

The Digital Preservation pattern relates in some ways to the practices of archiving physical materials, but with crucial differences in practical implementation that may often seem counter-intuitive to people with traditional archiving skills and knowledge. This may particularly be the case when maintaining the usefulness of files, as digital materials and their surrounding contexts may need to be altered, or otherwise 'touched' more often than one would expect with physical materials.

In contrast, the Digital Preservation pattern may have aspects that are counter-intuitive to some of the attitudes and approaches of software developers and other Information Technology practitioners. The nature of such work is still comparatively new (i.e. it is not much more than half a century since 'Computer Science' became a widespread subject), and so the overall domain of Information Technology is still forward-thinking to the extent that obsolesence is still considered an acceptable aspect of the domain. **While this remains the case, a tremendous amount of 'born-digital' human knowledge remains at risk**.

## Related Patterns

### Parent pattern

This is the overarching pattern that describes the whole Digital Preservation domain at the highest level of abstraction. 

### Sibling patterns

The following patterns are all at the same "whole domain" level of abstraction:

* Monitor Digital Preservation forces
* Manage Digital Preservation tasks
* Check Digital Preservation quality
* Improve Digital Preservation processes

### Child patterns

The following patterns are all at the lower "elevator pitch" level of abstraction:

* [Source digital materials to preserve](SourceThingsToPreserve.md)
* Get digital materials under control
* [Maintain the usefulness of digital materials](MaintainTheUsefulnessOfThings.md)