<center> <h1>Introduction</h1> </center>


## Abstract

<div style="text-align: justify">
The perception and use of profanity depend on the situation and differ from person to person. While swearing is relatively common and sometimes even welcomed in a relaxed environment, the use of such language is mostly frowned upon in a workplace or public spaces. This is why we are not likely to encounter it while reading the news. Still, heated debates and unexpected events can inspire the appearance of obscene language even in more formal settings. To better understand the circumstances in which profanity appears in media, we will explore Quotebank, a large and heterogeneous dataset of quotes extracted from media articles. We will analyze the distribution of obscene quotations through time and examine their presence with respect to the attributes of the speakers who uttered them and the media outlets who featured those speakers.
</div>

<!-- <div id="container" style="min-width: 310px; height: 400px; margin: auto"></div> -->
<!-- Furthermore, syntactically identical words can be considered obscene in one language but have a completely different meaning in another language. -->
## What is Profanity?
<div style="text-align: justify">
The dictionary offers a simple definition of the word 'profanity': Profanity is a type of language that includes dirty words and ideas.

The naive approach in detecting profanity is to use a hard-coded list of curse words. However, there are glaring issues with this approach as we are restricted by the words in our list and are completely ignoring the context surounding these words. 
<!-- Futhermore, the same word can be considered obscene in one language but have a completely different meaning in another language. -->

>"Finally! A pair of great tits has moved into my birdhouse!"

Would you classify this statement as profanity? It seems that Twitter would, as the user who posted it was banned from the platform, even though a quick look at the wikipedia article for the [Great Tit](https://en.wikipedia.org/wiki/Great_tit "Great Tit") can easily explain the meaning of this statement.


Identifying profanity in text has proved to be a rather difficult task which, if not done carefully, can often result in a high rate of false positives, as demonstrated by the [Scunthorpe problem]( https://en.wikipedia.org/wiki/Scunthorpe_problem "Scunthorpe problem"). Therefore, we decided to use a pre-trained machine learning model in order to identify obscene quotes in our dataset.
</div>

## 1. Profanity in Quotebank
<div style="text-align: justify">
People curse a lot, just not in media.

Quotebank is a dataset of ~150M quotes collected from different media articles. By observing the number of quotes our model identified as obscene we can already reach our first conclusion:
> Obscene quotes are not common in media articles.
</div>
<div align="center">
<iframe width="266" height="400"  frameborder="0" scrolling="no"  align="left" src="//plotly.com/~k_beans/84.embed?showlink=false" ></iframe>
<iframe width="266" height="400"  frameborder="0" scrolling="no" align="center" src="//plotly.com/~k_beans/3.embed?showlink=false"></iframe>
<iframe width="266" height="400"  frameborder="0" scrolling="no" align="right" src="//plotly.com/~k_beans/89.embed?showlink=false"></iframe>
</div>

## 2. Zooming in 
<div style="text-align: justify">
<!-- We have uncensored all profanities by using a complex regex scheme which will allow us to to a fair analysis. -->
Isolating the profane quotes out of Quotebank leaves us with 643,209 quotes, out of which 68% have censored profanities.
Let's take a deep dive into this small subset of Quotebank.
> WARNING: Curse words ahead! 
</div>

Profanity distribution

### Does your mum or dad curse more? 
<div style="text-align: justify">
Well, it seems that around 72% of all profane quotes we found were spoken by a male speaker. Our analysis also shows that media articles are heavily biased towards featuring male speakers. Feminists are going to be all over this...
<iframe width="900" height="500" frameborder="0" scrolling="no" src="//plotly.com/~k_beans/52.embed?showlink=false"></iframe>
</div>

## 3. How does the use of profanity behave through time? 
## Can we relate the use of profanity to certain events?

# 4. Which speakers are most likely to use obscene language?
## Are there any differences with respect to occupation, gender, or age of the speaker?

# 5. Which media sources feature vulgar speakers?
## How does it relate to the nature of the sources and their role

# 6. What is the relationship between profanity and sentiment of the quotes?


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


<a href="https://github.com/epfl-ada/ada-2021-project-k-beans class="github-corner" aria-label="View source on GitHub"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#fff; color:#151513; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a>

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
