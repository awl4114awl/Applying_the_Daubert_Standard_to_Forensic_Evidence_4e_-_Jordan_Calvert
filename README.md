<p align="center">
<img src="https://i.imgur.com/t23TXuR.png" height="80%" width="50%" alt="daubert standard"/>
</p>

<h1>Lab 1: Applying the Daubert Standard to Forensic Evidence</h1>

Introduction
<br />

One legal standard that is key to forensics and too often overlooked in forensic books is the Daubert standard. This standard is used by a trial judge to make a preliminary assessment of whether an expert’s scientific testimony is based on reasoning or methodology that is scientifically valid and can properly be applied to the facts at issue. Under this standard, the following factors may be considered in determining whether the methodology is valid:

 

    Has the theory or technique in question been tested?

    Has the theory or technique been subjected to peer review and publication?

    Does the theory or technique have any known or potential errors?

    Does the theory or technique adhere to the maintenance of standards controlling its operation?

    Has the theory or technique attracted widespread acceptance within a relevant scientific community?

 

Established in 1993 as a result of the Supreme Court case Daubert v. Merrell Dow Pharmaceuticals, Inc. (509 U.S. 579), the Daubert standard is the test currently used in federal and most state courts. Because the Daubert standard requires that scientific evidence presented in court be generally accepted in the field, it is unlikely that new tools would be immediately approved for use in court. For this reason, it is important that a forensic investigator be familiar with emerging technologies and developments in the field of forensic techniques.

 

In this lab, you will act as a forensic specialist assisting the lead forensics investigator at the Cyber Crimes Division (CCD) of the Boston Police Department. You have been given a hard drive image taken from a seized computer that is suspected to contain evidence of a sophisticated drug trafficking operation. First, you will review the search warrant and complete the Chain of Custody form that accompanies the evidence drive. You will then prepare the contents of the seized hard drive image as evidence in accordance with the Daubert standard using a variety of forensic tools.



Lab Overview

SECTION 1 of this lab has three parts, which should be completed in the order specified.

 

    In the first part of the lab, you will review a search warrant and complete a Chain of Custody form for seized evidence.

    In the second part of the lab, you will use FTK Imager to create hash codes for suspicious files.

    In the third part of the lab, you will validate the hash codes using Paraben's E3.

SECTION 2 of this lab allows you to apply what you learned in SECTION 1 with less guidance and different deliverables, as well as some expanded tasks and alternative methods. You will explore the suspect’s drive image to locate additional evidence. You will also use Autopsy, another popular digital forensics tool, to validate the hash codes created during your preliminary investigation.

 

Finally, you will explore the virtual environment on your own in SECTION 3 of this lab to answer a set of questions and challenges that allow you to use the skills you learned in the lab to conduct independent, unguided work - similar to what you will encounter in a real-world situation.



Learning Objectives

Upon completing this lab, you will be able to:

 

    Prepare evidence for court and complete forms used in evidence handling.

    Understand how a judge will determine the admissibility of evidence using the Daubert standard.

    Import a drive image as evidence using digital forensics software.

    Identify suspicious files as evidence using digital forensics software.

    Create hash codes to verify the integrity of forensic evidence.



Topology

This lab contains the following virtual machines. Please refer to the network topology diagram below.

 

    vWorkstation (Windows: Server 2019)

 

1622666045223_mceclip29.png



Tools and Software

The following software and/or utilities are required to complete this lab. Students are encouraged to explore the Internet to learn more about the products and tools used in this lab.

 

    FTK Imager
    Paraben's E3
    Autopsy



Deliverables

Upon completion of this lab, you are required to provide the following deliverables to your instructor:

 

SECTION 1

 

    Lab Report file, including screen captures of the following:

 

    Contents of the search warrant in Adobe Reader
    Completed Chain of Custody form in Adobe Reader
    Contents of the 0002665_hash.csv file
    Contents of the RecycleBinEvidence_hash.csv file
    Contents of the MyRussianMafiaBuddies_hash.csv file
    Contents of the Nice guys_hash.csv file
    MD5 and SHA1 values for the MyRussianMafiaBuddies.txt file
    MD5 and SHA1 values for the Nice Guys.png file

 

    Any additional information as directed by the lab:

 

    Describe how the hash values produced by E3 for the incriminating files compare to those produced by FTK. Do they match?

 

SECTION 2

 

    Lab Report file, including screen captures of the following:

 

    Contents of the suspicious email file in the Display pane
    Two hash values for the suspicious email file
    MD5 field in the Result Viewer
    MD5 value produced by E3.

 

    Any additional information as directed by the lab:

 

    Describe how the hash value produced by Autopsy compares to the values produced by FTK Imager for the two .eml files.
    Describe how the hash value produced by E3 compares to the values produced by FTK Imager for the two .eml files and the value produced by Autopsy.

 

SECTION 3

 

    Lab Report file, including screen captures of the following:

 

    Hash values for the Evidence_drive1.001 file

 

    Any additional information as directed by the lab:

 

    Define the original file names and file paths for each of the three files.

<br />
<p align="center">
<img src="https://i.imgur.com/DzxQfni.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/3DgRHBr.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/0F4Vx2N.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/kqMrt1f.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/4UOA6lP.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/GxHK1we.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/UEl9Rye.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/pyINs8h.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
v
