# ChatGPT Pro升级全攻略：Pro 200额度腰斩后还值不值？Pro 500的Ultrafast划不划算？老用户怎么保住原有用量？（附立减1美元开通方式）

9 月 29 日 DevDay 之后，“升级 ChatGPT Pro”从一道单选题变成了三道：$100 的 Pro 100、$200 的 Pro 200 和 $500 的 Pro 500 同时在售，而原来 $200 档的用量直接砍了一半。还挂着一个硬期限——10 月 30 日，老 Pro 200 的 20x 额度正式降到 10x，月费不变。

到今天为止，留给老用户做决定的时间只剩两周多。这篇文章把三档 Pro 的实际差异、Ultrafast 到底值不值、老订阅者该怎么应对、去哪开通这些问题一次讲清。

## 先把这次改动捋清楚

三个变化，都挤在 9 月底到 10 月底之间：

- **Pro 500 上线**：$500/月，25 倍 Plus 用量，是个人套餐里唯一带 Ultrafast（GPT-6 Astra 高速模式）的档位，也是唯一能在 Codex 和 ChatGPT Work 里通过 Agents API 使用 computer use 的个人套餐。
- **Pro 200 重新开放**：$200 档从 9 月 10 日起停止新订阅，9 月 30 日重新开售——但新订阅的用量从约 20x Plus 降到 10x，聊天里 GPT-6 Pro 模型的上限从每周 200 条降到 100 条。官方给的理由是“模型效率提高了”。
- **老用户有过渡期**：在资格截止点之前（或截止点前 7 天内）订阅处于有效状态的 Pro 200 用户，可以保留原额度到 2026 年 10 月 29 日；之后同样降到 10x，月费维持 $200。截至点前 7 天内断订的人，重新订阅还能恢复旧额度到同一天。

OpenAI Codex 负责人 Thibault Sottiaux 对这次调整的说法是：按 API 等价花销算，新方案大约相当于原来的一半。这句话听着像解释，其实取决于你是受益方还是买单方。

补偿方面，据多方报道，存量 Pro 200 订阅者会收到一次性 62,500 credits（价值约 $2,500），2026 年 12 月 31 日过期。注意这是 ChatGPT/Codex 的用量积分，不是 API 平台余额。

顺带一提，也有报道指出同期 GPT-6 Sol 和 Luna 的 API 价格减半，所以实际体验的落差可能比数字上看的稍小一点——但套餐内额度减半是实打实的。

## 三档 Pro 差在哪

先说定价逻辑，这个结论有点扎心：Plus、Pro 100、新 Pro 200、Pro 500 现在全部是每 1 倍 Plus 用量收 $20——$100 买 5x，$200 买 10x，$500 买 25x，没有任何量大优惠。唯一打破这条线的是老版 20x 的 Pro 200（相当于每单位 $10），而它正好是要退场的那个。

官方帮助文档目前只说“Pro 200 用量多于 Pro 100，Pro 500 最多”，具体倍数来自媒体和用户侧口径，但多方数字是一致的：

| 档位 | 月费 | Work/Codex 用量 | GPT-6 Pro 聊天上限 | Ultrafast | Dot 常驻 agent |
| --- | --- | --- | --- | --- | --- |
| Pro 100 | $100 | 5x Plus | 未公布 | 不含 | 含 |
| Pro 200（新订阅，及 10 月 30 日起全员） | $200 | 10x Plus | 每周 100 条 | 不含 | 含 |
| Pro 200（老额度，保留至 10 月 29 日） | $200 | 20x Plus | 每周 200 条 | 不含 | 含 |
| Pro 500 | $500 | 25x Plus | 未公布 | 含 | 含 |

所以 Pro 500 多出来的 $300，买的就两样东西：多 15 倍的用量上限，和 Ultrafast 的入场券。

### Pro 100：功能基本齐了，只是量少

Pro 模型、Codex、深度研究、图像生成、记忆和文件上传，这些 Pro 该有的它都有，还带一个 Dot（常驻 agent，和它的对话不计入用量）。如果你的 Codex 用量不算凶，$100 就能拿到 Pro 的全部体验，只是 5x 的池子小一些。

### Pro 200：给每周都泡在 Codex 里的人

新订阅 10x 的用量对重度开发者来说依然够用，前提是你不是每天把额度打穿的那种人。已经有老订阅的，10 月 30 日之前请看后面专门那节。

### Pro 500：上限最高，外加速度

25x 是三档最高，Ultrafast 和 computer use 是它独有的两张牌。但这两张牌怎么用，直接决定这 $500 花得值不值，下一节算这笔账。

## Ultrafast：快是真的快，烧也是真的烧

先给数据。Ultrafast 在 Codex 里生成速度最高 8 倍，官方口径最高约 300 tokens/秒；API 里最高 6 倍。Sam Altman 在发布当天发文说 "Ultrafast is so fast I do not ever want to go back"——信不信由你。

但代价写在同一段文档里：Ultrafast 按 8 倍标准速率消耗套餐内额度，Fast 模式是 2.5 倍，购买 credits 后按 6 倍计。

算一下就知道问题在哪：25x 除以 8 倍消耗，大约等于 3.1 倍 Plus 的实际工作量。也就是说，如果你整周都挂着 Ultrafast 跑，Pro 500 的额度折算下来还不到 Pro 100（5x）标准速度的用量。花 $500 得到比 $100 更少的总产出，只是快了很多。

还有一个门槛要说清：在 Pro 100 或 Pro 200 上买 credits 并不能解锁 Ultrafast，它是 Pro 500（个人套餐内）和 Enterprise 的专属。额度用完后 Ultrafast 会继续从你的 credits 余额里按 6 倍扣，速度照样快，账单也照样快。

实际建议很简单：默认用 Standard，只有在坐在屏幕前等输出的场景——长代码生成、大型重构、并行跑多个 Codex 任务——才切 Ultrafast。排队过夜跑的活儿，开它纯属烧钱。

## 全套餐一览：从 Free 到 Enterprise

| 套餐 | 价格（美元） | 核心配置 | 适合谁 | 开通入口 |
| --- | --- | --- | --- | --- |
| Free | $0 | 基础对话，用量低于 Plus | 轻度尝鲜 | [查看 Free 方案](https://bewild.ai/?code=ACCPAY) |
| Go | $8/月（美国区） | 官方未公布用量倍数 | 预算敏感的轻度用户 | [查看 Go 方案](https://bewild.ai/?code=ACCPAY) |
| Plus | $20/月 | 1x Plus 基准用量；5 小时窗口 + 周上限 | 日常聊天、写作、偶尔写码 | [开通 Plus](https://bewild.ai/?code=ACCPAY) |
| Pro 100 | $100/月 | 5x Plus；含 Dot；无 Ultrafast | 想用 Pro 模型和 Dot 的中度用户 | [开通 Pro 100](https://bewild.ai/?code=ACCPAY) |
| Pro 200 | $200/月 | 新订阅 10x Plus，GPT-6 Pro 每周 100 条；含 Dot | 重度 Codex / ChatGPT Work 用户 | [开通 Pro 200](https://bewild.ai/?code=ACCPAY) |
| Pro 500 | $500/月 | 25x Plus；Ultrafast；Agents API computer use；含 Dot | 需要最高上限和速度的用户 | [开通 Pro 500](https://bewild.ai/?code=ACCPAY) |
| Business Standard | $25/人/月（年付 $20） | 官方未公布倍数；5 小时窗口 + 周上限 | 小团队 | [咨询 Business 方案](https://bewild.ai/?code=ACCPAY) |
| Business Premium | $125/人/月（年付 $100） | 5x Business Standard；含 Dot | 需要 Dot 和更高用量的团队 | [咨询 Business Premium](https://bewild.ai/?code=ACCPAY) |
| Enterprise | 定制 | 定制用量；含 Ultrafast；Dot 为 Beta（管理员开启） | 大型组织 | [了解 Enterprise](https://bewild.ai/?code=ACCPAY) |

几个影响选择的细节：

- Pro 全系只按月计费，没有年付，也不能一次预付多月。一年 Pro 500 就是平铺的 $6,000。
- Pro 各档目前没有 5 小时窗口限制，用量按周预算走——可以一口气在周六用完一整周。Plus 和 Business Standard 仍是 5 小时窗口加周上限，爆发式工作会难受一些。
- 用量池在 Codex、ChatGPT Work 和通过 Sign in with ChatGPT 接入的第三方工具（如 Devin、Notion、Vercel）之间共享，一个池子到处扣。
- 这次 DevDay 顺带发布的新模型 GPT-6.1 Sol（API 定价每百万 token 输入 $2 / 输出 $10）Plus 及以上可用，先在 ChatGPT Work 和 Codex 上线；ChatGPT Space 共享空间和 Pages 文档则是 Pro / Business / Enterprise 的功能。
- Dot 每档 Pro 都含一个，但 EEA、瑞士和英国的 Pro 用户在发布时暂不包含。

## 老 Pro 200 用户，10 月 30 日前做这三件事

1. **别让订阅断掉。** 计划取消不会立刻生效，会用到本期结束，期内可以撤销；但如果真断了又超过 7 天宽限期，旧额度就回不来了。这个月宁可别动它。
2. **趁还有 20x，测出真实用量。** 打开 Settings → Usage 看看每周实际消耗多少。如果连 10x 都用不满，这次“砍半”对你其实没影响；如果经常顶到 20x，就得认真考虑换档了。
3. **把补偿 credits 在 12 月 31 日前用掉。** 它是一次性的，过期清零。额度被腰斩后的头两个月，这笔约 $2,500 的积分能帮你平滑过渡，也顺便让你用真实数据判断要不要升 Pro 500。

另外提醒一句：保留旧额度不等于升级。你的订阅仍然是 Pro 200，Ultrafast 和 Pro 500 的功能一样都不会多。

## 在哪开通：官方路径和第三方渠道

官方路径本身不难：新用户登录 chatgpt.com，打开定价页选档；已经在用的老用户在 Settings → My Plan 里换档。取消要在原购买平台操作（网页端、App Store 或 Google Play），卸载 App 不等于取消订阅。

现实问题在支付：三档都是美元月付，需要能正常扣美元的支付方式。如果你自己绑卡折腾不动，可以走第三方开通渠道，比如 Bewild。通过其入口下单时用优惠码 **ACCPAY**，能立减 1 美元，各档位的库存和到手价以下单页为准。

👉 [前往 Bewild 开通 ChatGPT Pro，优惠码 ACCPAY 立减 1 美元](https://bewild.ai/?code=ACCPAY)

顺带一句实话：OpenAI 的使用条款明确禁止共享账号凭据和转售访问，被限制访问的往往就是合租账号。不管从哪个渠道开，账号都建议自己一人用。

## 常见问题

### 用量到顶了怎么办？

等重置。到顶时该模型会暂时不可用，界面会显示重置时间，期间可以切其他可用模型。客服无法手动重置额度。对支持的功能，可以在 Settings → Usage（Codex 端是 Usage & Billing）购买 credits 续用。

### credits 能用在哪些地方？

Codex、ChatGPT Work、ChatGPT for Word / Excel / PowerPoint 等支持的功能。不是所有模型和功能都收 credits，规则是先扣套餐内额度，用完再扣 credits。

### Pro 能年付吗？

不能。Pro 全系按月计费，官方明确不支持年付或提前付多月。

### 取消订阅会立刻失效吗？

不会。取消只是停止续费，本期结束前都能继续用，期内还可以撤销取消。退款要看具体购买渠道和当地法规，网页端和 Google Play 找 OpenAI 支持，App Store 直接找苹果。

### 和 Claude Max、SuperGrok Heavy 比呢？

现价：Claude Max 5x 是 $100/月，20x 是 $200/月；SuperGrok Heavy $300/月；ChatGPT Pro 500 是 $500/月。但“20x Claude Pro”和“10x ChatGPT Plus”的基准完全不同，倍数不能跨家直接比。能比的是行为模式：Claude 按 5 小时会话滚动重置，外加周上限；ChatGPT Pro 是纯周预算，可以一口气花完。重度终端 agent 用户，模型本身往往比倍数更重要。

## 最后一点判断

10 月 30 日前后的 ChatGPT Pro 是两个东西：之前 20x，之后 10x。用得狠的人，要么接受减半，要么上 Pro 500 补回那 15 倍的量；用不满的人，这波调整反而帮你确认了 Pro 100 甚至 Plus 就够用，省下的 $300 到 $400 一个月不是小数。

先用一两周测出自己的真实用量再做决定，比看任何测评都准。如果已经想清楚了要锁哪个档位：

👉 [用优惠码 ACCPAY 在 Bewild 立减 1 美元开通](https://bewild.ai/?code=ACCPAY)
