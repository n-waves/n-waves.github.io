[](#){.body-overlay}

::: {.sqs-announcement-bar-dropzone}
:::

::: {#sidecarNav}
::: {#mobileNavWrapper .nav-wrapper content-field="navigation-mobileNav"}
::: {.index .homepage}
[home](index.html)
:::

::: {.index}
[Capabilities](services.html)
:::

::: {.collection .active}
[Perspectives](perspectives.html)
:::

::: {.index}
[About](about.html)
:::

::: {.collection}
[Contact Us](contact-us.html)
:::
:::
:::

::: {#siteWrapper .clearfix}
::: {.sqs-cart-dropzone}
:::

::: {.header-inner}
::: {#logoWrapper .wrapper content-field="site-title"}
[![n-waves](http://static1.squarespace.com/static/5b4dba1c372b9677b7cf4abd/t/5b6203c6352f533e63c0b929/1564424024853/?format=1500w)](index.html) {#logoImage}
===============================================================================================================================================
:::

::: {.mobile-nav-toggle}
::: {.top-bar}
:::

::: {.middle-bar}
:::

::: {.bottom-bar}
:::
:::

::: {.mobile-nav-toggle .fixed-nav-toggle}
::: {.top-bar}
:::

::: {.middle-bar}
:::

::: {.bottom-bar}
:::
:::

::: {#headerNav}
::: {#mainNavWrapper .nav-wrapper content-field="navigation-mainNav"}
::: {.index .homepage}
[home](index.html)
:::

::: {.index}
[Capabilities](services.html)
:::

::: {.collection .active}
[Perspectives](perspectives.html)
:::

::: {.index}
[About](about.html)
:::

::: {.collection}
[Contact Us](contact-us.html)
:::
:::
:::
:::

::: {.banner-thumbnail-wrapper content-field="main-image"}
::: {.color-overlay}
:::

::: {.blog-item-wrapper}
::: {.title-desc-wrapper}
September 20, 2018

::: {.post-category}
[Applied AI](perspectivescdce.html?category=Applied+AI)
:::

::: {.post-author}
[Piotr Czapla](perspectivesd28d.html?author=5b09e46da5fcacaf1738d32e)
:::

::: {.post-title}
fastai: a library that makes deep learning accessible
:::
:::
:::
:::

::: {#page role="main"}
::: {#content .main-content content-field="main-content" collection-id="5b4e47ff1ae6cf93adb76405" edit-main-image=""}
::: {.blog-item}
::: {.meta-above-title}
::: {.entry-byline}
[[Piotr
Czapla](perspectivesd28d.html?author=5b09e46da5fcacaf1738d32e){.p-author
.author .entry-byline-link}]{.entry-author}
:::

::: {.entry-dateline}
[September 20, 2018](fastai-v1.html){.entry-dateline-link}
:::

::: {.entry-morefrom}
[[Applied
AI](category/Applied%2bAI.html){.entry-morefrom-link}]{.entry-category}
:::
:::

[fastai: a library that makes deep learning accessible](fastai-v1.html){.u-url} {#fastai-a-library-that-makes-deep-learning-accessible .entry-title .p-name content-field="title"}
===============================================================================

::: {.meta-below-title}
::: {.entry-byline}
[[Piotr
Czapla](perspectivesd28d.html?author=5b09e46da5fcacaf1738d32e){.p-author
.author .entry-byline-link}]{.entry-author}
:::

::: {.entry-dateline}
[date:long](fastai-v1.html){.entry-dateline-link}
:::

::: {.entry-morefrom}
[[Applied
AI](category/Applied%2bAI.html){.entry-morefrom-link}]{.entry-category}
:::
:::

::: {.entry-content .e-content}
::: {#item-5ba38ecf352f5302573958cc .sqs-layout .sqs-grid-12 .columns-12 layout-label="Post Body" data-type="item" updated-on="1537445721951"}
::: {.row .sqs-row}
::: {.col .sqs-col-12 .span-12}
::: {#block-59e82387bde54093f261 .sqs-block .html-block .sqs-block-html block-type="2"}
::: {.sqs-block-content}
Recently our company, n-waves, has won [Poleval](http://poleval.pl/),
national NLP competition. I'd like to share with you some resource
without which it wouldn't have been possible: the
[fastai](http://fast.ai/) library, fast.ai's courses, and the community
around them. If you're struggling with finding an acceptable service to
address your automation needs or if you are interested in applying
recent breakthroughs in artificial intelligence, then these resources
can also work for you.

Until recently, entrepreneurs that wanted to run quick experiments in AI
were doomed to use black box online solutions that were hard to adapt to
their needs. For instance, I recall how I wanted to run a quick proof of
concept and analyze the sentiment of my slack channels to quantify the
mood in the team. I couldn't find anything that would work with the
Polish language! Let alone two languages, and I knew that English
sentiment analysis at that time was somehow working!

That experience led me to believe that you need to understand deep
learning to be able to do anything useful with it.  But if you are on
your own, without a team of researchers, how you can keep up? You may
feel like a small fish that swims next to the freighter, you get scraps
here and there, but if the scrap required \$10k of computing power, then
you are out of luck.

Fortunately, the situation has changed thanks to the open work that the
fast.ai team is doing:

-   They have the most [approachable course for Deep
    Learning](http://course.fast.ai/) out there if you are on to get
    your hand dirty and get results quickly. 

-   Their new library [fastai v1.0](https://www.fast.ai/) is specially
    tuned for quick iteration and applicability that helps you do your
    research quickly.

-   It is built for entrepreneurs that want to apply deep learning to
    their business but do not have an entire data center at their
    disposal. [(A small team of student AI coders beats Google's
    machine-learning
    code)](https://www.technologyreview.com/s/611858/small-team-of-ai-coders-beats-googles-code/)

-   It differs from other frameworks in that it implements the state of
    the art algorithms by default - often, no configuration is needed.
    This gives you a way to keep up.

-   Out of the box you get best data augmentation techniques, learning
    schedules that allow for super covergence (18 mins to train
    ImageNet),  [state of the art in text
    classification](http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html),
    some of the best image classification models, all of this just 6
    lines of code away.

-   Also, you know what? It is going to have the best sentiment analyzer
    for Polish. :)

With the help of this library and the support and teaching of Jeremy
Howard we managed to win the Polish Natural Language Competition.
fast.ai is all about applicability, so we are already in talks with some
of the smart companies in Poland and Germany to apply fast.ai to build
things like:

-   Better brand monitoring tools that support not only English, but
    also other European languages,

-   Tools to extract text from smartphone quality pictures of
    region-specific documents  like retyping of recipes, invoices or
    flight tickets,

-   Deep learning supported stocktaking,

-   And finally, some models to automate law offices, with smart text
    generation and outcome prediction.

As you see there is a middle way between using out of the box inflexible
services and funding your own research team. I hope you feel encouraged
to give it a try with your own ideas if so let's [meet on their
forum](http://forums.fast.ai/u/piotr.czapla/) I'm happy to help, and if
you need a quick proof of concept you know where to find us.

\
*Photo by* [*chuttersnap*](https://unsplash.com/photos/eH_ftJYhaTY) *on
Unsplash*
:::
:::
:::
:::
:::
:::

Tagged: [Logistics](tag/Logistics.html), [HighTech](tag/HighTech.html),
[Healthcare](tag/Healthcare.html)

::: {.entry-actions}
[ []{.like-icon} []{.like-count} ]{.sqs-simple-like
item-id="5ba38ecf352f5302573958cc" like-count="4"}
[]{.squarespace-social-buttons .inline-style
system-data-id="1537445717622-TLL03GCTHIXB7TKAH95U"
asset-url="https://static1.squarespace.com/static/5b4dba1c372b9677b7cf4abd/5b4e47ff1ae6cf93adb76405/5ba38ecf352f5302573958cc/1538170601570/Frame+%282%29.jpg"
record-type="1" full-url="/perspectives/fastai-v1"
data-title="fastai: a library that makes deep learning accessible"}
:::

::: {#comments-5ba38ecf352f5302573958cc .p-comment}
:::

::: {.newer}
[Newer Post]{.prev-label}[Business applications of Natural Language
Processing
(NLP)](2018/9/28/business-applications-of-natural-language-processing-nlp.html)
:::

::: {.older}
[Older Post]{.next-label}[Video Recommendation: Application of AI in
business by Growth
Tribe](2018/9/3/video-recommendation-application-of-ai-in-business-by-growth-tribe.html)
:::
:::
:::

::: {#blogBlocks-5b4e47ff1ae6cf93adb76405 .sqs-layout .sqs-grid-12 .columns-12 .open-block-field layout-label="Blog Sidebar Content" data-type="block-field" updated-on="1532021660596"}
::: {.row .sqs-row}
::: {.col .sqs-col-12 .span-12}
::: {#block-54286aebc30ca1f2f323 .sqs-block .html-block .sqs-block-html block-type="2"}
::: {.sqs-block-content}
Our perspectives are divided to following categories:
:::
:::

::: {#block-yui_3_17_2_1_1531949107650_4023 .sqs-block .archive-block .sqs-block-archive block-type="61"}
::: {.sqs-block-content}
::: {.archive-block-wrapper .archive-block-setting-layout-list .archive-block-setting-text-alignment-left .archive-block-setting-multicolumns}
-   [Applied AI](category/Applied%2bAI.html){.archive-group-name-link}
-   [news](category/news.html){.archive-group-name-link}
:::
:::
:::
:::
:::
:::
:::

::: {#preFooter}
::: {.pre-footer-inner}
::: {#preFooterBlocks .sqs-layout .sqs-grid-12 .columns-12 layout-label="Pre-Footer Content" data-type="block-field" updated-on="1410292214726"}
::: {.row .sqs-row}
::: {.col .sqs-col-12 .span-12}
::: {#block-yui_3_17_2_1_1410291973006_4664 .sqs-block .socialaccountlinks-v2-block .sqs-block-socialaccountlinks-v2 block-type="54"}
::: {.sqs-block-content}
::: {.sqs-svg-icon--outer .social-icon-alignment-center .social-icons-color-black .social-icons-size-small .social-icons-style-regular}
[](https://github.com/n-waves){.sqs-svg-icon--wrapper .github}

<div>

</div>

[](https://twitter.com/n_waves_com){.sqs-svg-icon--wrapper .twitter}

<div>

</div>

[](https://www.linkedin.com/company/n-waves/){.sqs-svg-icon--wrapper
.linkedin}

<div>

</div>
:::
:::
:::
:::
:::
:::
:::
:::

::: {.footer-inner}
::: {.nav-wrapper .back-to-top-nav}
::: {.back-to-top}
[Back to Top](#header)
:::
:::

::: {#secondaryNavWrapper .nav-wrapper content-field="navigation-secondaryNav"}
::: {#id5b603231575d1f4e6b89d0f8 .collection}
[Imprint](imprint.html)
:::

::: {#id5b601715aa4a9979974b6f10 .collection}
[Privacy Policy](privacy-policy.html)
:::

::: {#id5b5f6e436d2a734c55c2755a .collection}
[Cookie Policy](cookie-policy.html)
:::
:::

::: {#footerBlocks .sqs-layout .sqs-grid-12 .columns-12 .empty layout-label="Footer Content" data-type="block-field" updated-on="1533146632789"}
::: {.row .sqs-row}
::: {.col .sqs-col-12 .span-12}
:::
:::
:::
:::
:::

::: {#fb-root}
:::

::: {.fb-customerchat attribution="setup_tool" page_id="1708999202523830" theme_color="#4392f1"}
:::
