# 去中心化的迷思

## 去中心化的意义
很多人不明白去中心化其实是分两个步骤的：去中心，然后再统一形成共识。也就说要先去中心，然后再中心化。

一、先去中心化
BTC 软件的设计，就是将区块链完整地备份到每个节点的电脑上，这个软件或者说这个链或者说这个公开数据库一开始就是去中心的，这就完成了第一步 “去中心”。

二、再中心化
问题是去中心之后如何再把记账权统一起来，否则就是各记各的帐，乱成了一团。中本聪最终选择了 PoW 机制来实现记账权的统一，也就是说每 10 分钟，这个记账权就中心化到某个矿工身上，不集中没法记账，但是因为 PoW 是竞争性的，所以下一个 10 分钟，记账权就未必还在这同一个矿工身上了。

很多人就在这个地方产生了误解，认为权力都集中于矿工是巨大隐患。错，PoW 的设计就是要把权力在某一个时刻（出块的瞬间）集中在某个矿工身上，只不过每次集中到的未必是同一个人而已。换句话说， PoW 根本就不保障什么去中心化， PoW 保障的是 2 点：

从短期看，具体在某一个块上，权力必须集中在某个矿工身上以保证数据库写权力的唯一，重点是 “集中” 也就是 “中心化”；
从长期看，权力总是集中在对挖矿投资最大（同时也是效率最高）的人身上，因为他们算力比例必然最大。
如果你承认上面的分析，那你就可以很容易得出一个结论：

PoW 机制从来不是为了什么去中心化，恰恰相反， PoW 的目的在于 “把写区块链的权力，归于对 BTC 系统投入最大的人，即最大的矿工获得最大的权力”，也就是说， PoW 就是为了中心化而生的，从来都不是为了什么去中心化。

政府无力去考虑大范围的影响。你可能会问，为什么中央计划总是失败。 任何个人、部门或其他机构都无法预测社会的走向，即使施行了军事管制，结果仍然是不可预测的。




以下讨论仅针对工作量证明（Proof-of-Work）的共识体系：



1）挖矿节点因为有算力，他们能够选择在哪个区块上搭建新区块，也可以选择作废哪个区块，他们用算力来维护共识，这就是在原共识框架内行使“修复权”。需要注意的是比特币在2009年诞生时并没有什么共识，只是中本聪一人之识，随后越来越多的人加入，认可中本聪的愿景，于是才有了“共识”。也就是说，比特币的“共识”是后来者主动认可的，而不是预先敲定的。具体请看以前写的一篇小文章。



2）开发者能够写代码，可以将自己的想法注入整个体系，他们维护整个体系的正常运转，出bug时需要他们来解决。从这个层面上来说，开发者拥有的是新建共识（中本聪、Core）或修复共识（比特币后续各维护开发团队）的权力。举个例子，ETH的硬分叉就相当于是小神童（本身他就是开发者）强行新建并修复共识的行为。



3）非挖矿节点由于是跟随节点，他们本身本不能对网络产生任何影响，甚至还有可能因为硬件配置低而拖慢交易的广播，造成负面影响。由于非挖矿节点既无算力，也无写代码的能力，所以他们无法行使所谓的修复权。他们在既有共识体系内行使“修复权”的方式就是与开发者合谋，新建另一套共识体系，比如将工作量证明（Proof-of-Work）体系变更为权益证明体系（Proof-of-Stake），这可能是未来ETH会做的事；或者更改工作量证明本身的算法，比如现在的门罗币分叉。而这又和修复原共识体系根本不沾边了。



通过以上分析我们可以看出，在比特币这套共识体系下，获得话语权的唯一方式就是当矿工，你的话语权和你投入的资金规模成正比，这样普通用户才能相信你会为了长期的利益不作恶。否则用户可以随时用脚投票，让你的巨额投入血本无归。你不可能单单通过运行一个廉价的非挖矿节点就想拥有巨大的权力，这从来就不是一个可以自洽的逻辑。我并不反对个人依照自己的喜好去运行全节点，但是妄想能够依靠它就能保护网络就完全是个谎言了，希望大家都能想明白这个道理。

​




![](https://r.sinaimg.cn/large/article/2d0ed217d767137ad7c26e806bd3b0cb)

市场结果即是社会的观点。




市场就是社会。 少数公务员并不是社会，而且他们对社会一无所知。





中央计划是无效的，是一个会时不时还魂的失败实验。 再而言之，身居高位者难以自弃，因此，只要依然存在激励，政府人员便有强烈的动机以确保政府及其一切错误行为不受影响。





这个问题也是比特币的一部分意义所在。比特币占据着主要的底层系统，并将控制权从个人或团体的手中剥离出去。它的意义不在于矿工、开发者或交易所; 比特币是一个剥离权力的系统。这十分重要，货币的基础不应该是控制。你可以在与黄金类似的物质的基础上进行构建，同时保持黄金是一个稳定的系统，一种衡量和传输价值的手段。





最近，我们又看到了另一个缓慢且阴险的企图，有人试图改变比特币的本质。在 Peter Todd [提议提高2100万比特币上限](https://www.trustnodes.com/2019/03/26/peter-todd-advocates-raising-the-21-million-bitcoin-limit-hence-the-blocksize-constrain)的文章中，解释了 Core 的开发者再次寻求改变比特币的主要目标并寻求获取权力。




与文章中的说法相反的是，比特币不会消亡。原因很简单: BTC 不是比特币。 是的，这种阴险的攻击使用了比特币这个名字，这种使用名称的方式直接来源于奥威尔的《1984》。BTC这种改变并不意味着新的规则，只意味着BTC是一个修改过的协议，而比特币的协议是固定且一成不变的。

对于比特币来说，由于协议是固定的，因此不存在因分叉而衍生出来的混乱。




比特币不是通货，而是一种现金和商品。通货是由政府发行和控制的东西。比特币永远不可能以这种方式成为通货，但是比特币之上可以用代币的方式发行一种通货。




世间并没有两个比特币，而是只有一个。而且只能有一个。事情的真相是，有的人在寻求权力，而开发人员能做到这一点的唯一方式就是控制和改变协议。 因此，他们可以这样做的事实意味着他们对系统拥有控制权。 这意味着他们对法律范围内的后果负有责任。 他们越是一边反驳这种说法，一边改变着与他们的比特币副本相关的协议，他们就越是展示出他们试图攫取权力和控制的双手。






那些一直在攻击比特币的人瞄准了矿工和矿池的中心化。这就是非黑即白的思维谬论。这是一种错误的选择或者说是错误的二分法。人们在此错误地认为只有非此即彼。

拿比特币来说，中心化被认为是全有或全无的情况。但是事实却更为微妙。

错误的二分法是这样的，它们不是互补的（还有其他选择），或者不是互斥的（备选方案有重叠），也有可能二者都不是。请注意，上面给出的示例并不互斥，因为测试和程序可能都是错的。

中心化。

去中心化。

其实还有其他选项。

这个争论引出了比特币为何存在的问题。比特币是一种电子货币系统，它旨在使微交易成为可能的同时使交易费用变得非常低甚至可以忽略不计，即使对于大额交易和国际交易也是如此。它不是数字黄金，而且数字黄金这种系统也不可能成功。许多人误解了法定货币即使如此贬值也会被广泛使用的根本原因。

在极端情况下，分布式系统是割裂的。他们并不强健，很容易被颠覆。和大多数事情一样，解决之道是平衡。比特币不是一个旨在实现平等的系统，因为实现真正平等的唯一途径是让所有人同样赤贫。

Kyotaki和Wright（1989）型构了一个货币模型。在该模型中，货币是作为一个“搜寻问题”的解决方案而出现的。参与交换的各方以科斯的方式降低了交易摩擦。首先，他们解释了法定货币的优势。有两个特性使得法币系统被广泛使用，这两个特性直接来自以下两个属性：

1.比所有其他物品和商品更低的存储成本，以及

2.不可消费性

这两个属性共同构成了较低的交易成本和较大的贸易机会。扩容之后，并且只有在扩容之后，比特币才能为微交易和银行结算提供较低的交易成本和较高的可靠性。重要的是，它没有提供任何额外的消费者功能的情况下就能做到这一点，这些都与系统本身的功能别无二致。在比特币中，系统的价值来自于该系统本身没有其他基于商品的输入。这是法币系统的真实写照，但是比特币与此同时开创了稳定性并限制了各方贬值货币的能力。

比特币通过竞争解决了这个问题。作为商业验证者或矿工的实体通过竞争创建区块来证明交易的完整性。只要没有一个人控制超过50％的网络算力，系统就可以保持稳定而不会被任意篡改。其要求是三方或更多方参与竞争。在任何具有三个竞争性矿工的实现中，只要任意矿工在任意时间持有不超过50%的网络算力，系统就是去中心化的。

现实是更多实体会更好。鉴于至少需要有三个竞争主体以及资本主义体系的性质，利润可能导致某些组织失败并破产，建议在任何时候都有三个或四个以上的组织在竞争，以确保不会出现某个个体的失败导致网络不稳定这种一损俱损的局面。

任意系统中只要拥有五个或以上挖矿实体，且没有任何一方控制超过50％的网络算力，比特币就是去中心化的。随着系统的扩容，运营和攻击这些商业实体的成本显着增加。即使只有少数矿工，比特币作为一个分布式的货币系统仍然是去中心化的，它仍然能够提供其最主要的成果，即货币的稳定性。更重要的是，随着比特币的扩容，攻击网络的成本会显着增加。作为一个全球性的体系，任何政府都无法攻击比特币。

还有一点也要着重强调，如果某个别矿工破产，所有其他矿工的利润都会增加。这会导致使得竞争和利润动态地维持着系统的平衡。当一个矿工失去竞争优势时，另一个矿工就会取代他。这种均衡的结构允许足够的去中心化以保持稳定性，同时提供低成本的且几乎是瞬时的交易。

许多开发人员和专家无法理解的是，货币系统作为交换媒介的唯一方式是没有其他价值或其使用价值是远低于任何其他交换商品的。关于黄金你要考虑到的不仅仅是它的稀缺和稳定性，还要考虑它在历史上几乎没有其他用途。将黄金作为结算系统的早期原因之一是它缺乏耐用性以及不能用于制造商品。使用黄金作为珠宝是晚于其拥有货币价值的。我们在许多文化中都能看到这种情况，而在没有广泛的货币基础的地方（例如印度），以黄金为基底的珠宝是个人携带其财富的手段，同时也是作为一种凡勃伦商品来表示其所处的阶级。

有种错误的想法认为加密货币必须具有替代价值，这个问题通过“货币单位的搜寻效率”已经被解决了（Arrow-Hahn，1971）。在这个模型和KW模型中，证明了法定货币并没有明确地带来福利的提高。生产额外的法定货币被证明是降低消费的。其结果是证明了流通中最佳的法定货币数量。

这就像一个囚徒困境模型。由于不可消费性和有利的存储成本，法定货币有能力挤出传统意义上的商品货币。任何无法维持稳定的有效货币，无论是法定货币还是加密货币，都会不可避免地达致一个纳什均衡，即驱使大家使用效率较低的货币，同时降低整体福利。正是出于这个原因，比特币被设定为稳定的货币体系。它在提供一个非消费性系统的同时，其扩容后产生的交易摩擦低于任何法定货币之间的交易摩擦。

比特币的目的不是提供一个分布式的系统。分布式系统是为了确保实现比特币的主要目标，即稳定的货币单位。


这是比特币最大的迷思。扩容的唯一问题在于对家庭用户节点的补贴。比特币现在就可以扩展到TB级的区块。唯一阻碍的是一种错误的想法，即网络中是需要非挖矿节点的。矿工们是相互竞争的组织。



有一个简单的原因来说明人们对区块链扩容所生产的疑问。它们（区块链们）总是被设计成商业性的。它们被设计为竞争性的。它们被设计为货币交换的单位。对于比特币，实际上是对于任何区块链来说，成功的路径有且只有一条，即其必须聚焦于成为单一的现金单位。

一旦这个观点被接受之后，无数其他用途都将各归其位。正如用户不运行他们自己的电子邮件服务器，他们自己的Web服务器或任何其他服务器集群一样，比特币使用公司数据验证而不是受信任的第三方，但它是一个特定的协议系统。这个系统之所以有效是因为资本主义是一种竞争的体系。比特币纯粹是竞争驱动的。你是否喜欢这个设定并不重要，因为比特币是非政治性的，它是纯粹的资本主义。

我们可以信任比特币以及矿工的原因是协议治理机制。这之所以能成为一个货币单位的原因只是因为一个简单的事实，矿工并不是一个统一行动的整体。

这与对企业高管的典型评论是一样的。企业高管并没有统一的形式。我们如何信任这些企业实体。很简单，我们相信他们的贪婪。道德情感是企业文化之上的一层，而这与比特币的治理无关。它（比特币）依赖于寻求利润。我们知道这（寻求利润）是有效的，因为我们知道公司将寻求利润最大化，他们将尽一切努力来实现这一目标。这就是比特币能成功运作的原因。最有效率的组织将寻求其对于竞争对手的优势，并且这样做将推动矿业的盈利能力达致极端。在这一点上，任何公司实体都无法获得任何改变比特币内在的方法。为了达到这一目标，我们需要扩容。

比特币扩容的成本超过了网络和系统架构的成本。扩容无极限。比特币中没有垃圾交易这样的东西。任何愿意为交易付款的人都可以让该笔交易被存储下来。矿工尽全力竞争以尽可能多地包含交易，因为这是他们获取相较于其他矿工的盈利优势的方式，这是让他们保持竞争力的方法。随着时间的推移，矿工们所有的利润都将几近来自于交易费用。

无上限的区块才是区块链正确地打开方式。使用越多，利润越多，规模越大，交易成本越低。比特币的激励在于它要成为全球互联网的主心骨。

达成此目的的唯一方式就是成为现金。
