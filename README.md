# Our goals

The goal of the project is to create a **beautiful, easy-to-use, clean** cross-platform APP to record **great Chinese poems**. 

Since the APP is goal-oriented, our focous is the content and design. For content, we will only include these masterpiece. For design, we will emphasize the appearence and the degree of easy-to-use.





# What we'll include

First of all, to control the quality of our content, we will only review poems mannually, so the pross may be  slow and the judgment can be quite subjective. 

Chiness poem is a very unique concept --- it not only includes what westerns call "poems", but also includes **词** and **赋**. So in terms of format, we wil accept all of them(诗,词,赋 ). Note that we **dont accept** modern poems, other-language poems, 曲, 小说 or 古文. Appreciations of Poetry will be included too since we will carefully pick appreciation's versions.

# How we develop it

> **The app is cross-platform and we will develop Android and Web version. iOS version is not sheduled for now.**

LovePoem is a side project and we believe that the most important thing to develop a side project is to **focus on the problem itself**. So our prioritization is:

1. Only write frontend
2. if there must be a backend, try Serveless as much as possible
3. maintain a server



Here're the technical selection:

* Frontend( hybrid development ): React/ReactNative + Ts + Tailwind + Android
  * may be we can add Redux
* Backend: we try to avoid backend, but if we have to, we will use SpringBoot
* CICD: Jenkins. We're also considering [Vercel](https://vercel.com/) too.
* Database: Mysql or [Dynamodb](https://aws.amazon.com/cn/dynamodb)
* CloudNative: We hope we can use K8S.
* Test: Test is low priority. But the [SoloPi](https://github.com/alipay/SoloPi) for mobile testing is interesting, we will consider it if we have plenty time.





# Timeline

* 2022/8/15: Defining the vision.



## Get started

TODO

## Contribute

Well, altough we only take in ancient literature, any contributon is welcomed if you consider your work is good enough. Note that posted works must also be comliant with our limitations above.
