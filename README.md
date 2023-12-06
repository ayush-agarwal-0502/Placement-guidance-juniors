# Placement-guidance-juniors

Hi, Im Ayush Agarwal , from IIT BHU ECE (Electronics ) 24 

You probably opened this link cause you are looking specifically for infoedge ds based experience, or few months away from placements looking for how to prepare for data science roles accordingly (No I’m not introvert, but I’m usually busy so I might have sent ya this link, feel free to ping me after reading this for a quick chat, you can reach me through my linkedin ) , or a junior looking for ml guidance , so I made this repo . Do star the repo or tell me if u find it useful , took me some decent time to write all this :) 

## About me –

I got into Infoedge as Data Scientist , had 12 shortlists and 2 off campus opportuinities 

Shortlists – Infoedge DS , Sprinklr DS, FPL Technologies DS, JM Financials DS (DS is data science) , AspectRatio Analyst (DA is data analyst)(waitlist) , ZS consulting, Samsung Noida SDE , Micron Core ECE , Qualcomm core ECE , Flipkart AMBA (Assistant Manager business development profile) (managerial role) , ICICI management trainee (managerial role) , Sprinklr Product Analyst (Product Management role) 

Off campus – Google Hardware (reached till round 3(final round)) , Tata Elxsi (Mechatronics/Automation engineer)(reached till final round) 

So I am multifielder , meaning I had experience across various domains and profiles 

## Profiles on campus and my intuition on them – 

* Data Scientist – needs ML knowledge which I will explain below . ur target companies are – navi , hilabs , infoedge , sprinklr , fpl , publicis sapient . should know dsa too since some ask dsa in 1st rounds , then sde people crack it , and then the sde people cant answer well in interviews leaving the companies disappointed 
* Data Analyst – excel , sql , graphs , data interpretation needed . companies – axxela , axtria , citi , futures first etc (I don’t remember many but there are tons) . Case studies and guesstimates asked 
* Product Management – also comes under names like apm (associate product manager) , product analyst (pa) . This is a business role that comes after MBA usually . Few ask you to make decks like Flipkart APM and Hilabs APM (hiring numbers very less in these ) . Other few ask you aptitude , product sense etc . more Companies – sprinklr pa , meesho apm , medianet pa etc . In interviews there will be emphasis on product design , RCA (root cause analysis), product cases etc 
* Managerial role - This is a business role that comes after MBA usually. Honestly , very small profile , nobody even told me this profile exists , and there is no hard skill they test . you should have good English , good communication skills , be able to cook up and present stories well and have business acumen . Even Im not sure what they want , but about 10% of iim prepare for this role . people skill is a key here . companies – flipkart am ba , icici gm 
* Consulting - This is a business role that comes after MBA usually, rather I would say MBA colleges ki “coding” . Black coats, good exposure , foreign travel and long work hours . companies – exl , zs . should prepare for guesstimates cases . should remember frameworks for all types of cases like RCA (root cause analysis) , market entry , profitability and prepare aptitude and English well . 
* Core ECE – I made a whole github repo last year after I got my intern in nvidia – github ayush-agarwal-0502 electronics-guidance-freshers . Verilog , digital electronics , mosfets vlsi etc 
* SDE- coding . coding . coding . do dsa , os , oops , dbms , computer networks (cn) (start watching gatesmashers atleast 6 months before if u want sde only). Candidate may do system design (low lld and high hld) and machine coding if they have time and are preparing specially for this .  Ask a coder for tips , I didn’t have much intrest here so Ill skip this . joboverflow for questions , interviewbit for interview practice , leetcode for coding , gfg for article might be useful for you

Scope har jagah hai , har profile ka apna apna scope hai , cant emphasise it enough - don't blindly fo into SDE !!!! Explore , see what you like and choose your career accordingly . Even in the worst case you would still earn enough money to have a decent life as compared to any non iit (no offence meant) its just that relatively thinking about money makes people feel low , so use this freedom and do what you really like , after all you gonna do the same thing for 8-10 hours everyday in your life . Also consult more seniors according to which profile you preparing for as my explanation wont be exhaustive :) 

## Infoedge experience –

Paper had 40 mcqs , all on mixed concepts , I don’t remember much of it honestly 

Then there were 5 rounds of interview lasting almost 5 hours 

First I will give overview of the rounds then tell about the questions 

First and second rounds were continuous grilling on variety of topics . They made sure to ask questions from SQL, Python, ML, DL, Statistics, Probability, Linear Algebra 
Third round was ML coding round on a colab notebook made by the interviewer 
4th round was case study and background round 
5th round was HR round 

There were lots of questions, some questions I remember are – 

Probability and statistics – Bayes theorem , formula for bayes theorem , assumptions behind bayes theorem (mece – mutually exculsive collectively exhaustive events) , how will you use it in real life (basically I directed this question to naïve bayes theorem), they also asked me which distribution can be used for modelling number of customers coming or something like that (the question was related too poisson so I said poisson distribution ) then they wanted to know what all poisson distribution could model (so I explained about how it can be used to model any count data, number of customers coming in shop ,number of cars passing etc , and then took them towards GLM and poisson regression , they were satisfied) ,they asked geometric distribution or something which I didn’t know then they asked me to make fn for probability that it will take n failures before first success ( I took the assumption that events are Bernoulli, then derived it on the spot , then when I came with the final answer they said yeah this is called as geometric distribution ) , then they asked what is linearity of expectation (basically E(aX+bY) = aex + bey ) , p value and alpha significance level

Linear Algebra – Rank of matrix, Null space of matrix (linear algebra is the only topic which only infoedge and no other company asks , if you want to go in infoedge prepare this also)

Deep Learning – this was the most drilled section . They asked me about vanishing gradients , exploding gradients, how to avoid it (xavier, he initialization for relu and tanh respectively I said) , weight decay , how to avoid overfitting in neural networks (dropouts) , what is learning rate , how to adjust learning rate , intuition behind how neural networks train and how backpropogation works, They asked me what to do if neural network gets stuck at local optima (you rerun it again and again and take the lowest loss fn value iteration )
For CNN side , they asked me to explain it (I explained the filters , stride , padding , 3 parts convolution activation pooling and n+2p-f/s+1 vaala formula they were content with me after that) they asked me what max pooling is , they asked whether CNN is rotationly invariant or variant (whether it can work on rotated images or not) , whether it is translationally invariant or not . 
They asked me what deep learning model to use for time series (then I explained them about rnn gru lstm and bptt (backpropogation through time) low memory problems of rnn , little bit of lstm gru structure and they were content with my answer) 

In the 4th round when I said I knew bit of RL (reinforcement learning also) , they asked me bit on that also so I explained environment agents and reward functions and policies for learning and Markov models and DQN algorithm 

Classical ML – They asked me how I can reduce overfitting in trees (pruning) , 
as my project has PCA and t-SNE , they asked me how PCA works (I explained SVD Singular Value Decomposition Scree plots and % explained variance and linearity and how it’s a deterministic algorithm , they were content with my answer) , then they asked about t sne (I explained it was made by geoffery hinton in 2008, successor to sne algorithm explained about how it’s a non deterministic dimensionality reduction algorithm , how it can capture non linear relations like swiss roll datasets also , how it tries to preserve neighbours in projected lower dimension and thus good for visualizing clusters, little bit on perplexity also ), then they asked me about LDA (Linear Discriminant Analysis alg or something, I explained them how it does dimensionality reduction while maximise fisher lda formula and increasing separability of clusters , how its deterministic and linear algorithm etc) 

They asked me bit on Markov chains also (I guessed it was about FSM diagrams and transition probabilities and Markov chain is related to chain of events to which they replied yes that’s correct) 
In 4th round , they asked me what is heteroscedasticity (opposite of homoscedasticity) and how we can model data using linear regression which disobeys the homoscedasticity assumption (I answered that I would use Generalized Linear Models (GLMs) and then model the variance also as a linear combination of inputs and use this model . Although they said they were looking for some transformation to make it homoscedastic (I jokingly said standardize it) they were supportive of the GLM answer too) 

They asked what SVM is (then I explained on svm , hinge loss , kernels , and how kernels project datapoints into higher dimensions to find hyperplane and linear separablity , bit explanation on support vectors and what margin is ) 

They also asked me a bit on multicollinearity , how to detect it and how to avoid it (I answered about VIF variable inflation factor , 1/1-R^2 , the intuition of multicollinearity , dropping columns to avoid it )

In the __ML coding round__ , the dataset was on MBA students , we were given few numerical columns and categorical ones , and we had to predict status of placement and salary column was also given . Documentation was allowed but yeah its not that hard to remember some of the code also if you really are an ML person it just comes . They asked me to predict status of placement using other columns , I could see that  Had to check missing values (there were none) then they verbally asked how would you have dealt if there were (I explained dropping , imputing mean median , imputing mode for categorical , or using xgboost imputer for filling missing values, and I wrote it in comments also so that they could keep track ) , then we had to check outliers . But Beware , they were checking presence of mind , since all of the data was meant to be percentage marks in exam , they had to be in 0 to 100 range , printing data.describe showed me that values were roughly between 30 to 90 range , so I could clearly say there were no outliers . Applying box plot or z score to remove outliers would have given an impression that you rote memorized it without looking at the data , so be careful they might use tricks like this to test you . Then had to ordinal encode the categorical columns . Then had to print value counts for each column , and say that data was imbalanced . he asked me what methods can be used to tackle imbalanced and I took a deep dive into undersampling , oversampling , near miss algorithm , smote , borderline smote , adasyn etc to which he said yeah you can change the weights also for the datapoints inside the model to which I agreed . But he said that we were not expected to balance the dataset for that 1 hr . Then we plotted few seaborn box plots , and did train test split , and trained a logistic regression model , then made the confusion matrix then wrote accuracy f1 score precision and recall . 

In the 4th __case study round__ that was hardest as I was grilled until the point I said I didn’t know . First he wanted to know my background about where all I had learnt ml from and where all had I used it so I gave him a deep life on how I used rl in robotics club , computer vision experience from inter iit , got business intrests , picked random datasets to work on online , branch fest udyam bla bla bla . This was the hardest round imo (boss level vibes) and the interviewer looked quite senior also .   Then I was asked 2 case studies – If I was the sales head of Naukri dot com how will I improve the revenue . I thought a lot , then explained that revenue would come from postings of jobs by companies , so more companies means more website users and more users meant more companies so the customer segments grow symbiotically . So we can target new customer markets , we can have tie ups with colleges so that they don’t need to build their tpc portal , and students can register on our site . this would also increase our user acquisition . Imo I think he was testing bit of company knowledge too since I had to know how Naukri earns money . Then I further went to customer base expansion point , and went into how I know that France people prefer French over english , so we need to make our site multilingual and adapt it to different countries to get more customers . and the last point I made is that doing analysis of current customer bases and figuring out what our competitiors do better than us . Then 2nd case study – imagine you have all the browsing data of a customer at Naukri dot com , you have to find whether they will buy (finalize the deal) on a certain property or not ? – make features (he kept saying more more until I get stuck) I made a feature using browsing data that if someone sees most properties in 30k range and few in 20k few in 50k then they wont take 50k or 20k one . I made feature using locations and emphasized its importance by giving examples of Noida and bangalore . I made features on history of customer contacting broker , property visits arranged by them etc and the interviewer was convinced . 

The 2nd 3rd and 4th rounds were literally consecutive , happened back to back . they literally told me “__tum 5 minute issi meet me ruko hum next interviewer bhej rahe hai__” , so my tip here would be to stay hydrated and practice speaking continuously for 3 hours , since you might not get breaks . Then I went to give qualcomm round 1 (that interviewer was lowkey annoyed why I came so late and so wasn’t interested in me) . Then I came back to infoedge and gave round 5 .

In round 5 , it was HR round , they asked me to introduce myself . I focused on showing leadership and management skills now since this is HR round intro . then we talked a bit about guitar (I guess he also plays guitar lol) He asked me – what does infoedge do (and I explained about jeevansathi , Naukri , 99 acres , shiksha etc multicoglomerate , internet company etc) and the hr was happy . then they asked me – why infoedge (then I explained about how infoedge does end to end work , makes sure ML models are serving business purpose and helping real people , and they are good at ml , explained some stuff from what I saw in ppt (yes I watch ppts , yes it helps , yes I recommend my juniors watching atleast for their dream companies)  and explained about how I was impressed with the research group they menthioned in the ppt . HR was impressed with the answer . then they explained me basic stuff like 2 offices in noida , 4 day wfo 1 day wfh etc . round was done in 15-20 minutes and was pretty chill . 
Finally I was taken to the TPR room and he said – koi aur interview hai ? chill kardo usse , congratulations and that’s how it finished : ) 

## Flipkart AM BD (Assistant manager business development ) 

The test had mostly English , very less aptitude , and 10 economics questions of exact same type – if at 20 dollar price you could sell 100 and at 21 you can sell 90 at what price will you have max revenue and how much is the max revenue . answer to it is that it will be a parabola – R(x) = (100-10x)(20+x) and you can find maxima easily , I remembered it from my jee time so was very easy for me . 

I was confused while going to the interview since I was told I got infoedge ds in 1-1 and slot 1 results were expected like 3-4pm but didn’t come so I was panicking but decided to sit for 1-2 anyways . (slot 1 result came next morning , a little heads up would have been nice but yeah ok)

The interview started with interviewer giving interview and he was from clustering department in flipkart where he clusters customer segments and decides stratergies . I had my project – starbucks customer segmentation so I pretty much glowed up . 

I gave my intro explaining how my intrests went from engineering slowly into management . then he said lets start with your project starbucks customer segmentation . (obviously) . He asked mw the story behind it , and we discussed business models where we earn money from interest on the money deposited by the customers . He was satisfied with my knowledge of finance . 
I was explaining k means and PCA but the interviewer was not interested in tech at all and asked me to stop on that 

Then he had questions –

You would have chosen few important features out of the 39 features , what were the important features – so I explained him how pca creates a lower dimension version of actual dataset and the axes represent a mixture of the original features 

What were the segments formed – I took him to my github page and was explaining him the clusters . 

After getting to know the clusters , he twisted and made more questions – imagine we have 3 clusters as you have in ur project – 1 grp which is regular office goers , 1 is discount chaser , 1 is old ppl who come irrespective of offers , which one will you expand , I said that these decisions should be based on the revenue generated from each cluster and went for the 3rd cluster using my intuition and he agreed to my answer saying that he thinks the same . Then he wanted me to know which cluster to expand next – then I told him office goers – and took the discussion towards cac and word of mouth marketing strategy , explained him how office goers carrying our starbucks cups would literally be a free edvertisments for us (one of my strengths is marketing , I have good intuition on marketing strategies so I took the discussion to that side) We had some discussion on marketing strategies and he agreed with my answers . He also explained me that in flipkart , customer acquisition cost is pronounced as kaaq . I told him that we can test a control system and reduce the number of discount offers given to regular customers and although I was shy about saying negative things about customer , he reinforced me by saying that in real life its not just about the comfort of customers , we have to optimize our monetary resources in such a way that we can serve larger customer base more efficiently , and agreed to the marketing strategy I designed . 
Then he wanted me to explain how I will market to these segments , how I see that in future , and I did that and he was happy . 
Then he said – you look like you have a ML or analyst background , cause all this work is done by analysts in flipkart , why management , and I took back on this question by saying that if this project ML part was developed by someone else and I just made the strategies , would he have let me sit in the interview , to which he exclaimed baat to sahi hai tumhari , sahi baat hai . 

Imo interview went very well , pretty much like a quick 40 minute chat , cause I had good business acumen . I suggest my juniors who are preparing for business roles to read finshots and grow articles daily . 

After that as soon as I walked out I was informed that my infoedge ds offer letter has been finalized and I cant sit for slot 2 , so I couldn’t move ahead with flipkart , to which I happily agreed and went back to hostel . 

So takebacks – prepare project well , and have a good business acumen for this role , tech wont be asked . 

## Data Science 

Andrews NG course , Kaggle course, Krish Nair youtube channel , statquest, and lots of practice by solving standard datasets :) Also cassendra and mosaic from Udyam (ECE dept fest IIT BHU) (Tho beware that they just surface level touch the topics and they are not exhaustive at all , do not think of udyam as the whole syllabus !!

