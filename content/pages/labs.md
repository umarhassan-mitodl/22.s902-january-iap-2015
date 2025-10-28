---
content_type: page
description: This section provides instructions, tools, and software for a lab assignment
  to build a Geiger counter.
draft: false
learning_resource_types:
- Laboratory Assignments
ocw_type: CourseSection
title: Labs
uid: 0b9a6b9b-5bf6-bb2b-733c-8567fa220058
---
WARNING NOTICE:

An activity described in this course is potentially hazardous and requires a high level of safety training, special facilities and equipment, and supervision by appropriate individuals. You bear the sole responsibility, liability, and risk for the implementation of such safety procedures and measures. MIT shall have no responsibility, liability, or risk for the content or implementation of any of the material presented. [Legal Notice](/terms/)

During lab periods, students build their own Geiger counter, and then characterize their counter, the background radiation in the room, and its shielding properties, using the tools and software described below.

## Building the Geiger Counter

The MIT students enrolled in this class were given a kit containing all the parts required to build their Geiger counter, and a set of detailed instructions. 

- Parts list (choice of two file formats): {{% resource_link "56f66328-2079-1cdb-ee27-0133f311a740" "Bill of Materials (XLS)" %}}, {{% resource_link "217e9440-9a50-f7ca-9f02-c3ae6e5ae364" "Bill of Materials (PDF)" %}} (Courtesy of Mark Chilenski. Used with permission.)
- {{% resource_link "e5641a1b-cb88-964d-182a-11b5437fb1c6" "Instructions to build your Geiger-Müller Counter (PDF - 5.2MB)" %}} (Courtesy of Mark Chilenski. Used with permission.)
- {{% resource_link "eeb952be-7a60-3ecd-85c3-f54bbe681541" "Geiger Counter schematic diagram (PDF - 1.1MB)" %}} (Courtesy of Mark Chilenski. Used with permission.)

A soldering iron is also required.

### How Can I Obtain the Parts?

OCW cannot provide this parts kit to you directly, but we can offer tips on how to obtain the parts yourself. The Bill of Materials file above lists all of the parts, and the Instructions gives more details about how the parts are used for each step.

- In 2015, the parts would cost $60-$100 US (depending on your source).
- Most parts should be readily available from any electronics retailer.
- The SBM20 Geiger-Müller tube can be purchased on {{% resource_link "8f65a526-8de2-4500-a3d5-32d587c6b49f" "eBay" %}}.
- Circuit board fabrication companies can make the board for you, using the specification in these {{% resource_link "0dd01977-ae3f-5be7-8d62-8cae74d4e615" "Gerber files (ZIP)" %}} (This ZIP file contains: 1 .gbl file, 1 .txt file, 1 .gbo file, 1 .gtl file, 1 .gts file, and 1 .gto file). One such company is {{% resource_link "3d6083ff-9e75-41cc-b8f8-85ea91ee84b7" "Advanced Circuits" %}}. Shop for student specials on a single or small number of boards. 
- The plastic case is a Serpac 052C, which can be ordered from electronics retailers like {{% resource_link "0527d3eb-0a7f-44e8-8744-10911db1b2b8" "DigiKey" %}}.
- The case must have holes drilled in its sides, in order to let the beta particles through. While the MIT kit's case was custom machined on a CNC to produce letter-shaped holes, any shape holes in the middle of the sides will do. Refer to these mechanical drawings for guidance on the proper location of the holes: {{% resource_link "6aaa8bf9-e8c8-9368-f891-f4772b8b82d2" "top-view drawing (PDF)" %}} and {{% resource_link "9fc0523f-a416-59a6-4169-d53575349cc2" "bottom-view drawing (PDF)" %}}.

**NOTE** (July 2015): If OCW users express sufficient interest, the MIT Department of Nuclear Science and Engineering might offer this kit for sale to the public. If you are interested, please let them know by completing this brief {{% resource_link "8230b2be-467b-4f18-8c05-b19c2c8cf471" "web survey" %}}.

## Tools and Software

Labs use the {{% resource_link "05280de3-b054-4835-878c-e9bc325e7f54" "National Instruments ELVIS II" %}} system and MIT-provided software running on a Windows personal computer to collect data about the Geiger counter.

Begin by installing the National Instruments LabVIEW Run-Time engine and NI-DAQmx Run-Time engine. The versions of these programs used during the January 2015 MIT class are linked below.

- {{% resource_link "56f08daf-edfd-476f-8242-dc6d787e8f67" "LabVIEW Runtime Engine 2014" %}}
- {{% resource_link "00e9c35a-f405-4a26-adec-2e80f91e58bc" "NI-DAQmx 14.1 Runtime Engine" %}}

Note that these programs are updated frequently; consult the {{% resource_link "94a1bb86-f7ca-4b38-84d3-c9e7283de2f1" "NI Hardware Drivers page" %}} for the latest versions.

### MIT NSE Geiger Data Collection Program

After installing the above National Instruments programs, next install the {{% resource_link "0772d8c7-4905-d75b-9b6c-9e6e1ee762d4" "MIT NSE Geiger Data Collection Program (EXE - 1.8MB)" %}} (Courtesy of Matthew D'Asaro. Used with permission.) Detailed instructions for its use are displayed when you run the program.

*Please note*: This software is provided "as-is," and OCW cannot offer any further technical support.

Technical requirements:

- The software is designed to work with the NI-ELVIS II system. Most likely, it should also work with a wide variety of other NI data acquisition hardware (i.e. the NI-USB-xxxx series), but this functionality is untested.
- The following software environment is required:
    - Windows XP or newer
    - NI LabVIEW runtime engine 2014 or newer
    - NI NI-DAQmx runtime 14.1 or newer

## Lab Report

Having built their Geiger counter, each student performed a series of lab tests and activities with it, and wrote up a lab report.

{{% resource_link "35ccd113-f045-ca46-f3fb-47778d578931" "Lab Description and Report (PDF)" %}}

## {{< anchor "images" >}}{{< /anchor >}}Image Gallery

Here are some photos of the Geiger counter kit and students working in the lab.  
{{< image-gallery id="0b9a6b9b-5bf6-bb2b-733c-8567fa220058_nanogallery2" baseUrl="/courses/22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015/" >}}  
{{< image-gallery-item href="8806deeb408cb649ce8cf1b0f39a5beb_01_built.jpg" data-ngdesc="The assembled Geiger counter. Photo by Mark Chilenski." text="The assembled Geiger counter." >}}  
{{< image-gallery-item href="08fb374241c1acec9d4bd6e549b54f5d_02_kit.jpg" data-ngdesc="The parts that comprise the Geiger counter kit. Photo by Mark Chilenski." text="The parts that comprise the Geiger counter kit." >}}  
{{< image-gallery-item href="2722c55e6634a9cc994d1b5be187ebb9_03_lab.jpg" data-ngdesc="Students assembling their Geiger counters in the lab. Photo by Mike Short." text="Students assembling their Geiger counters in the lab." >}}  
{{< image-gallery-item href="6b0abc6e95bebf78f24059838f49d34e_05_solder.jpg" data-ngdesc="Soldering is one of the skills developed in this course. Photo by Mike Short." text="Soldering is one of the skills developed in this course." >}}  
{{< /image-gallery >}}