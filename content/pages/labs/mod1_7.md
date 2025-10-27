---
content_type: page
description: This page contains information for Module 1.7.
draft: false
learning_resource_types:
- Laboratory Assignments
ocw_type: CourseSection
parent_title: Labs
parent_type: CourseSection
parent_uid: fc19e690-0ca7-af8b-d48d-3a5a9e329f01
title: 'Module 1.7: Probe Western'
uid: 89bac614-a063-67bb-cc05-e887c5398227
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
Modules: {{% resource_link "7f7964e4-2595-1a59-8f84-d95cdcb5de44" "1.1" %}} | {{% resource_link "0a3fc94e-dd53-6ee2-6aaf-17593e9a9a7d" "1.2" %}} | {{% resource_link "db49fca7-cdc2-5384-74da-d305fa2b13e0" "1.3" %}} | {{% resource_link "1e64ebeb-ccfc-293a-a27c-6269d1dd0c40" "1.4" %}} | {{% resource_link "57397949-c673-e872-7d34-f9eeba887214" "1.5" %}} | {{% resource_link "6b023b7d-0017-7df6-1d56-533d6e1b41e8" "1.6" %}} | 1.7

## Introduction

Antibodies are useful tools in the lab. Today you will use antibodies to detect a protein on a blot. This technique, called Western analysis, can give you information about the size and concentration of the protein in the pool that was separated by SDS-PAGE. In your case today, you will use a Western to identify the expression of an M13 protein in infected cells and to determine if phage are present in the supernatant of infected cells. In general, detection depends on which antibody you choose, and the quality of your results depends largely on the quality of that antibody.

For Western analysis, a high quality antibody can have a relatively low affinity for its target protein. This is because the target is localized and concentrated on a blot, allowing the antibody to bind using both antibody "arms" thereby strengthening the association. Even an antibody that is loosely bound to the blot under these circumstances may dissociate then re-associate quickly since the local concentration of the target protein is high. The lower limit for protein detection is approximately 1 ng/lane, a value that varies with the size of the protein to be detected and the Western blotting apparatus that is used. For most acrylamide gels, the protein capacity for each lane is usually 100 to 200 ug (that would be 20 µl of a 5-10 ug/µl protein preparation). Thus 1 ng represents a protein that is approximately 0.001-0.002% of the total cellular protein (1 ng out of 100,000-200,000 ng). Obviously proteins that make up a more significant fraction of the total protein population will be easier to detect.

Many species can be used to raise antibodies. Most commonly mice, rabbits, and goats are immunized, but other animals like sheep, chickens, rats and even humans can be used. The protein used to raise an antibody is called the antigen and the portion of the antigen that is recognized by an antibody is called the epitope. Each antibody can recognize only a small portion of its antigen, typically 5 to 6 amino acids. Some antibodies are monoclonal, or more appropriately "monospecific," and recognize one epitope, while other antibodies, called polyclonal antibodies, are in fact antibody pools that recognize multiple epitopes. We will be using a monoclonal antibody against the p3 protein today, but for the sake of completion, the origin of both polyclonal and monoclonal antibodies are described.

{{< resource uuid="13034303-257c-731e-cfe0-8f6ba6467e6a" >}}

Generating monoclonal antibodies.

To raise polyclonal antibodies, the antigen of interest is first purified and then injected into an animal. To elicit and enhance the animal's immunogenic response, the antigen is often injected multiple times over several weeks in the presence of an immune-boosting compound called adjuvant. After some time, usually 4 to 8 weeks, samples of the animal's blood are collected and the cellular fraction is removed by centrifugation. What is left, called the serum, can then be tested in the lab for the presence of specific antibodies. Even the very best antisera have no more than 10% of their antibodies directed against a particular antigen. The quality of any antiserum is judged by its purity (that it has few other antibodies), its specificity (that it recognizes the antigen and not other spurious proteins) and its concentration (sometimes called its titer). Animals with strong responses to an antigen can be boosted with the antigen and then bled many times, so large volumes of antisera can be produced. However animals have limited life-spans and even the largest volumes of antiserum will eventually run out, requiring a new animal for immunization. The purity, specificity and titer of the new antiserum will likely differ from that of the first batch. High titer antisera against bacterial and viral proteins can be particularly precious since these antibodies are difficult to raise; most animals have seen these immunogens before and therefore don't mount a major immune response when immunized. Antibodies against toxic proteins are also challenging to produce if they make the animals sick.

{{< resource uuid="2c432764-79a1-f8f5-6dcc-7a18120ec7f2" >}}

Antibody-secreting cells are first isolated from an immunized animal, usually a mouse, and then fused with an immortalized cell line such as a myeloma.

Monoclonal antibodies overcome many limitations of polyclonal pools in that they are specific to a particular epitope and can be produced in unlimited quantities. However, more time is required to establish these antibody-producing cells, called hybridomas, and it is a more expensive endeavor. Antibody-secreting cells are first isolated from an immunized animal, usually a mouse, and then fused with an immortalized cell line such as a myeloma. The fusion can be accomplished by incubating the cells with polyethylene glycol (antifreeze), which facilitates the joining of the plasma membranes of the two cell types. A fused cell with two nuclei can be resolved into a stable hybridoma after mitosis. The unfused antibody-secreting cells have a limited lifespan and so die out of the hybridoma population, but the myelomas must be removed with some selection against the unfused cells. Production of stable hybridomas is tedious and difficult but often worth the effort since monoclonal antibodies can recognize covalently-modified epitopes specifically. These are invaluable for experimentally distinguishing the phosphorylated or glycosylated forms of an antigen from the unmodified forms.

Making antibodies is big business since they can be useful therapeutics. The 2002 market for monoclonal therapeutic antibodies was estimated at almost $300 million and total therapeutic antibody market was estimated at more than $5 billion. These markets are expected to grow considerably, although successful antibody treatments may require clever engineering discoveries to "humanize" antibodies raised in other animals, as well as speedier development, well-protected patents, improvements in drug-delivery methods and cost efficient production of the therapeutics.

## Protocols

### Part 1: Probe Western Blot

1. You should retrieve the blot that you made last time and pour the TBS-T + milk solution into a 50 ml conical tube.
2. Wear gloves and cut the blot next to the markers in the middle of the blot.
3. Place the blot lanes 1-4 in one blotting container, and the other portion of the blot (lanes 5-10) in another container.
4. Add 15 ml of TBS-T + milk to each.
5. Add 15 µl of anti-p3 antibody to the container.
6. Cover the containers, label with your team color and the antibody they contain, and place on the platform shaker for 45 minutes. During this time, a representative from MIT's {{% resource_link "056b6851-801e-4a1b-ba1d-1ca5174b6bc6" "Environment, Health and Safety Office" %}} will speak with us about biosafety as it relates to cell culture work.
7. Pour the antibody solution into a conical tube, writing the identity of the antibody and the date on the tube.
8. Give the blots a quick rinse with TBS-T, enough to cover the blot (volume is not critical here).
9. Wash the blot on the platform shaker 2 times with TBS-T at room temperature, five minutes per wash. Again the volume of the wash solution is not critical.
10. Add secondary antibody (1:1000 Goat-antimouse-alkaline phosphatase) in 15 ml TBS-T and incubate on the platform shaker at room temperature for 30 minutes. During this time you can analyze your sequence data (see Part 2).
11. Wash the blot as before (rinse and two washes).
12. When you are done washing, mix 250 µl of each of the solutions from the alkaline phosphatase substrate kit into the provided tube of 25 ml 1X developing solution.
13. Add developing solution and shake on the platform shaker watching for color to develop. Rinse the blot with water when bands are evident (you should anticipate what size protein you are looking for) but before the background of the blot becomes discolored. One of the teaching faculty will scan the blot and post the results for you.

## Part 2: Sequence Analysis

Analysis of sequence data is no small task. "Sequence gazing" can swallow hours of time with little or no results. There are also many web-based programs to decipher patterns. The nucleotide or its translated protein can be examined in this way. Thanks to the genome sequence information that is now available, a new verb, "to BLAST," has been coined to describe the comparison of your own sequence to sequences from other organisms. BLAST is an acronym for Basic Local Alignment Search Tool, and can be accessed through {{% resource_link "df18dee9-b4c5-47fb-b8d5-d0ddf25d3725" "the National Center for Biotechnology Information (NCBI)" %}} home page.

The data from the MIT Biopolymers Facility is available for you to examine, by logging in to the MIT Biopolymers Facility's {{% resource_link "9f1c33d7-5642-4bf0-9e2a-ba125d58ed27" "dnaLIMS tool" %}}.

Rather than look through the sequence to magically find the relevant portion, you can align the data you just got with the standard M13KO7 sequence and the differences will be quickly identified. There are several web-based programs for aligning sequences and still more programs that can be purchased. The steps for using two web-based tools are sketched here. You do not have to perform your alignments using both programs (the results ought to be the same!!). They are both provided here for your reference.

## Align with "CLUSTAL-W" from {{% resource_link "44ae966a-dab5-4b50-85fb-37b8709dec17" "EMBL-EBI" %}}

1. The alignment program is called {{% resource_link "3faf6b8e-fc88-491d-bccc-156b234cb441" "CLUSTAL-W" %}}. It's default settings should work fine for this alignment and you do not have to enter your email address unless you want to.
2. In the box labelled "Enter or Paste a set of Sequences in any supported format: you should type ">my\_sequence\_name," and on the following line paste the sequence text from your sequencing run.If there were ambiguous areas of your sequencing results, these will be listed as "N" rather than "A" "T" "G" or "C" and it's fine to include Ns in the query.
3. On the following line you should type ">M13KO7" followed by the M13KO7 sequence from NEB's site for {{% resource_link "5ce71dc2-8ace-4354-b9e8-4f0e6c0819aa" "DNA Sequence Information" %}}.
4. Hit "run" and the sequence alignment will be available in several formats. If you scroll down the page there will be areas that are aligned. These are indicated with \* as shown here.

{{< resource uuid="7331e056-f590-51bb-d264-a0b28ec17636" >}}

1. Alternatively you can look at the data with "Jalview," scrolling to find alignments like this:

{{< resource uuid="79dff8dc-516a-edbf-4b42-e71298b9b33e" >}}

## Align with "bl2seq" from {{% resource_link "df18dee9-b4c5-47fb-b8d5-d0ddf25d3725" "NCBI" %}}

1. The alignment program can be accessed through the NCBI {{% resource_link "25d4f34b-94f0-4181-afaf-b3c80c2942ff" "BLAST page" %}}.
2. To allow for gaps in the sequence alignment, uncheck the "filter" box. All the other default settings should be fine.
3. Paste the sequence text from your sequencing run into the "Sequence 1" box. This will now be the "query." If there were ambiguous areas of your sequencing results, these will be listed as "N" rather than "A" "T" "G" or "C" and it's fine to include Ns in the query.
4. Paste the M13KO7 sequence from NEB's site for {{% resource_link "e7f47b6a-adb7-4fd4-984c-0f78806b964b" "DNA Sequence Information" %}} into the "Sequence 2" box. Numbers are OK to include.
5. Align the sequences. Matches will be shown by lines between the aligned sequences. If you find a gap in the alignments look back at your sequence data for the missing bases.

You should print a screenshot of the relevant alignment, cross reference it against your oligo design and draw conclusions in your notebook. You might want to email yourself the alignment screen shot or post it to your wiki userpage.

## Part 3: Analysis of Plaque Assay

Last time you titered the phage that had been secreted into the media while the infected cells were growing. Before you leave today be sure to count the number of plaques that arose on each plate and, if possible, calculate the PFU/ml associated with each sample. This will give you some idea if the modification to the phage genome has measurable consequences to phage production.

DONE!

## For Next Time

1. Your first draft of part 3 of your portfolio will be due when you arrive in lab next time. Email your draft to the instructors prior to arriving in lab.
2. If you are planning to give an oral presentation next time, please be sure to email your finished Powerpoint presentation to Natalie or Agi. The order in which we receive your presentations will be the order of speakers.
3. Prepare for the start of module 2 by browsing through the day 1 lab on {{% resource_link "7506446f-0ce3-4227-fbf7-0e265f4a7002" "siRNA Design and Startup in Cell Culture" %}}.
4. Familiarize yourself with cell culture work by reading {{% resource_link "0c4a53dd-bd80-b23e-4c10-da37526560e2" "Guidelines for working in the tissue culture facility" %}}.

## Reagents List

- TBS-T Tris-Buffered Saline + Tween
- monoclonal anti-p3 from NEB, raised in mouse cells
- polyclonal antimouse-AP from BioRad, raised in goat
- BioRad AP detection reagents
    - 1 ml 25x detection stock + 24 ml H{{< sub "2" >}}O with 0.25 ml solnA and 0.25 ml solnB.