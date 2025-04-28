# fit3152-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [FIT3152 Assignment 1 Solved](https://www.ankitcodinghub.com/product/fit3152-faculty-of-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119562&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FIT3152 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Information Technology

Your task

• Analyse the activity, language use and social interactions of an on-line community using metadata and linguistic summary from a real on-line forum and submit a report of your findings.

Suggested Length • 6 – 8 A4 pages (for your report) + extra pages as appendix (for your code)

• Font size 11 or 12pt, single spacing

Submission • PDF file only. Naming convention: FirstnameSecondnameID.pdf

• Via Moodle Assignment Submission.

Late

Penalties • 10% (3 mark) deduction per calendar day for up to one week.

Instructions

Submit the results of your analysis, answering the research questions and report anything else you discover of relevance. If you choose to analyse only a subset of your data, you should explain why.

There are two options for compiling your report:

(1) You can submit a single pdf with R code pasted in as machine-readable text as an appendix, or

(2) As an R Markup document that contains the R code with the discussion/text interleaved. Render this as an HTML file and print off as a pdf and submit.

Submit your report as a single PDF with the file name FirstnameSecondnameID.pdf on Moodle.

Software

It is expected that you will use R for your data analysis and graphics and tables. You are free to use any R packages you need but please document these in your report and include in your R code.

Questions

Activity, language use and social interactions in an on-line community. Analyse the metadata and linguistic summary from a real on-line forum and submit a report of your findings. Do the following:

(a) Analyse activity and language on the forum over time:

(b) Analyse the language used by threads:

We can think of threads as groups of participants posting on the same topic.

(c) Analyse social networks online:

(d) Overall considerations:

Data

The data is contained in the file webforum.csv and consists of the metadata and linguistic analysis of posts over the years 2002 to 2011. You will each work with 20,000 posts, randomly selected from the original file. The linguistic analysis was conducted using Linguistic Inquiry and Word Count (LIWC), which assesses the prevalence of certain thoughts, feelings and motivations by calculating the proportion of key words used in communication. See http://liwc.wpengine.com/ for more information, including the language manual http://liwc.wpengine.com/wpcontent/uploads/2015/11/LIWC2015_LanguageManual.pdf

Create your individual data as follows:

rm(list = ls())

set.seed(XXXXXXXX) # XXXXXXXX = your student ID webforum &lt;- read.csv(“webforum.csv”)

webforum &lt;- webforum [sample(nrow(webforum), 20000), ] # 20000 rows

Data fields given. (see the language manual for more detail and examples):

Column

Brief Descriptor Column Brief Descriptor

ThreadID Unique ID for each thread we “We, us, our” words

AuthorID Unique ID for each author you “You” words

Time Time they “They” words

WC Word count of the text of the post posemo Expressing positive emotions

Analytic Summary: Analytical thinking negemo Expressing negative emotions

Clout Summary: Power, force, impact anx Indicating anxiety

Authentic Summary: Authentic tone of voice anger Indicating anger

Tone Summary: Emotional tone sad Indicating sadness

ppron “I, we, you” words focuspast Expressing a focus on the past

i “I, me, mine” words focuspresent Expressing a focus on the present

focusfuture Expressing a focus on the future focusfuture Expressing a focus on the future

End.
