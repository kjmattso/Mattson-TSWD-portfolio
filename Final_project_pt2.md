| [home page](https://kjmattso.github.io/Mattson-portfolio/) | [visualizing-government-debt](https://kjmattso.github.io/Mattson-portfolio/Visualizing_gov_debt.html) | [critique by design](https://kjmattso.github.io/Mattson-portfolio/Critique_by_design.html) | [final project I](https://kjmattso.github.io/Mattson-portfolio/Final_project_pt1.html) | [final project II](https://kjmattso.github.io/Mattson-portfolio/Final_project_pt2.html) | [final project III](final-project-part-three) |

# Final Project Part II

## Storyboarding

I started storyboarding on a piece of paper - I find this the best way to start from scratch. I mentioned in part 1 my desire to take a top-down approach, starting broad and then narrowing my focus to a "Call to Action" by the end. Due to the initial breadth of possibilities with this topic, it's hard to know where to start. As such - I created a (very) rough draft to work off of:

#### 1. Introduce severity and prevalance of children's oral health issues - to get audience invested in topic and realize we need change!
   - Statistics on Illness/Infection
   - Statistics on Fear and Anxiety
   - List of long term consequences of childhood dental issues
     - Teeth Issues
     - Confidence Issues
#### 2. Introduce existing public health measures to show how the Government has decided to invest in this issues - build audience investmenta as well
   - Timeline visualization - make it interactive
   - But express how the problem still exists (COVID?)  
#### 3. Transition to how preventable it is! - Keep the mood happy and eager and temper the sad stats :(
   - Visualization on statistics from ADA and papers about how it is preventable
#### 4. Start call to action!
   - Supporting policy
     - Dental Therapy
     - School Based Care
   - At home care/Regular visits
     - Visualization on how to prevent!
   - Donate and support causes
     - Link to various non-profits
   - Potential link to get it on legislative agenda

I didn't end up following this exactly, but it gave me a good place to start! Now that I have some framework to work off of, I can start building visualizations.

I decided to start building out my story with the above storyboard straight into Shorthand. See the draft below:

[First Draft](https://preview.shorthand.com/apcZeDJhpTQCQcNz)

## Visualizations/Wireframes

To start making my visualizations I had to pre-clean the data. My very first step was to open the code book that youy have to reference to use the.csv from the National Survey of Children's Health. I first erased any row that did not have anything to do with Dental Health. This erased 891 questions out of 922. This left me with 31 possible questions. Having worked with this data set before, I knew there was likely some redundant data - or some columns were transformations of earlier questions. So, I went through this much closer to identify what data I actually needed and make a .csv that could be useable in Tableau, Canva, or any other software I wanted. I ended up keeping 11 columns of data. But, I still had 54000 rows of data - so a lot to work with.

I had significant additional data transformations to complete as well! A lot of missing data coded as "99" instead of "0", ruining aggregations in Tableau. Additionally, some variables were strings and needed to be converted into numbers for Tableau to register on heatmaps, etc. 

Fortunately, I was able to make most of the visualizations from the [National Survey of Children's Health](https://www.childhealthdata.org/learn-about-the-nsch). I made some of my first visualizations (the prevalence of children with cavities, diabetes, and asthma) in Canva. I made the timeline in Tableau from research I did and then inputted manually into an Excel sheet. For background images, I used Shutterstock and Unsplash. 

I made 3 Tableau visualizations: 
#### 1. An interactive timeline
This interactive timeline required me to do some research on exact dates that certain important events in the development of teh Dental practice happened. I then entered each year into an Excel sheet, with an abbreviated description for the time line, and a longer one for an interactive tool box. I built a "dummy" aggregate sum in the column to make them all on one line!

#### 2. Bar graph of treatment and income
I chose to make a simple bar graph for this data, as I couldn't show it any better! The disparities are obvious quickly, and this one was pretty simple to make clear and effective. Unfortunately the data limits how they bin income, reducing the cross comparison I could make, but nevertheless, it is still effective!

#### 3. Heatmap of outcomes
For this US map, I tapped into a different data set - the CDC's report on compliance with School Based Sealant Benchmarks. Unfortunately this was a PDF, so I did have to hand import it into a PDF. I then had to use Excel functions to transform the grades to become a a numeric value for Tableau to make a heat map. 

## User Research Protocol
My intended audience are educators and caregivers of children, but anyone without significant subject knowledge or a desire to improve public health will benefit from this! Fortunately, we have a lot of those people at Heinz! I chose two colleagues who I knew were interested/working in public health but unfortuantely I don't know many people who are caregivers for young children. 

Here were my questions:
1. Please scroll through the presentation and stop at any point if you are overly confused.
2. After finishing, do you remember anything that felt particularily out-of place?
3. Did you like the Tableau timeline? Would it be better as a graphic versus an interactive piece?
4. How about the other two - the heatmap and barchart?
5. Did the Canva visualizations easily convey what they intended to?
6. What do you think of the theme and color choices? The font?
7. Any backgrounds elements that are distracting?
8. Finally, can you recall the story?
   
The two colleagues I interviewed first scrolled the presentation and gave me their own poitners on what worked/didn't work for them. I asked them to stop at any point if they needed to talk through a part, and fortunately neither did! At the end I asked if they could immediately recall anything they felt was off or odd in the presentation. One mentioned a background photo, the other had none.

I then asked specific questions about the Canva and Tablea visualizations. We went through each together and talked abotu what worked/didn't work. They both enjoyed the Canva visualizations - but had a lot of suggestions for Tableau. One even suggested making the timeline outside of Tableau, and one wanted it flipped vertically. Unfortunately, that's not doable in Tableau (with my current knowledge at least!), but I did make the graph cleaner by adjusting the font and tool pop-up box to be cleaner. I also changed the background color so the embedding blended in easier. This also solved the problem of the background photo that was disliked by one of my interviewers!

My next questions were about the overall font and color choices. Both enjoyed the color scheme and the images chosen, and felt it fit with the project theme. They didn't feel strongly either way about the text. They also really liked the call for actions I included, and felt they were logical conclusions in the narrative. Neither had any significant red flags and just encouraged me to continue building out the narrative into next week. 

In class, I used a lot of my time to posit new visualziation ideas, and they really liked the idea of more cross-comparisons like the ones I did in Tableau. They felt it fit well in the audience. One group member had a particularily good suggestion of keepinf the theme cohesive, but varied enough to discourage viewer fatigue, and keep the audience interested. All of us agreed to continue tightening our ideal "audience" and keeping them in mind as we finalize our presentations!

With this feedback in mind, I know most of my work is filling in the "in-betweens" of my visualizations, to continue my story. I feel well prepared for my final presentation! 
