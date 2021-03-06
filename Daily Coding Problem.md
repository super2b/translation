#### 您好,请介绍一下你的背景，最近在忙什么
大家好，我叫Lawrence，我和我的合伙人Jae正在做 [Daily Coding Problemn](https://www.dailycodingproblem.com/)。我们是计算机科学专业，曾就读于多伦多大学。

我们提供的服务是每天给用户发送一道面试编码题。我们大学最后一年开始做Daily Coding Problem，但几个月前，才真正开放使用。从那以后，每月盈利已经增长到接近3000美元。


#### 开发Daily Coding Problem的动力是什么？
大学最后一年，我和我的朋友们都在准备面试。我每天都在聊天群里发送“今日面试题”，大家抢着去把它做完。当他们拿到offer的时候，归功于我的面试题，我不仅非常高兴，也很好奇地想这能否作为一个事业来做。我参加过很多面试，也面试过不少人，我确定在这个领域有丰富的经验。

我用邮件列表来尝试是受到以下几件事情启发：一件是你们的对Scott的Cheap Flights的采访，这让我受益匪浅。另一件是Ben Thompson的[Stratechery](https://stratechery.com/)。我对邮件列表订阅情况和盈利能力还是很乐观的。那时候我还在学校，我想可以用我的专业知识来赚点啤酒钱。现在我们赚的钱够付房租了，虽然不多，但至少在旧金山以外的地方租金是够了。

#### 怎么做第一版产品？
在做邮件列表之前，我是打算把在线评审代码、社交还有其他杂七杂八的功能做一个平台。相反，为了避免花几个星期做这个平台，我们只花了一个晚上的时间来做了一个登录页面来验证我们的产品，还把它发送到Hacker News上面。

一开始并没什么吸引力。之后我们开始写博客发送到Hacker News和Reddit。有几篇博客点击量很大，我们最早的一批用户基本上都是从这里来的。

我们的起步的开销很小，我们使用HeroKu(云服务器提供商),Sendgrid(电子邮件服务平台),Netlify(专注于提供静态网站托管服务)和Namecheap(域名)。第一个月总共花了不到50美元。我们手上有大量我们写的问题和解决方案，通过技术手段来发送邮件。以下是我们的费用分析:

* Stripe: 2.9% + 30美分/每笔交易
* Heroku：7美元/月
* SendGrid：10美元/月（我们现在换到了80美元/月的套餐）
* Netlify：免费
* Namecheap：10美元/年

这看起来利润很高，但是把编写新问题和答案，编辑旧内容和帮助读者的这些时间都算进来的话，其实并不是很多。

#### 你是怎么吸引用户的？
用邮件列表有一点好处就是，发送一些很难很有意思的问题，人们往往就会很自然地把邮件转发出去。所以我们必须仔细检查确保发送的问题清晰、简洁、有意思、有帮助。我认为已经取得成功了：现在很多用户发邮件跟我们讨论问题。

我们吸引用户的另一个方式是通过我们的[博客](https://www.dailycodingproblem.com/blog)。我们在博客上发布了面试策略，问题解决技巧和编程概念手册，也有我们问题和答案的真实例子，这也吸引了一些新用户来注册我们的邮件列表。

最后还有一个已经试验了的想法是为我们的订阅用户开发有用的工具。我们最近开发的是求职信生成工具。以前我在找工作的时候，给每个公司写求职信感到很厌烦。所以我觉得求职信生成工具对于求职者来说是很有用的。

我们的求职信生成工具从Reddit和Product Hunt带来了1万+人次的访问量。

#### 你的商业模式是什么？怎么增加盈利？
我们采用的是免费增值服务模式。你可以免费订阅获取所有的面试问题。但你需要支付9美元/月的订阅来获取答案详解（订阅全年，7.5美元/月）。

我们立刻收费是为了让这件事情作为商业来运作。我们最初的一篇博客终于上了Hacker News的头条，第一天就获得了150美元的订阅。这就是我们需要验证的，之后马上就开发我们的产品和基础架构了。

下面是我们过去5个月每月盈利图:

我们通过不断地市场推广和提升产品质量来增加盈利。比如说，我们注意到相当高比例的用户在第三个问题之后就有退订的倾向了。我们经过调查后意识到可能是问题太难了，所以用简单点的问题来替换，把这个复杂的问题往后移。我觉得这样一个微调可以减少整体用户流失，提高服务质量。

#### 未来的目标是什么？
我们的目标是持续给读者提供更好的问题和答案。但因为邮件列表扩散性，我想我们最需要做的是保证我们的产品足够好。为此，每封邮件都有一个CTA(???没Google到)用来用户回馈。用户需要做的就是回复邮件。这样，我们就知道哪些问题和解决方案还不够清晰。

我们也想开发一些有用的工具：有意思、可重用，并很有市场前景。我们的求职信生成工具每天还有几百人次的访问，有部分用户最后也会付费订阅我们的邮件列表。

我们也考虑跟一些公司合作出售广告位，像Software Engineering Daily 和 Scott的Cheap Flights那样做，甚至也可以把潜在的候选人推荐给公司（to even to refer potential candidates to）。如果你作为公司对此有兴趣的话，随时联系我们。

#### 有没有什么东西对你特别有帮助？我觉得做过最有帮助的事情是专注在快速响应上。这就意味我们清楚知道什么促使我们前进以及正在做的事情。当我们积压了大量的需求，我们倾向于先做最简单的，这让我们快速看到成果，产生动力。

还有一点就是快速把价值传递给客户。这听起来很简单但很容易忘记。对于我们黑客来说，尝试自动化工具，减少损耗，体验新技术，或者早期就做一个长期可用的架构方案(make long-term moves too early)是非常诱人的。比如，一开始我们没有自动发邮件的工具，就手动通过Gmail发送，用户不关心邮件是不是自动发送的。这也正好给我们时间来交流，帮助用户确信我们正在做一些他们想要的东西。

最后一点就是砍功能。这样不仅能让我们更快发布有价值的东西，这也恰恰能让用户牢牢记住你的产品(but somewhat paradoxically helps to anchor your product in customer's minds)。一天一个问题和一个技术面试社交平台哪个更容易被理解？就像Unix格言：做一件事而且把它做得很好。

#### 对刚开始的人有什么建议？
其中一条建议就是做比想象中更多的试验，即使是不一定要解决的事情也一样。你通过尝试和失败每天不断进步，而你发现的事实可能与期望的并不一样。

另一件事情就是马上启动。刚起步的时候，我们只有一个登录页面，但这比其他任何一个项目都走的更远。

写下来之后我才意识到这些理论听起来很老套，但这是对的。所以，只要尝试一下，然后启动。

#### 哪里能了解更多？
我希望这对你是有帮助的。你可以关注我们的[官网](https://www.dailycodingproblem.com)和[博客](https://www.dailycodingproblem.com/blog)，也可以在评论区里面问任何问题。

英文原文：[Indiehackers.com](https://www.indiehackers.com/interview/a2b57cca87)
翻译：[wblei](https://github.com/super2b?utm_source=sideidea.com)
校对：
