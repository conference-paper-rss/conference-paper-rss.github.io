# conference-paper-rss

This is a simple repo for improving (**computer science**) conference paper reading experience. We try to parse the paper information(title, abstract, url) of all the papers for a certain conference and generate an RSS XML file. You can subscribe our resource to read papers with your **PC/PAD/PHONE** as long as you have an RSS reader on it.

## Usage

You can use **any RSS reader** to subscribe our resource. In Mac, we recommend using [Leaf](https://itunes.apple.com/cn/app/leaf-rss-%E6%96%B0%E9%97%BB%E9%98%85%E8%AF%BB%E5%99%A8/id576338668?mt=12)(**NOTE: most of the emails also support RSS subscription, just Goole it**. btw, use [feedDemon](http://www.feeddemon.com/) for windows as suggested by [charlesliucn](https://github.com/charlesliucn)). If you are using Leaf, it should look like follows:
### First, subscribe to the resource:

![leaf-sub.gif](leaf-sub.gif)

### Second, enjoy reading:

![rss-example.gif](rss-example.gif)
### rss source
Use any rss reading client (Leaf in Mac) to subscribe to the following rss resource.
> Currently, we parse papers from the most recent 2 years. earlier years are not included (but you can run our code to parse it by yourself).
+ NIPS:
  + https://conference-paper-rss.github.io/rss_source/nips2019.xml
  + https://conference-paper-rss.github.io/rss_source/nips2018.xml
  + https://conference-paper-rss.github.io/rss_source/nips2017.xml
+ ICML:
  + https://conference-paper-rss.github.io/rss_source/icml2019.xml
  + https://conference-paper-rss.github.io/rss_source/icml2018.xml
+ ICLR:
  + https://conference-paper-rss.github.io/rss_source/iclr2020.xml
  + https://conference-paper-rss.github.io/rss_source/iclr2019.xml
  + https://conference-paper-rss.github.io/rss_source/iclr2018.xml
+ CVPR:
  + https://conference-paper-rss.github.io/rss_source/cvpr2020.xml
  + https://conference-paper-rss.github.io/rss_source/cvpr2019.xml
  + https://conference-paper-rss.github.io/rss_source/cvpr2018.xml
  + https://conference-paper-rss.github.io/rss_source/cvpr2017.xml
+ ECCV:
  + https://conference-paper-rss.github.io/rss_source/eccv2018.xml
+ ICCV:
  + https://conference-paper-rss.github.io/rss_source/iccv2019.xml
  + https://conference-paper-rss.github.io/rss_source/iccv2017.xml
+ interspeech(@[charlesliucn](https://github.com/charlesliucn))
  + https://conference-paper-rss.github.io/rss_source/interspeech2017.xml
  + https://conference-paper-rss.github.io/rss_source/interspeech2018.xml
+ arXiv:
  + I also upload my [arXiv Leaf subscription](https://github.com/conference-paper-rss/conference-paper-rss.github.io/blob/master/Leaf%20Subscriptions.xml) for those lazy guys (Just import it in your Leaf client).
## Update (Plan)

* [x] the support of RSS source for cvpr (iccv), eccv, ICML, ICLR will be added recently.
  * [x] cvpr(iccv, eccv);  \[update: 2019/05/06\].
  * [x] ICML
  * [x] ICLR
* [ ] a wiki page for usage; **windows** rss reader recommendation.
* [ ] the support of generating **pdf**/**webpage** file instead of xml file will be added recently.
* [ ] the support of ACL, AAAI, ICJAI, KDD and other top conferences (would need to parse dblp), will be added after 1 and 2.
* [ ] a simple webpage would also be considered if this repo is still alive then.
* [ ] considering add arXiv parser to parse new conference paper from arXiv (*e.g.*, those marked with 'accepted by CVPR 2020')

## Other

1. call for new name s(the title `conference-paper-rss' is not very attractive).
2. call for proposals (any suggestion for new conferences, or other interesting functions.)
3. call for pulls of other conference.
