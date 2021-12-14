# 1. Introduction:

## Abstract:
In October 2019, the <b>Swiss federal elections</b> took place and led to a huge paradigm shift. Almost all the parties started talking about climate change and the two Swiss green parties considerably increased their numbers of representatives in
the parliament. This phenomenon is called the <b><i>Green Wave</i></b>, and was designated <a target="blank" href="https://www.rts.ch/info/culture/10916700-en-suisse-romande-vague-verte-choisie-comme-expression-de-l-annee.html" class = "link">"expression of the year"</a>
in Romandy (French speaking part of Switzerland). Through this data story, we aim to better understand how the different <b>Swiss political parties</b> communicate their ideas to the public, e.g., which keywords and topics are most addressed. We concentrate on the six largest
parties of the last elections and observe if there is any <b>change in their communication</b> over the years and if so, if it has a relationship with the results of the federal elections.

<div id="container" style="min-width: 310px; height: 400px; margin: auto"></div>

## The databases

Twitter became a central medium of communication and is used by most of the politicians to transmit their ideas. The restriction of 280 characters per tweet forces the politicians to be succinct by compressing their ideas in order to keep only the
essential, often using recurrent keywords. It gives us a good way to grasp which topics are mainly addressed by each party and politician. Therefore, we analyze <b>163,186 tweets</b> posted by the six largest parties (listed below)
and some of their members (selected by their <a target="blank" href="https://www.tagesanzeiger.ch/sonntagszeitung/wer-hat-in-bern-am-meisten-einfluss/story/11893481" class = "link">influence</a> in the parliament). We also use the archives of the Radio Television of Switzerland
(<b>RTS</b>) to understand what are the principal topics discussed by the politicians over the years using a different medium. Finally, we compare the changes in communication of the parties with the <b>results of the federal</b> elections using the associated datasets.

# 2. Swiss parties, did you say ?

To familiarize ourselves with political parties of Switzerland, we propose a small introduction about them, with the most frequent words in their tweets (members and parties tweets aggregated):

<div class="container">
    <div class="row" style="background-color: #66be29;">
        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_UDC_logo.png" onmouseover="this.src='static/images/UDC_logo.jpg';" onmouseout="this.src='static/images/WordCloud_2_UDC_logo.png';">
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="color: #FFFFFF;">
            <div class="boxtext">
                <h2> UDC </h2>
                The Swiss People’s party (Union Démocratique du Centre in French) is a national-conservative, <b>right-wing</b> populist party. It is the party with the most members in the Swiss parliament. They fight
                for the preservation of Switzerland's political sovereignty (they are Eurosceptic) and are against mass immigration by making the asylum laws stricter. The party opposes governmental measures for environmental protection.
            </div>
        </div>
    </div>
</div>
<br>
<div class="container">
    <div class="row" style="background-color: #e52935;">
        <div class="col-lg-6 col-md-6 nopadding" style="background-color: #e52935; color: #FFFFFF;">
            <div class="boxtext">
                <h2> PS </h2>
                The Social Democratic Party of Switzerland or Socialist party (Parti Socialiste Suisse in French) is a socialist, progressive and <b>Center-left</b> party. It is the second strongest party in Switzerland. They are in favor of strong
                public services, environmental policy with climate change mitigation and social equity in an open society. The party is against policies of economic liberalization such as deregulation and capitalism.
            </div>
        </div>

        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_PS_logo.png" onmouseover="this.src='static/images/PS_logo.png';" onmouseout="this.src='static/images/WordCloud_2_PS_logo.png';">
        </div>
    </div>
</div>
<br>
<div class="container">
    <div class="row" style="background-color: #375191; ">
        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_PLR_logo.png" onmouseover="this.src='static/images/PLR_logo.png';" onmouseout="this.src='static/images/WordCloud_2_PLR_logo.png';">
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="background-color: #375191; color: #FFFFFF;">
            <div class="boxtext">
                <h2> PLR </h2>
                The Liberals (Parti Libéral-radical in French) is a liberal and <b>right-wing</b> party. It is the third largest party in the Swiss parliament. They call themselves the party of the economy and promote individual responsibility. The
                party believes that an open society and economic freedom are more conducive to prosperity, rather than a redistributive and regulative state.
            </div>

        </div>
    </div>
</div>
<br>
<div class="container">
    <div class="row" style="background-color: #84b414;">
        <div class="col-lg-6 col-md-6 nopadding" style="background-color: #84b414; color: #FFFFFF;">
            <div class="boxtext">

                <h2> Les VERTS </h2>
                The green Party of Switzerland (Les Verts in French) is a environmentalist, progressive and <b>left-wing</b> party. It is the fourth-largest party in Switzerland. Their main concerns are the protection of the environment and the fight
                against climate change. The party is often allied with the Socialist Party, sharing common values such as social equity and strong public services.
            </div>
        </div>

        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_VERTS_logo.png" onmouseover="this.src='static/images/VERTS_logo.png';" onmouseout="this.src='static/images/WordCloud_2_VERTS_logo.png';">
        </div>
    </div>
</div>
<br>
<div class="container">
    <div class="row" style="background-color: #f6a12b;">
        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_PDC_logo.png" onmouseover="this.src='static/images/PDC_logo.png';" onmouseout="this.src='static/images/WordCloud_2_PDC_logo.png';">
        </div>
        <div class="col-lg-6 col-md-6 nopadding" style="background-color: #f6a12b; color: #FFFFFF;">
            <div class="boxtext">

                <h2> PDC </h2>
                The Christian Democratic People’s party of Switzerland (Parti Démocrate-Chrétien in French) is a Christian-democratic and <b>center-right</b> party. It is the fifth strongest party in Switzerland. They advocate moderate social
                conservatism, social market economy, and balance between economic liberalism and social justice. They consider themselves to be the link between the left and the right wing.
            </div>
        </div>

    </div>
</div>
<br>
<div class="container">
    <div class="row" style="background-color: #1a1915;">
        <div class="col-lg-6 col-md-6 nopadding" style="background-color: #1a1915; color: #a5c840;">
            <div class="boxtext">
                <h2> PVL </h2>
                The Green Liberal Party of Switzerland (Parti Vert’Libéral in French) is a <b>center-right</b>, green-liberal party in Switzerland. It is the youngest and the sixth strongest party in Switzerland. They seek to combine moderate economic
                liberalism with environmental sustainability. The party promotes economic growth, but with the preservation of the environment. They encourage sustainable energy.
            </div>
        </div>
        <div class="col-lg-6 col-md-6 nopadding">
            <img src="static/images/WordCloud_2_VERTS_LIB_logo.png" onmouseover="this.src='static/images/VERTS_LIB_logo.jpg';" onmouseout="this.src='static/images/WordCloud_2_VERTS_LIB_logo.png';">
        </div>
    </div>
</div>
<br>
The parties presented above are the sixth largest parties and represent <b>90% of the Swiss population</b>.

## The first rule of Swiss Politics is: you do not talk about PVL
After this little introduction about Swiss politics, let's see <b>how much the different parties talk about the others parties</b> on Twitter.


You can select the party that you wish:

<button id="UDC-1">UDC</button>
<button id="PS-1">PS</button>
<button id="PLR-1">PLR</button>
<button id="VERTS-1">VERTS</button>
<button id="PDC-1">PDC</button>
<button id="PVL-1">PVL</button>

<figure class="highcharts-figure">
    <div id="partyGossip"></div>
</figure>

On the mainlines, we observe that parties tend to talk more about more powerful parties and parties from which they are ideologically distant. Some parties have alliances, so mentions of each other can be high, as it is the case for the VERTS with the PS. The PS being the main opposition to UDC's majority in Switzerland, they adopted a strategy of mentioning (criticizing) UDC, they talk about them nearly 6 times more than the others parties combined.

Finally, one communication strategy catches the eye: <b>don't mention the Green Liberal Party (PVL).</b>

## Who's talking ?
Aside from the information released by each party through their Twitter account, we analyze the appearances of representatives of each party on RTS. RTS is the media where a large number of the Romandy population get information about the political parties and their views. Therefore, the representation of each party on these platforms is crucial for them to convey their messages. Below is a comparison between the contributors appearing in RTS broadcasts from 2012-2015 and from 2016-2019 election years.

<div id="contributorProportions" style="min-width: 310px; height: 400px; margin: auto"></div>

> **FUN FACT**<br>
The green party uses nearly twice as many emojis than any other party. In fact, even their name on Twitter, Les VERTS suisses 🌻 contains an emoji. Their most used emoji is 🌍.

# 3. Topics to pick

## I see dead topics
In order to understand which political topics were being discussed on RTS and Twitter, we first conducted <a target="blank" class = "link" href="https://towardsdatascience.com/nlp-extracting-the-main-topics-from-your-dataset-using-lda-in-minutes-21486f5aa925">LDA topic modeling</a> using the RTS subtitles and summaries. It results in a list of topics with an associated set of word for each of them. Below are word cloud representations of selected topics with our title assignments.


<div class="grid">
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels0.png"/><p class="img__description-0">Family</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels1.png"/><p class="img__description-1">Climate</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels2.png"/><p class="img__description-2">Safety</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels3.png"/><p class="img__description-3">Army</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels4.png"/><p class="img__description-4">AVS</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels5.png"/><p class="img__description-5">Women</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels6.png"/><p class="img__description-6">Health</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels7.png"/><p class="img__description-7">Europe</p></div>
  <div class="img__wrap"><img class="img__img" src = "static/images/LDAModels8.png"/><p class="img__description-8">Economy</p></div>
</div>
These topics along with some of our creation were then used as the basis for our topic analysis below.

## Topics for each party
After running the LDA modeling, which gave an idea of 9 different topics approached by the parties on RTS, we designed the 14 topics on which we mainly focus. We drew the list of words corresponding to each topic, searching for keywords in Swiss Politics for each of them, and we made them as exhaustive as possible by filtering words with their roots in order to also include derivatives of these words and hashtags containing those words.
Below is the distribution of the topics for each party's tweets.
<div id="topicsByParty" style="min-width: 310px; height: 650px; margin: auto"></div>

This graph shows the consistency of the parties between the values they promote and their communication on social media. For example, we observe that the green parties are mainly focused on climate while UDC usually talks about immigration and Europe, and PDC mentions family more often than the other parties. Furthermore we observe that right-wing parties are used to talk about freedom while the left ones advocate for equality. For the rest of the topics, it varies for each one of them and it would be interesting to study their evolution during the last legislature.
## Are politicians really all the same ?

The political spectrum is often represented as an axis left-right, with sometimes a second axis from conservative to progressive. It is interesting to figure out how close a party is to another one. To do that, we compute the <b>similarities
    between the different parties</b> by considering the geometrical distances between them.
> Brace yourself, <b>mathematical stuff</b>:<br> In practice, we associate each word of the tweets to a vector of dimension 100 by looking at the words (the context) around them. Then, we only keep the keywords of our topics and compute the averaged
vector of all the keywords used by a given party. To conclude, we compare the obtained vectors using the cosine similarity.

The following chart represents the similarities between the parties:

<div id="heatmap"></div>

We can observe that some results are very close to what we could expect. The left-wing <b>green party is very far from the right-wing UDC party</b>, but closer to the other left-wing socialist party and the other green (liberal) party.
Surprisingly, <b>the PLR and the PS</b>, which respectively represent the right and the left, <b>are also very close</b>. A non exhaustive interpretation could be the following: both are talking about the same topics but with different and opposite
opinions.

## The usual suspects

As predicted, each party's <b>top tweets</b> represent their <b>ideology</b>.
The followers of the page will tend to retweet or follow posts which best confirm their beliefs.
Confirming our topic analysis, we can see that UDC talks about immigration, PS talks about refusing
payments from private corporations, PLR about individualism and work, les VERTS about climate, PDC
about healthcare and PVL about climate, entrepreneurship and youth.
<div class="container">
    <div class="row">
        <div class="col-lg-6 col-md-6" style="background-color: #66be29; color: #FFFFFF;">
            <div class="centered">
                <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                    <a href="https://twitter.com/UDCch/status/924285981657878528"></a>
                </blockquote>
            </div>
        </div>
        <div class="col-lg-6 col-md-6" style="background-color: #e52935; color: #FFFFFF;">
            <div class="centered">
                <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                    <a href="https://twitter.com/PSSuisse/status/805395166790094849"></a>
                </blockquote>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-lg-6 col-md-6" style="background-color: #375191; color: #FFFFFF;">
            <div class="centered">
                <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                    <a href="https://twitter.com/PLR_Suisse/status/1136942992865071105"></a>
                </blockquote>
            </div>
        </div>
        <div class="col-lg-6 col-md-6 " style="background-color: #84b414; color: #FFFFFF;">
            <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                <a href="https://twitter.com/LesVertsSuisses/status/1179754578612572163"></a>
            </blockquote>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-lg-6 col-md-6" style="background-color: #f6a12b; color: #FFFFFF;">
            <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                <a href="https://twitter.com/CVP_PDC/status/901765603471626240"></a>
            </blockquote>
        </div>
        <div class="col-lg-6 col-md-6 " style="background-color: #1a1915; color: #FFFFFF;">
            <blockquote class="twitter-tweet" data-cards="hidden" data-lang="en">
                <a href="https://twitter.com/vertliberaux/status/1108658013081088000"></a>
            </blockquote>
        </div>
    </div>
</div>

# 4. What ? The party is evolving !

## Trending topics

We are interested in how the communication has evolved over the last legislature (2015-2019); specifically, what are the main topics of each year for the different parties. The following chart represents the evolution of these different <b>topics
over the years</b>.

<b>All</b> is an aggregate of all parties Twitter data while the <b>RTS</b> data only looks at the dominant topics for each broadcast found through the LDA topic modeling. 

You can select the party that you wish:
<button id="All">All</button>
<button id="UDC">UDC</button>
<button id="PS">PS</button>
<button id="PLR">PLR</button>
<button id="VERTS">VERTS</button>
<button id="PDC">PDC</button>
<button id="PVL">PVL</button>
<button id="RTS">RTS</button>

<div id="topicsByYear" style="min-width: 310px; height: 650px; margin: auto"></div>

Globally, we observe a lot of changes over the years and three are significant:
<ol>
    <li>The topic of <b>climate</b> has largely <b>gained</b> importance during the two past years.</li>
    <li>The theme of <b>immigration</b> has <b>lost</b> importance over the last legislature.</li>
    <li>Between 2015 and 2017, the question of <b>AVS</b> (Assurance-Vieillesse et Survivants) has also considerably <b>grown</b> in importance.</li>
</ol>

These changes could be explained by recent events e.g., votations, crisis, bombing, etc... We will focus on the first and main change, the climate change. During the past years, all parties started talking about global warming
and the protection of the environment. The PLR and the PS have respectively <b>increased about 25 and 40 times their communication about climate</b> (in proportion). About 50% of the communication of the green party in 2019 is also
about climate, more than the other green (liberal) party, 36%. Thus the <i>Green Wave</i> has submerged until the twittersphere.

## Green is the new black
Studying the tweets and communication of the parties is interesting but we now want to observe whether this <b>evolution in the communication has led to a change in the political landscape</b>.  Has the growing interest in climate on social media had an impact on the results of the 2019 elections ?
<div id="electionsEvolution" style="min-width: 310px; height: 400px; margin: auto"></div>

As expected, we observe one main evolution in the results which is... The <i>Green Wave</i>! While most of the parties have decreased their seats in the parliament by one or two seats, both green parties have tripled their number of seats. <b>The <i>Green Wave</i> has struck again</b> and this time it is not on the twittersphere but in the Swiss parliament. These results show that the growth of the climate topic is not just a trend on social media but reflects the decisions of the Swiss people to vote for parties that prioritize climate.

# 5. Conclusion
Through this project, we first observe that the <b>tweets are representative of the ideologies of the different parties</b>. The keywords used, the top tweets and the topics addressed match their beliefs. Indeed, Twitter became a direct way for politicians to communicate with their followers. Moreover politicians are mostly coherent in their beliefs, whatever the channel of information. We also notice that <b>all the parties increased their discussion about climate</b>. In 2015, climate only represented 6% of the topics addressed and was only the top topic for the two green parties. In 2019, it is the main topic for four parties and represents approximately 34% of the topics addressed, which corresponds to a five times increase from 2015. Finally, <b>only the green parties increased their representation in the Swiss parliament</b> in 2019. The population preferred to vote for parties that were already talking about climate in 2015. How might this trend evolve over the next 4 years ?

<div id="adaImage" align="center">
    <br>
    <img src="static/images/Ada_Marra.jpg" height="340" width="410">
    <br>
    <b>Ada</b> Marra, Swiss politician
</div>


<br>
<footer style="background-color: #d32f2f">
    <div class="container">
        <div class="row ">
            <div class="col text-white text-center">
                <p>
                    <br>
                    Deniz Ira, Isabelle Pumford, Arthur Vignon & Robin Zbinden
                    <br>
                    <button id="ada"><b>ADA</b></button>, EPFL
                    <br>
                    <a href="https://github.com/ArthurVignon/ADA_project_RADI"><b>GitHub Repository</b></a>
                    •
                    <a href="https://github.com/alcarinn/alcarinn.github.io"> <b> Website Repository </b> </a>
                    <br>
                    <b>Theme </b>
                    <a href="https://github.com/chibicode/duo">duo</a>
                    <b>by </b>
                    <a href="https://github.com/chibicode">Shu Uesugi</a>
                    <br>
                </p>
            </div>
        </div>
    </div>
</footer>




<a href="https://github.com/ArthurVignon/ADA_project_RADI" class="github-corner"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;">
        <path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path>
        <path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor"
            style="transform-origin: 130px 106px;" class="octo-arm"></path>
        <path
            d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z"
            fill="currentColor" class="octo-body"></path>
    </svg></a>
<style>
    .github-corner:hover .octo-arm {
        animation: octocat-wave 560ms ease-in-out
    }

    @keyframes octocat-wave {

        0%,
        100% {
            transform: rotate(0)
        }

        20%,
        60% {
            transform: rotate(-25deg)
        }

        40%,
        80% {
            transform: rotate(10deg)
        }
    }

    @media (max-width:500px) {
        .github-corner:hover .octo-arm {
            animation: none
        }

        .github-corner .octo-arm {
            animation: octocat-wave 560ms ease-in-out
        }
    }

    #ada { background:none;border:none;color:white }
</style>
