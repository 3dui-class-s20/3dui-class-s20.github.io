---
title: CS 4803/8803 3DU Grad Project Overview
permalink: /project/
layout: single
classes: wide
---

# 1. Outline
<!-- TOC -->

- [Outline](#outline)
- [Project Overview](#project-overview)
- [Before you start: IRB](#before-you-start-irb)
- [Milestone 0: Preliminary project proposal](#milestone-0-preliminary-project-proposal)
- [Milestone 1: Final project proposal + literature review](#milestone-1-final-project-proposal--literature-review)
- [Milestone 2: Implementation](#milestone-2-implementation)
- [Milestone 3: Project Presentation and Demo](#milestone-3-project-presentation-and-demo)
- [Milestone 4: Project Writeup](#milestone-4-project-writeup)
- [Teamwork Expectations](#teamwork-expectations)
- [Available Resources](#available-resources)

<!-- /TOC -->
 
# 2. Project Overview

The purpose of the project is to give you the opportunity to explore some topic in 3D user-interface software in more depth than in lecture. You are asked to propose a well grounded and motivated (and hopefully creative!) project, implement your idea, write up your work in the form of a conference-style paper, and give a final presentation/demo of your project. The project counts for more than half of the project/homework part of the grade for each of the team members, and so should represent a substantial effort, both in terms of creativity and implementation, on your part.

You have a lot of freedom to come up with a project idea. You are not limited to using the software used in the homeworks; while I would prefer that you do a Web-based project so that it can be shared and demonstrated more easily, if you want to do something not possible with current Web technologies you can use a platform of your choice (although I cannot promise we can support other platforms). 

Whatever you choose to do, your project should represent a substantial implementation effort that's motivated by, and grounded in, the principles we discuss in the class. As a starting point to finding a topic, notice that both textbooks use the same three major categories of 3D interaction: selection & manipulation, navigation & locomotion, and system control. Starting with one of those categories, your project should be grounded in the discussions we had in class and in the book (e.g., affordances, feedback, and mechanics). 

In other words, just doing a different an interaction technique that doesn't meet some need, or that has sloppy mechanics or feedback, is a bad idea. See [here](/project-ideas/) for some possible project ideas. Feel free to run ideas by the instructor if you want early feedback.

What not to do: don't come up with an idea that's just about building some application, like an email reader or a web browser, unless you're using that application to demonstrate an interesting, creative, and substantial, contribution to user interface software--new interaction techniques, interfaces, toolkit capabilities, and so forth. Remember, this class is about creating compelling user interactions, not just app building or gluing together existing software components.

Projects must be done in teams of two, and must be on a topic approved by the instructor. Depending on whether we have an even or odd number of people, we may have a single team of 1 or 3 at the instructor's discretion. It is possible that more than one team works on a related project topic. However, those teams must work separately on their projects.

You are responsible for finding team mates early in the semester. If you're looking for a partner, using the discussion forums on Canvas may be a good way to match people and project ideas into teams. Please note that I expect all teams to behave professionally with each other, and to share in the obligations of the project equally. See the section on Teamwork Expectations at the end of this document for more details. In situations where work is not shared equitably, overall project grades for individual team members may be adjusted to reflect this.

Start right now: You should begin immediately looking for a project partner and discussing possible project ideas. I suggest reading carefully through this entire document so that you understand the requirements and grading criteria for all parts of the assignment before deciding on a project topic.

It should go without saying, but proper citations and adhering to the Georgia Tech honor code are essential with this assignment. Bulk copying from a published research paper, website, etc., is unacceptable, whether cited or not. Properly citing others' work and acknowledging external references is required in all cases.

The breakdown of deliverables and grading for the project is given below.

Please see the online class schedule for due dates

# 3. Before you start: IRB

Students can only start working on their project when they have provided evidence for successful completion of relevant IRB (Institutional Review Board, which is concerned with ethical approvals for research conducted at Georgia Tech) training (CITI certificate(s) as outlined in the [syllabus](/syllabus)).

All projects are by definition class-room (educational) projects and as long as you adhere to good academic practice as attested through a successful IRB training, they are exempt from IRB approval. However, without proper IRB approval (if required by a project) the results of a project can NOT be published. Publication (for example, in form of a scientific article) typically requires IRB approval (depending on the project). Teams aiming for publication of their project results should discuss this with the professor.
 
# 4. Milestone 0: Preliminary project proposal

Your team should begin brainstorming on possible project ideas early in the semester. Feel free to look at the project ideas linked off of this page, but you do not need to limit yourselves to these ideas. You should look ahead in the class topics and readings, as well as browse relevant conference proceedings (conferences like CHI, UIST, and Ubicomp are particularly good places to look for inspiration). Other classes you're currently taking, or have taken, might also provide inspiration (example: if you're taking the grad networking class, perhaps some interesting interaction techniques designed to afford better network management). You're welcome to send initial project ideas to the instructor early in the semester for feedback.

By this milestone, you must deliver a preliminary writeup that describes the project you're planning to do. This is a preliminary proposal, because the instructor and TA may give comments or feedback about how to modify your project. For example, we may suggest changes in direction to ensure that your project aligns better with the learning goals of the class, or may suggest increasing or decreasing the complexity of the project. Proposals that are out-of-scope for the class, or that represent an insufficient amount of work, will be disallowed.

The deliverable for this phase of the project is a two-page proposal in PDF format, which outlines the motivation for the project (why it is a good idea, ideally grounded in what you've learned from the lectures, readings, or outside materials), and details on what exactly your project will do (a description of the system, or interaction technique, or whatever, as well as some details of how you think you'll implement it). You can feel free to include a few citations if they help you motivate or describe your project, but these aren't required. Images or figures may be useful in helping you communicate what exactly your proposed system will do.

This deliverable should be submitted on Canvas, by only one of the team members. Be sure to give your project a title and list the names of all partners on the team in your submission. This submission will not be graded, it's just to give an early opportunity for you to get formal feedback on your project idea.

 
# 5. Milestone 1: Final project proposal + literature review

In this milestone you'll submit your final project proposal. This written document should incorporate any feedback provided by the instructor or TA on the preliminary proposal, and should be a polished and detailed description of your motivation as well as what exactly you will deliver at the end of the semester.

In essence, this deliverable should look much like the first half of a conference paper: it should introduce your idea, provide the motivation and setup for your system, discussion of related work, and overview of what you plan to build. Illustrations may be helpful if you're proposing some GUI-based interaction technique or other visual system.

As before, you'll lay out the motivation and justification for your work—why it's a good idea. For this deliverable, however, your project idea should be fully grounded in the relevant literature from the UI Software community. This literature is expected to come from major scientific sources, including peer-reviewed conferences such as UIST, CHI, Ubicomp, Multimedia, CSCW, or others, and journals such as ACM TOCHI, IEEE Pervasive Computing, and the HCI Journal. The Georgia Tech library website allows you access to all of these for free; sites such as Google Scholar and CiteSeer are also helpful. I would expect most submissions to have 15-25 citations.

In a few well-justified cases, authoritative web sites and non-research articles may be accepted, but the large majority of your bibliography must be academic research publications. Remember: a good related work section isn't just a list of papers. You should use it to motivate your project by using the papers to explain what the current state of the art is, and where the gaps are.  Just throwing in a bunch of citations will not earn you a good score.

Your deliverable for this phase of the project is a 4-page (max) proposal in PDF format that includes the items listed above, in standard ACM format. For details, please check here (Links to an external site.) for the formatting instructions used by UIST (ignore the specification of 10-page papers, and you do not need to include the copyright information). I suggest starting from the provided template, rather than trying to retrofit into it later.  Again, only one team member should submit this in T-Square, but be sure you have both partners' names on the submission.

This submission will count for 20 points in the project grade. Grading will be based on the following criteria:

    Quality and clarity of motivation. Is the project idea well justified? Is it well grounded in principles from the class, and/or relevant literature?
    Quality and clarity of proposed project description. Is the proposed work sufficiently well described that I know precisely and in detail what you're attempting?
    Coverage and relevance of citations. Does the discussion of related work provide good coverage of the fields from which this project draws? Are the selected references authoritative, well justified, and relevant to the project?
    Format. Does the submission follow the required formatting guidelines? (Please don't ignore the formatting component of the grading! Following the correct format is important so that everyone is on a level playing field in terms of proposal length. My recommendation is to start writing from the template document.)
    Quality of writing. Is the submission well written, spell-checked, etc.?

 
# 6. Milestone 2: Implementation

Milestone 2 is the completion of the implementation of your project. As noted above, you have complete freedom in choosing the development environment (language, platform, tools) for your project. The only requirement is that you be able to fully describe that development environment and make sure you have some way to demonstrate your project at the end of the semester (see Milestone 4). Note that in most cases we won't try to run your code, especially since it may depend on software libraries, platforms, or hardware that the instructor and TA do not have access to.

For this milestone you'll submit the following deliverables:

    All source code and required libraries for your project.
    A 2-4 page written overview of your implementation in PDF. This should include a description of the work you performed (what specifically you built), a clear description of your development environment, and links to any 3rd party libraries or code that you used. You may also include screenshots or pictures of your implementation working, where appropriate. If you use code written by others, be especially clear to indicate which code you actually wrote.

Please submit all of these as a single ZIP file via Canvas. Only one person should submit the file, but be sure to include both team members' names.

The implementation portion of the project will count for 30 points in the overall project grade. This is the milestone in which we evaluate what your project actually does:

    UI contribution. How significant is the UI contribution of the project? Is the project simply an application, or does it have a substantial focus on new UI technology? How novel and creative is the system?
    Implementation complexity. Projects should represent a substantial implementation effort, at least equal to three homework projects.
    Match with proposal. How closely does your finished implementation reflect the goals you set out in your project proposal? You don't have to exactly match what you proposed, but deviations should be well justified (for example, simply not finishing a proposed feature because you ran out of time is not a good justification).

In some cases, we may award bonus points for extreme novelty or extra "polish" (such as great graphical design, or implementation of extra features that, while not contributing to the UI portion of the work, make it more useful or finished).

 
# 7. Milestone 3: Project Presentation and Demo

During the last class meetings, students will be responsible for a presentation on their project.  This will include a demonstration of your work as well as an overview of your project's motivation and implementation.

If you rely on special equipment that can't be transported to class, please bring a video and slides; if you have special logistics considerations you may schedule time for a private demo with permission of the instructor.

Note that it is your responsibility to understand what equipment is available in the classroom and come prepared! For example, most classrooms have both VGA and HDMI connections for the projector, but you should check this for the current semester. Be sure to bring your laptop power adapter.

Given that our presentation schedule is very tight, here will be a substantial penalty on the grade for this milestone if we have to reschedule due to lack of preparedness.

The presentation will count for 20 points in the overall project grade.

In this milestone we are only grading for the quality of the presentation itself, not the overall quality of your system. Presentations will be graded on the following basis:

    Clarity. Are the concepts and ideas presented clearly and cogently? Are important details skipped? Are appropriate visual aids used?
    Organization. Is the presentation well structured? Does it jump all over the place? Is it repetitive?
    Pacing. Does the presentation fit well into the allotted time? Is it too rushed? Are the presenters "stretching" the material to fill time?
    Motivation. Presentations should be understandable by everyone in the class, not just your team members. Do you set up and motivate your work well? Do you explain why it's a good idea?

You may want to do a practice talk or two in front of friends to make sure your timing is right and that your presentation does a good job of conveying your project.

 
# 8. Milestone 4: Project Writeup

The final project milestone is to do a complete writeup of your project that is in the form and style of a conference research paper. This will be an 8 page (max) paper in standard ACM format, as in Milestone 1. If you wish, you can "reuse" your material from Milestone 1 in this deliverable, as appropriate (be sure to update it if your motivation, references, or other material have changed, and of course the deliverable should describe what you have done as opposed to what you plan to do). This deliverable should be submitted as a PDF document on Canvas by one of the project members; be sure to list both members' names.

Look at some of the assigned readings from the class, or proceedings of conferences such as UIST, Ubicomp, CHI, and CSCW to see the form and style of these papers. The typical paper will have an introduction section that motivates the work, a discussion of related work, a system description (including implementation details as necessary), sometimes an evaluation, discussion section, conclusions or future work, and references. Many of these sections will be new for this deliverable. The actual sections that you might have can vary, of course, but should be plausible as a research conference paper. I suggest looking for papers that are on topics that are at least superficially similar to your project and using them as templates.

The Author's Guides for various conferences provide details on how to write an effective research paper. As an example you can check out the Review Criteria (Links to an external site.) for the UIST conference. This document details the set of criteria for how the reviewers (in our case, the instructor and any TAs) will evaluate your paper.

For a project of the appropriate scope, I would expect the final writeup will likely take the entire 8 pages to provide sufficient detail, coverage of related work, and so forth.

This portion of the submission is worth 30 points. The grading criteria are as follows:

    Quality/clarity of intro, motivation, related work discussion, references, etc. (i.e., material previously covered in Milestone 1). The sections of your paper you submitted in Milestone 1 will be reevaluated here; you can update these as you see fit, to improve the quality of presentation, or to reflect new findings or related work. This portion of the grade will reflect the overall quality and clarity of this portion of the paper.
    Quality/clarity of system description and other new material for this deliverable. Are the system and its implementation well described? Are caveats or weaknesses of the chosen approach fairly and honestly described?
    Format. Does the submission follow the required formatting guidelines? (Please don't ignore the formatting component of the grading! Following the correct format is important so that everyone is on a level playing field in terms of proposal length. My recommendation is to start writing from the template document.)
    Quality of writing. Is the submission well written, spell-checked, etc.?

 
# 9. Teamwork Expectations

It should go without saying that in a team project, I expect everyone to contribute equally. This doesn't mean that everyone has to do the same job: some may take on more responsibility for the writing, others for the coding, and so forth. But it does mean that I expect each teammate to exhibit an appropriate level of professionalism, responsiveness to their teammates, and overall sharing of the obligations of the project.

The first step toward a successful project is setting expectations appropriately. Talk to your partner early about workload and division of responsibilities. If you will be out attending a conference, let your partner know beforehand so that he or she can plan appropriately.

If you feel that a member of your project team isn't carrying his or her weight, then the first step is to speak to that person directly. I strongly prefer to rely on teammates working through these problems themselves. However, if you feel that you've exhausted these options, please make an appointment for your team to speak to me directly.

At the end of the semester, each person will complete a short "teammate assessment" form, detailing what specifically you did, what specifically your teammate(s) did, and how you feel the workload was distributed. In certain rare cases, where a strong inequity in workload or quality of work exists, overall project grades for the individual teammates involved in the project may be adjusted plus or minus up to 5 points to account for this discrepancy. In general, I do not anticipate (nor look forward to) having to do this for anyone, so please ensure that you're carrying your weight on the project.

 
# 10. Available Resources

Georgia Tech has resources available that may be useful for your project. Some highlights include:

    RNOC Lending Library. The RNOC center has a variety of hardware available for loan, including phones and tablets. Details are here (Links to an external site.).
    GVU Prototyping Lab. The lab, located in the basement of TSRB, has fabrication facilities including 3D printers, laser cutters, and more.  See this page (Links to an external site.) for more details, including how to get access to the lab.
    ACM Digital Library (via Georgia Tech Library). When accessing the ACM Digital Library (Links to an external site.) through the Georgia Tech network, you should have automatic access to most papers through an arrangement with the GT Library. Generally, Google Scholar (Links to an external site.) will be a better search tool for finding relevant prior research, however. The most salient ACM publication venues for this class are CHI, UIST, Ubicomp, and IUI.
