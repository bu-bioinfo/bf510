---
permalink: /
---

# BF/BI510: Institutional Racism in Health and Science

Historically, scientific theories and methodologies have been inappropriately,
and sometimes fraudulently, employed to provide justification for establishing
and maintaining social, economic, and racial hierarchies, resulting in
centuries of dehumanizing and unethical practices toward certain groups,
especially against Black and Indigenous People of Color (BIPOC).
Unfortunately, many of these pernicious ideas persist, such that they hinder
opportunities of BIPOC in Science and exacerbate their health outcomes. 

This course traces the historical roots of racism in science through to its
modern manifestations, examines the harmful consequences on victims' health
outcomes, and presents ideas, approaches, and practices to ameliorate and
eradicate the presence of racism in our institutions.

**Semester:** Spring 2023

**Location:** BRB 121 (5 Cummington Mall)

**Time:** Tues/Thurs 12.30PM - 2.30PM

<a id="contents"></a>Contents:
* <a href="#instructors">Instructors</a>
* <a href="#objectives">Course Objectives</a>
* <a href="#prerequisites">Prerequisites</a>
* <a href="#schedule">Schedule</a>
* <a href="#the-instrument">The Instrument</a>
* <a href="#grading">Grading</a>
* <a href="#final-project">Final Project</a>
* <a href="#resources">Resources</a>
* <a href="library.html">Course Library</a>

<a id="instructors">
## Instructors <a class="tiny-link" href="#">Top</a>

### Lead Instructor
Melisa Osborne, Ph.D. (she/her)

Research Scientist and Segrè Lab Manager, Bioinformatics Program

Research Assistant Professor, Graduate Program in Bioinformatics

* *Office Location:* Segre Lab (LSEB Room 101A)
* *Office Hours:* By Appointment

* *Email:* melosbor at BU dot edu
* *Twitter:* @MelisaLKO

### Teaching Fellow
Mae Rose Gott
   
* *Office Location:*
* *Email: gott at BU dot edu*

### Co-instructors

* Felicity Crawford (she/her)
* Adam Labadorf (he/him) - labadorf at BU dot edu
* TJ McKenna (he/him)
* Theresa Rueger (she/her)

<a id="objectives">
## Course Objectives <a class="tiny-link" href="#">Top</a>

The pedagogical goal of this course is to develop student competencies in
discriminating between fact-based conclusions and unsupported pseudoscience and
constructing empirical knowledge for themselves.  We will focus on the
empirical process behind interrogating and dismantling disinformation and
pseudoscience in the specific context of racism.  Students will learn the
skills needed at each step of inquiry and walk through a stepwise process:

1. learning about the biological background on scientific topics
2. learning to critically analyze data and critique conclusions in primary sources
3. learning to engage with one another and talk to others about their critical analyses
4. learning to apply this critical reasoning to other topics outside of race.

Beyond racism, scientific reasoning has been and still is used to form the
basis for discrimination against many different groups.  Beyond the context of
this course, students will gain the skills needed to apply this same process to
look at issues of ableism, sexism, and gender discrimination.  BF/BI510 will
prepare students to look at the scientific and popular literature and dismantle
systemic inequity from its foundations. 

### Course Principles and Classroom guidelines

In this class:
* We will cover uncomfortable ideas and information in this class
* Feeling discomfort is normal - it is a sign of challenge and growth
* It’s ok to make mistakes, so long as we are dedicated to becoming better
* This room is a space for respectful dissent
* The goal is not to agree - it is to gain a deeper understanding.

Classroom norms:
* Listen actively - respect others when they are talking.
* Speak from your own experience instead of generalizing ("I" instead of "they," "we,"
and "you")
* Participate to the fullest of your ability - community growth depends on the inclusion
of every individual voice.
* Although no one experience or example will prove accurate 100% of the time, we will
try to hear the truth in what is said instead of looking for exceptions to the case.
* Assume everyone’s good intentions but also acknowledge the impact of saying
something that hurts someone else, even if it is unintended.


<a id="prerequisites">
## Prerequisites <a class="tiny-link" href="#">Top</a>

**Graduate Student Prerequisites:** MSc./PhD. program standing in
Bioinformatics, or MSc./PhD. program standing in Biology, or MSc./M.A. standing
in BU Wheelock, or consent of instructor.

**Undergraduate Prerequisites:** CAS BI 107/108 OR CAS BI 126 and senior
standing, or consent of instructor.

<a id="schedule">
## Course Schedule <a class="tiny-link" href="#">Top</a>

<table class="table table-light">
   <thead>
     <tr class="table-primary">
       <th scope="col">Date</th>
       <th scope="col">Day</th>
       <th scope="col">Lec #</th>
       <th scope="col">Topic</th>
       <th scope="col">Assignment</th>
       <th scope="col">Instructor</th>
     </tr>
   </thead>
   <tbody>
{% for lec in site.data.schedule %}

  {% if lec.Lec %}
    <tr class="table-light">
  {% else %}
    <tr class="table-gap">
  {% endif %}
    <td>{{ lec.Date }}</td>
    <td>{{ lec.Day }}</td>
    <td>{{ lec.Lec }}</td>
    <td>
      {% if lec.Lec %}
        {% if lec["Topic Slide Link"] %}
          <a href="lectures/{{ lec["Topic Tag"] }}.html">{{ lec.Topic }}</a>
        {% else %}
          {{ lec.Topic }}
        {% endif %}
      {% else %}
          {{ lec.Topic }}
      {% endif %}
    </td>
    <td>
        {% if lec.Assignment %}
            <a href="assignments/{{ lec["Assignment Tag"] }}.html">{{ lec.Assignment }}</a>
        {% endif %}
    </td>
    <td>{{ lec.Instructor }}</td>
   </tr>
{% endfor %}
   </tbody>
</table>

<a id="the-instrument">
## The Instrument <a class="tiny-link" href="#">Top</a>

![The Instrument](assets/images/the_instrument.png)

“The Instrument” is a tool we are developing in this class to help identify
hidden biases in a text. It is a structured approach to reading a text that has
the following phases:

1. [**Annotate**](assignments/annotate.html) -  label key words, phrases, or sentences with a controlled set
   of hashtags

2. [**Analyze**](assignments/analyze.html) - answer a set of short answer questions designed to identify key
   aspects of the text

3. [**Synthesize**](assignments/synthesis.html) - write a short narrative reflection about the article guided
   by a set of scaffolding questions

We will apply The Instrument to readings throughout the course. A more detailed
description of The Instrument is found [here](the_instrument.html).

<a id="grading">
## Grading <a class="tiny-link" href="#">Top</a>

**Weekly annotations in Perusall (50% of grade):** Students will submit annotations of the
weekly readings that will be used to assess participation and engagement.

**Three case study reflections (20% of grade):** There are three case studies
assigned to readings throughout the semester.

**Peer review activities (10% of grade):** Students will review their peers’
final project presentations during class time in the final week of the course.  Peer reviews will be submitted using a simple google form.

**Final Project (20% of grade):**  
Each student (either individually or in a group) will complete a final project

   
<a id="final-project">   
## Final Project <a class="tiny-link" href="#">Top</a>   
   
**Purpose:**

In this class, we cover many different themes that show how systemic racism is manifested in our institutions and society - especially in science and medicine.  It can be discouraging to hear about how entrenched inequity is in modern systems and to learn about how extensive the history that established the system is. For the final project, we want you to think about what equitable science and medicine means to you and build a project that is around addressing or learning more about that topic.  You will apply the methods you used in your case studies to a larger project.  Select one of the themes covered in class, or pick one of your own, and select 3-5 articles or other sources to integrate together into a coherent synthesis project. Sources may include scientific articles, journalism, editorials, books, podcasts, or other media. The format of your report is flexible, ranging from traditional research paper to more creative forms as described below. This project aims to leverage your own experiences (personal and in this course) and create something that can be shared broadly (with your approval).
   
**Potential Guiding Questions**

   What is the story you are telling with your synthesis? 
   
   What are you using to tell your story? Data? Science? 
   
   Who is your audience? 
   
   What do you want your target audience to learn from your project?
   
   A new way of thinking about your topic? Facts? A new way of looking at the world? A story they feel compelled to share?
   
   How will you make sure your message is clear?
   
   What examples are you choosing to use? Metaphors? Images? Audio or video excerpts? 

**Tasks:**
   
   Project Proposal: 1 page summary of project topic (see Blackboard for submission dropbox and full guidelines)
   
   Project Presentation to the class: short (10min) presentation to the class about your topic and takeaways (informal; last week of class)
   
   Peer review: Google form feedback to your peers regarding the in-class presentations (in class; bring a device to fill in google form in real time)
   
   Final Project Submission: Submit your final project (Blackboard)
   
**Potential Formats**
  
Option 1: Traditional Research Paper (~5 pages for written report)

   OR

Option 2: Non-traditional Synthesis of Learning. Possibilities might include (but are not limited to) 

**Book** - Students create a children’s book, mini-textbook, handbook, comic, or other kind of book. These can be done on paper or created with apps like Book Creator.

**Google Tour** - Using Google Tour Builder, students can create customized tours that combine photos, text, and targeted locations on Google Earth. These could be used to create tours that explore current events, historical periods or phenomena, science or geography topics, global research topics, students’ personal histories or future plans, or completely fictionalized stories that take place in various locations around the world. 

**Infographic** - On paper or using a tool like Piktochart, have students create an infographic to represent or teach about an idea or set of data. 
Museum, Library, or Multimedia Collection: Have students curate a collection of artifacts representing a curricular concept, along with their own written captions, in a Google Slides presentation. Two fantastic resources for gathering these artifacts are the Smithsonian Learning Lab and the Google Arts & Culture website.

**Podcast** - Have students use the recording tools mentioned in the “Audio” section above or an app like Anchor to record a podcast where they express an opinion, tell a story, or teach about a content-related topic. If students have a lot of material, they can break their podcast into multiple episodes and do a series instead.

**Sketchnote** - Have students create a sketchnote to represent a content-related topic using paper or with a drawing app like Sketchpad.

**Video** - Students can create their own videos as creative, informative, persuasive, or reflective pieces. These can be public service announcements, commercials, mini-documentaries, instructional videos, short feature films or animations, or TED-style talks. Tools for creating these can range from quick response platforms like Flipgrid, to screencasting tools listed in the previous section, a tool that creates stop motion videos like Stop Motion Studio, or simple online video creators like Adobe Spark. 
   
**Website** - Using tools like Weebly, Wix, or Google Sites, have students develop a website to document a long-term project or teach about a particular idea.
   
**Criteria for Success**

   This project will...(1) ask you to show your knowledge (2) encourage creativity, risk taking (3) require peer feedback, incorporation of your peers ideas & critiques
   
   This project will NOT... (1) have a standard checkbox rubric (2) be a ‘recipe’ style assignment where all projects look the same (3) be an assignment that only your professor sees and then gets filed away in a folder

   
<a id="required-texts">
## Required Texts <a class="tiny-link" href="#">Top</a>

Course texts are available for purchase via the Boston University
bookstore and are on reserve at Mugar Library.  Scanned PDFs of chapters are also available through Perusall.

“[Superior: The Return of Race Science](https://www.goodreads.com/book/show/42042093-superior)”
by Angela Saini. Beacon Press, Boston, MA 2019. ISBN-13: 978-0-8070-2842-1

This course will use open access primary research articles as the for many
required readings. PDFs of all articles will be made available on the course
Perusall website.

<a id="resources">
## Resources/Support/How to Succeed in This Course <a class="tiny-link" href="#">Top</a>

### Office Hours

By appointment.

### Office of Disability and Access Services

The Office of Disability and
Access Services (25 Buick Street, Suite 300) is responsible for assisting
students with disabilities. If you have a disability, you are strongly
encouraged to register with this office. Lecture hall and discussion rooms are
accessible and ADA compliant.

### Learning and Testing Accommodation
Boston University complies with the
Americans with Disabilities Act and Section 504 of the Rehabilitation Act. If
you are a student who needs academic accommodations because of a documented
disability, you must present your letter of accommodation from the Office of
Disability and Access Services directly to the instructor as soon as possible.
If you have questions about documenting a disability or requesting academic
accommodations, contact the Office of Disability and Access Services. Letters
of accommodations should be presented as soon as possible to ensure that
student needs are addressed from the start of the course. Instructors are not
able to provide accommodations without documentation from Boston University's
Office of Disability and Access Services.

### Support from the Instructor

Finally, if you tell me that you are having
trouble, I will not judge you or think less of you. You do not owe me an
explanation of your health (physical or mental) or the health of your loved
ones; but you are welcome to tell me and I will listen. Even if I can’t help
you directly, it is likely that I know someone who can. If you need help or
more information, please ask, and I will work with you.

<a id="policies">
## Community of Learning: Class and University Policies <a class="tiny-link" href="#">Top</a>

### Diversity, Inclusion, Anti-racism

This course is a judgement free and
anti-racist learning environment. Our cohort consists of students from a wide
variety of social identities and life circumstances. Everyone will treat one
another with respect and consideration at all times or be asked to leave the
classroom (physical or virtual).

The instructors of this course pledge to:

1. Learn and correctly pronounce everyone’s preferred name/nickname

2. Use preferred pronouns for those who wish to indicate this to me/the class

3. Work to accommodate/prevent language related challenges (for instance I will avoid the use of idioms and slang)

### Attendance

Per university policy, this class is held in person.  However, attendance is not used as a criterion for assessment in this course.  
Zoom links and recordings will be made available during/after each session to accomodate all learners.
   
### Policy on Religious Observances

Due dates can be revised for documented
religious observances according to the specifications of the University Policy
on Religious Observance
(http://www.bu.edu/ctl/university-policies/policy-on-religious-observance/).
Please make sure to communicate about religious observances as far in advance
as possible (and no later than one week before the observance, per university
policy) so that accommodations can be made.

### Assignment Completion & Late Work

Assignments will be submitted on BU Blackboard and are due by 11.59.59PM on the listed due date.  
   
### Illness and Assignment Deadlines

We hope that all of you will remain
healthy throughout the semester and are able to fully engage and participate in
the course. If you do unfortunately become ill, we require that you follow the
protocols mandated by the University under those circumstances. The course
attendance and engagement policies already reflect substantial flexibility to
allow for absences of short to moderate length due to illness. Please make
sure to contact your instructor about any absences that will last beyond a
couple of days. In the case of a prolonged illness that is not already covered
by the course absence policies, we will work with the CAS Dean's office to
determine the best course of action for any given student.

### Academic Conduct

The community at Boston University has adopted the
following Academic Conduct Code: “All students entering Boston University are
expected to maintain high standards of academic honesty and integrity.”
Obviously, the full text is more detailed. The expectation is that you will
adhere to this code, as your instructor pledges to do as well. For more
information, please visit this website:
http://www.bu.edu/academics/policies/academic-conduct-code/. In keeping with
this code, cheating, plagiarism, or any other form of academic dishonesty will
not be tolerated (ACC III) and will be referred to the Dean’s Office.

### Proper use of Online Resources

Students at Boston University are required to abide by all regulations
regarding academic integrity and conduct, including the proper use of
technology and digital resources. Course materials are provided by faculty for
your personal use in the course only. Any other use of these materials
including, but not limited to, posting of materials online in forums or
websites, is a copyright violation and a violation of the academic
conduct code. Additionally, materials submitted for course credit (papers,
exams, etc.) are similarly not permitted to be used or posted.

### COVID-19 Responsibilities and Regulations

We are all in this together, and we are committed to offering the best learning
experience possible given the need for safety. To do this, we need your help.
We must all be responsible and respectful. Faculty, staff, and teaching fellows
will wear masks during class and other meetings to protect you.  While masks are 
not required in classrooms (per University policy), the University recommends
that people, especially those at risk of serious infection, use high-quality masks
in crowded locations or if they’ve been exposed to someone with COVID.  We also ask 
that you follow the safety practices recommended by
the CDC outside the classroom, including all state and university guidelines
regarding sheltering in place while feeling ill, testing, quarantining, social
contacts, and gatherings. If you cannot follow these guidelines, be responsible
and respectful: do not show up for in-person learning. Do not put your
classmates, staff and instructors in danger. We will work to our utmost to 
accomodate you if you need to miss an in-person session due to illness.
   
See also: https://www.bu.edu/articles/2022/bu-fall-covid-and-monkeypox-protocols/   

### Copyright Laws and Protection

The syllabus, course descriptions, lab manual, and all handouts created for
this course, and all class lectures, are copyrighted by the course instructors.
The materials and lectures may not be reproduced in any form or otherwise
copied, displayed or distributed, nor should works derived from them be
reproduced, copied, displayed or distributed without the written permission of
the instructors. Infringement of the copyright in these materials, including
any sale or commercial use of notes, summaries, outlines or other reproductions
of lectures, constitutes a violation of the copyright laws and is prohibited.
Please note in particular that distributing, receiving, selling, or buying
class notes, lecture notes or summaries, lab reports or related materials, or
similar materials both violates copyright and interferes with the academic
mission of the College, and is therefore prohibited in this class and will be
considered a violation of the student code of responsibility that is subject to
academic sanctions.

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
