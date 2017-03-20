# Maintain the usefulness of digital materials

## Problem

Digital materials have particular characteristics that may cause them to become useless as time progresses. What actions must be taken to prevent digital materials from becoming useless?

## Context

The usefulness of digital materials is threatened in three ways; firstly, the software required to view and otherwise interact with digital materials may become obsolete; copies of the software may become hard to source, the expertise required to use it may become rarer, or the software it depends upon (e.g. the Operating System it expects to run upon) may also become obsolete. 

Secondly, the hardware used to store digital materials may deteriorate. In the case of magnetic materials such as hard disks or digital tape, the deterioration is often caused by 'bit-flipping', whereby external magnetic interference causes the magnetic impression of a '1' or a '0' to reverse. This gradually (or potentially catastrophically) changes the state of the stored data, which will eventually render the material unusable. Similarly, the reflective surfaces of optical media such as CDs and DVDs will also degrade over time.

Thirdly, digital materials that have been poorly arranged or described are also a risk of being lost, literally, because it becomes difficult to retrieve them. Unlike real materials with physical manifestations, it either needs a lot of technical skill, or dogged perseverance, to find materials that are 'saved on a disk somewhere' with no obvious logic to the storage scheme, and no description of the material provided to help find it later.

Addressing these three issues will ensure that digital materials can still be read and otherwise interacted with, that the information contained within the materials is still valid (and sometimes that the wider experience of using the materials is still available to the user), and that the materials can still be found in the first place.

## Forces

The key negative forces described in the context above are: **obsolescence**, **degradation** and **obscurity**. These are the key forces that cause the overall problem addressed by the whole domain of [Digital Preservation](DigitalPreservation.md). At a higher level of abstraction (which applies to all activities in the whole domain), the positive forces that address this issue are monitoring, management and maintenance.

**Monitoring** helps us know when the negative forces are having an impact. **Management** involves working out the steps to take to counteract the negative forces. **Maintenance** involves taking steps to counteract those negative forces.


## Solution

The three activities that address the negative forces threatening usefulness are: **the addressing of obsolescence**, **the prevention of deterioration**, and **the enablement of discovery**. 

**Obsolescence can be addressed** in two key ways:

1. Transforming the format of the file to one that is likely to have more longevity. There are multiple approaches to this, but one way that enables more efficient monitoring and management of digital material is to transform it to a small number of standard formats *before* preserving it. (This process is often referred to as 'normalisation' by digital preservation experts). Digital materials may also need to be transformed to more contemporary formats at later dates in their lifespans (a process often referred to as 'migration'), though this act is in turn made easier if they are in a commonly-used, well-understood format to start with. 
2. Emulating the environments required to use the digital materials. I.e. the software and wider environments required to use the materials can themselves be preserved, and then run using contemporary hardware and software at a later date, by employing a technique such a virtualising the environment on a host computer.

**Deterioration can be prevented** by monitoring the state of the hardware upon which the data is stored, managing the replacement of that storage hardware, and then moving digital materials from the old storage hardware to the new. At a more granular level, each piece of digital material can: 

* have backup copies made
* have the initial state that is to be preserved measured, and the measurement of that state recorded 

This record of initial state (usually in the form of a checksum) can then be used to validate that the original has not deteriorated, and when it has, the corrupted file can be replaced with a backup (which can also be checked, of course).

**Discovery can be enabled** by adequately describing the materials as they are preserved. The term 'adequately' is problematic here, however, as (over the timescales relevant to long-term preservation), what constitutes an adequate description to help find digital materials *now* may cease to be adequate in future. This can only be addressed by ensuring that as many contemporary descriptions of digital materials as possible (which are intended to make sense of them at the time) are linked to the materials effectively. This will result in a set of historical interpretations of materials that contemporary users can use to make sense of them when the time has come to use them again.

## Resulting context

If the solution is applied correctly, we should have digital materials that can still be used with hardware and software that did not exist at the time the materials were created. The materials should also be constituted of exactly the same underlying data that constituted the original data. And it should still be possible for people who are interested in the information the materials contain to find them and understand the contexts in which they were originally created.

## Rationale

The *Maintain the Usefulness of Digital Materials* pattern, is only valid as described here due to two phenomena that have fundamental root causes that are **not** addressed by the pattern:

1. **Obscurity** has 'traditionally' been made worse by a lack of standardisation in the early days of computing, before certain 'key' formats became prevalent. However, while obscurity is *less* of an issue at the time of writing, it is still problematic for two reasons. Firstly, there are still older computers 'in the wild' with important, valuable content in older, non-standard formats (Wordperfect seems to be a commonly-used example). Secondly, there are formats 'at the cutting edge' of computing where standards are yet to form (academic Research Data related to complex scientific topics would be a good example of this).

## Related Patterns

This pattern is at the 'elevator pitch' level of abstraction, that is - one level down from the overall domain.

### Parent pattern

* [Digital Preservation](DigitalPreservation.md)

### Sibling patterns

* [Source things to preserve](SourceThingsToPreserve.md)
* Get things under control.

### Child patterns

* Address obscurity
* Prevent deterioration
* Enable discovery