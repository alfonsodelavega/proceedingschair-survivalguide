# Survival Guide for MODELS Proceedings Chairs

If you're reading this, you probably have been invited to become Proceedings Chair (shortened as "ProC" in the following) for a [MODELS](https://conf.researchr.org/series/models) (or any other ACM/IEEE computer science conference) edition. Congratulations! This is a great chance to understand what happens during the camera-ready submission process from the other side. Also, we can ensure this position *will definitely* show you some of the hard work required to organize a conference that mostly goes unnoticed.

This repository contains a lot of information that we (i.e. MODELS'26 ProCs) would have liked to know before the start of our tasks. Also, this is a position that, for reasons that will soon be obvious to you, is rarely held twice. We consider that losing all the know-how gained by ProCs during each MODELS edition is a waste that makes the next ones suffer from similar (if not the same) pitfalls and challenges. We also believe part of this information can be useful for ACM/IEEE conferences other than MODELS.

The advice in this guide is organized chronologically, in the order that you are going to need it. This was fully written by humans, so expect mistakes here and there (and ask us about it). We hope you find it useful.

## MANDATORY DISCLAIMER

The information provided is, to the best of our knowledge, valid at the time of writing these paragraphs. However, it might not be applicable to your concrete MODELS edition due to some changes in the processes, or simply to the editorial alternation between ACM and IEEE. So, please verify any information in these guidelines before its application.

MODELS editorial alternates between ACM and IEEE each edition. These guidelines were created after ACM MODELS 2026, so no specific IEEE tips are given. If you are a PC during an IEEE-managed models edition, feel free to include these tips in the same fashion we have done so for ACM.

## Before the papers arrive

### Doing the CR in August is the main issue

You must understand that many people will take annual leave (or will be already on holidays when you contact them) during the CR process. So, anything that you can prepare before August will reduce delays considerably.

### Get the full list of events that end up in the proceedings

This is fundamental to keep track of some of the steps described below. Events will be published as part of the MODELS main proceedings (Research and NIER tracks in MODELS'26) or the Companion proceedings (the other satellite events and workshops). Double-check these lists with MODELS organizers so you are not missing anything.

### Ensure the Easychair events have asked for the appropriate license

Each co-located MODELS event (e.g. satellite events, workshops) will have access to the same EasyChair license as the main conference events. However, organizers of these events must ask EasyChair support themselves to obtain this license. It can be done weeks/months in advance, as soon as the event has been created in EasyChair as part of a MODELS conference. We can confirm doing it *just when you need to extract the accepted papers' metadata* will translate in delays even before the camera-ready process can be started for those papers.

Two options here:

- Ensure the event organizers ask Easychair for these licenses themselves.
- It would be better to give Easychair support a list of the co-located events, so that they can add the licenses to them in batch. Probably easier and faster than coordinating tens of event organizers, but we didn't test this.

#### ACM

These are the two EasyChair features that were needed in our case:

- Helpdesk Questions and Technical Support: useful in case things go south (we have proof of this D:).
- ACM Proceedings Management: allows exporting XML metadata in the format that can be imported into the ACM eRights system. You will know this step has been completed successfully for an event when the organizers have given both ProCs the *volume manager (ACM Proceedings)* role.

### Ensure event organizers know what you would need, and when

Event organizers might need to perform some steps after papers have been accepted in Easychair, so you can proceed with the camera-ready process as ProC. If the event already has the necessary licenses stated above and clear instructions on what to do, this can be as simple as a few clicks.

The main issue here is organizers availability (due to [August](#doing-the-cr-in-august-is-the-main-issue)). Ideally, one of the organizers of each event should be available at any point during the camera-ready process (because that is one of the reasons to have several people for each role, right?). Our advice is asking their availability during the dates you would need their help. The Workshop Chairs should help you communicate with the numerous workshops of this conference, so check their availability as well. Also, it will not hurt to ask the Workshop Chairs for their list of emails in case you need to quickly contact the organizers of a concrete event.

#### ACM

The *volume manager (ACM Proceedings)* in EasyChair can see the list of papers that have been added to the proceedings. It can also add papers marked as *accepted* in the event, but we would advice that this step is *only done by event organizers*, for reasons such as papers pending conditional acceptance.

### Help establish a common process for conditional acceptance

If no instructions are given on how papers can be conditionally accepted after attending some change requests, the organizers of each event will arbitrarily come up with their own, and each will be different to the others. This can cause delays, confusion, and doubts on whether the list of accepted papers of an event is final (we had events accepting papers *hours before the CR deadline*, to the disgrace of their authors).

We would advice discussing with PC, Workshop and Satellite events's chairs whether to allow a conditional acceptance process, and if so, to ensure its dates do not conflict with the camera-ready submission.

### Give yourself a backup window

There will be a final date at which all the camera-ready papers should be 100% complete for the editorial process to have the proceedings ready for the start of the conference. Find out that date.

Then, what that date *cannot* be is the CR deadline for the authors. There will be a handfull of papers that will not meet the deadline for too many reasons to enumerate here. So, your maximum deadline for authors (generally the companion proceedings ones) should be something between 2 to 4 weeks earlier.

### Stagger camera-ready deadlines for main and companion proceedings

This was a great idea (thanks Mehrdad!) that allowed us to learn about the CR process with a subset of all the papers. The accepted papers of the main proceedings (e.g. Research and NIER tracks) will be known way before the ones of the companion. Also, the main proceedings have less papers, so it is good to discover any issues and potential delays before the companion proceedings start. Having a difference of 2-3 weeks was reasonable.

## After papers have been accepted

### Ensure the list of accepted papers of each event is final

Double-check with the organizers of each event whether their list of accepted papers is final before processing it. Precisely, ask if there are papers pending [conditional acceptance](#help-establish-a-common-process-for-conditional-acceptance). Ask organizers to add the papers to the EasyChair proceedings.

### Camera-ready (CR) instructions

*This step can also be done while papers have not yet been accepted, we place it here because it's when the instructions are needed.*

Compose the CR instructions with the information received from the editorial (ACM/IEEE) contacts. These instructions might be different between events (e.g. due to different paper length limits). Event organizers will usually be the ones sending out this information to the accepted papers.

The [camera-ready-instructions](camera-ready-instructions/) folder contains examples of previous years.

#### ACM TAPS issue with ERights details

We updated the uploaded camera-ready instructions for MODELS'26 to emphasize the greatest source of delays during the process, at least when using TAPS for managing papers. This is the relevant paragraph:

> [!IMPORTANT]
> THE AUTHOR NAMES, EMAILS AND AFFILIATIONS YOU FILL IN THE ERIGHTS FORM WILL BE USED TO OVERRIDE YOUR PAPER SOURCES.
>
> Please be aware that ACM TAPS enforces that the details introduced in the erights form are identical to the ones present in the paper. These details include the paper title, author names, emails and affiliations. TAPS will overwrite the sources of your Latex/Word manuscripts with the details used in the form. Therefore, as corresponding author you must carefully review the information of every author in the article. Failure to do so can cause issues, such as papers not fitting in the max length anymore (due to extra vertical space required).

### Include event prefixes in papers IDs before uploading paper metadata to any other system

EasyChair allows extracting paper's metadata so it can be ingested into the required next system. For instance, for ACM this is required to fill the ERights form that need to be signed for each paper.

If exporting the data from Easychair is needed, a general tip: prefix paper ids provided by EasyChair with the event acronym (e.g. NIER-5, ME-2). This will avoid any collisions later on, and it will be really helpful to know which event a paper belongs to quickly.

### Ask event organizers about prefaces

The frontmatter of the main proceedings is easier to obtain, as few people collaborate on it. For the MODELS companion, prefaces have to be prepared by the organizers of each event, so it's better to ask this with enough time ahead. We used a Latex template to simplify the process to combine them later. The template is [in this repository](preface-template/), ask us if you are interested in obtaining the main latex document as well.

Frontmatters can be filled completely, but for paper pages. Those were filled by ACM later in our case, so we included some facilities to ease the filling of these.

### Be nice (and specific) to helpdesk supports

You will probably need to interact with the support system of some (or all) the systems that intervene in the CR process. Do be nice with them, as they're probably overwhelmed by too many issues to fix, and too many requests at the same time.

Also, being precise helps a lot. For us it even helped asking them how they will prefer us reporting things, such as recurring issues, to avoid duplicating requests on their side. We share the templates we used to communicate issues and how to fix them in the following sections.

## (ACM) Tips / Issues with their fix

Some issues we faced where very specific to the article in question having them, so we do not comment them here. However, there were a few recurring issues that took most of our efforts during the CR process. You can find them below.

### (ERights) Sent emails in batch is faulty

There is an option in the ERights system that allows to send erights form emails to all authors that have not been notified *yet*. This is useful because you will be starting the CR process for some events before others (we recomend doing so as soon as the list of papers for an event is final). However, this does not work as it says, as all authors will receive a new email, independently on whether they already received one early. Unless that gets fixed in the future, just invest 20 seconds in selecting the papers you want to send the erights form email each time.

### (ERights) Form appears duplicated

In some cases, the row for some papers appears twice or more times, with some of them completed, but some not. In our case, the reason for this was that ACM needed each of the authors to complete a separate form. So, double-check that the authors are aware of this.

### (ERights + TAPS) Form mistake, needs reset

This is usually found when the generated PDF proofs don't have the correct author names and affiliations, or when the final manuscript does not fit into the required paper length.

The culprit for this were mostly mistakes in the [ERights form data](#acm-taps-issue-with-erights-details). What make this issue cumbersome is the required steps to fix it, because neither authors nor ourselves could do it without the help of TAPS support.

Check the steps to fix this in the [erights and taps reset folder](erights-and-taps-form-reset/).

### (TAPS) How to access author's dashboard

There is no easy way to access authors' dashboards from your TAPS interface. However, this is useful, forn instance to read for pending support tickets (and sometims closing them by yourself is necessary for progress to happen).

You can access authors' dashboards by exporting the TAPS Excel metadata. Among all the column of the exported table, there is one, named `AUTHURL`, that you can use to access it, or to copy-paste it in your emails to ease the authors' part.

### (TAPS) How to sort papers by STATUS

You can click on any of the TAPS column headers to sort articles by them, except for the `STATUS` one (don't ask me why). However, if you click on the `ACTIONS` column header (i.e. the last one, where the gazillion buttons of actions are), then papers get ordered by progress. A useful thing that we were oblivious about until we accidentally clicked on that.

### (TAPS) Detect length issues eagerly sorting by pages

If you short papers by pages length, you can detect issues that might go unnoticed. Sometimes authors approved papers that exceeded their page limits, generally due to [changes in their afilliation details in their forms](#erights--taps-form-mistake-needs-reset).

### (TAPS) Paper blocked at 25%

This was a recurring issue, where the use of certain Latex packages broke the tex-to-html TAPS conversion. The issue was compounding, because having an error in this conversion blocked the CR submission for that paper, with no extra actions possible either by the authors or by us.

The only ones who could fix these blocking issues were TAPS support, and any re-upload from the authors after TAPS had unlocked the papers resulted in a re-block. So, it is important to tell the authors to WAIT until they get authorized by you to do a resubmit, if needed.

In our case, as the deadlines were approaching, it was useful to ask TAPS support to postpone HTML generation, and just include a temporary HTML stub in the proofs. That allowed the PDF proceedings to be ready on time.

### (TAPS) Word template not working

We do not have any specific recommendation for this. 100% of the 6-8 papers that tried to submit a Word-templated manuscript through TAPS failed to do so, and the solution that worked in the end was migrating the manuscript to Latex.

## Don't worry (too much)

This is an interesting role. You will probably face issues you did not expect happening at a top-level conference. However, we can ensure that if

- around [half of the 200+ papers get stuck in an out-of-your-hands](#erights--taps-form-mistake-needs-reset) block,
- all organizers of an event are on vacation during almost the whole August in completely different time zones,
- the organizers of an event tell you that their EasyChair instance might have been deleted, along with all the papers data (accepted or not),
- an author asks for the third time to change the final title of their article,
- a paper is granted conditional acceptance 24 hours before the camera-ready deadline (or a few days later even),
- a paper manages to get blocked into every step of the process, and even into the same issue half a dozen times or more,
- the last camera-ready paper to complete the full process does it 20 days after the deadline,
- you receive petitions to amend some paper mistakes one month after the proceedings have been closed,

don't worry, it will be fine in the end.

## Contributors

- [Alfonso de la Vega](mailto:alfonso.delavega@unican.es) (MODELS'26 Proceedings Chair)
- Iván Alfonso (MODELS'26 Proceedings Chair)

If you are a newer ProC and want to contribute, please either send a pull request or an [email](mailto:alfonso.delavega@unican.es), so that we can give you access to the repository.
