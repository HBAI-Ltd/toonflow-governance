# RFC: Toonflow 开源协议变更 | License Change Proposal

> **RFC 发布日期 | Published:** 2026-03-24
> **RFC 反馈截止 | Feedback Deadline:** v1.0.8 发布当日 / On v1.0.8 release date
> **发起方 | Proposer:** HBAI-Ltd

---

## 一、提议摘要 | Proposal Summary

Toonflow 拟将开源协议从 **AGPL-3.0** 变更为 **Apache 2.0 + 补充协议**。

Toonflow proposes to change its open-source license from **AGPL-3.0** to **Apache 2.0 + Supplementary Agreement**.

变更将在 RFC 反馈期结束后正式生效，旧协议期间的使用行为不受影响。

The change will take effect after the RFC feedback period. Usage under the previous AGPL-3.0 license will not be affected.

---

## 二、为什么要改 | Why We Are Proposing This Change

### 2.1 当前协议的问题 | Problems with Current License

AGPL-3.0 对"网络使用也必须开源"的要求，导致：

The AGPL-3.0 requirement that network use also triggers source code sharing has caused:

- 大量潜在商业合作方因法律不确定性而回避 Toonflow
- Many potential commercial partners have avoided Toonflow due to legal uncertainty.
- 开发者在集成和二次开发时对合规边界存在疑虑
- Developers have had concerns about compliance boundaries when integrating or forking.
- Skills 生态扩展受到协议模糊性的制约
- The Skills ecosystem expansion has been constrained by the ambiguity of the license.

### 2.2 新协议的优势 | Benefits of the New License

**Apache 2.0 + 补充协议**提供以下改善：

**Apache 2.0 + Supplementary Agreement** provides the following improvements:

| 对比维度 | AGPL-3.0 | Apache 2.0 + 补充协议 |
|---------|-----------|---------------------|
| 商业使用规则 | 模糊，网络使用也需开源 | 明确，仅 SaaS 产品分销需授权 |
| Commercial use rules | Ambiguous — network use triggers share-alike | Clear — only SaaS distribution requires authorization |
| 开发者集成 | 合规边界不清晰 | 规则透明，内部使用无需担忧 |
| Developer integration | Unclear compliance boundaries | Clear rules — internal use is safe |
| 社区回馈机制 | 无直接机制 | 授权收入 50% 回归社区基金 |
| Community benefit mechanism | No direct mechanism | 50% of licensing revenue goes to community fund |
| 企业采纳阻力 | 高 | 低 |
| Enterprise adoption barrier | High | Low |

---

## 三、新协议全文 | Full Text of the New License

### Apache License 2.0

请参阅 Apache Software Foundation 官方版本：
See the official Apache Software Foundation version:
https://www.apache.org/licenses/LICENSE-2.0

### 补充协议 | Supplementary Agreement

> **补充协议 | Supplementary Agreement**
>
> 若您将本软件或其衍生版本以产品形式分发、销售或提供给**两个及以上独立的第三方主体**使用（无论采用买断、订阅、授权或任何其他商业模式），均须事先取得 HBAI-Ltd 的**书面商业授权**。
>
> If you distribute, sell, or provide this software (or any derivative) as a product to **two or more independent third parties** (regardless of business model: one-time purchase, subscription, licensing, etc.), you must obtain **written commercial authorization** from HBAI-Ltd prior to such use.
>
> **五个以内（含五个）**的法人主体作为联合运营方共同使用本软件，且不向联合体以外的第三方分发或提供服务的，视为**内部使用，无需商业授权**。
>
> **Five (5) or fewer** legal entities jointly operating and using this software internally, without distributing or providing services to parties outside the joint operation, are considered **internal use** and do not require commercial authorization.
>
> 在使用 Toonflow 的过程中，您不得删除或修改 Toonflow 控制台或应用程序中的标识或版权信息。
>
> You may not remove or modify any trademarks, logos, or copyright notices in the Toonflow console or application.

---

## 四、永久免费场景 | Always Free — No Authorization Required

以下使用场景**永久免费**，无需任何授权：

The following uses are **always free** and require no authorization:

- ✅ 用 Toonflow 制作内容，在平台发布并获得分账 / Using Toonflow to produce content and earn platform revenue shares
- ✅ 二次开发，供自己团队内部使用 / Secondary development and modification for internal team use
- ✅ ≤ 5 个法人联合运营内部使用，不对外提供服务 / ≤5 legal entities operating jointly, internally only
- ✅ 个人学习、研究、非商业用途 / Personal learning, research, and non-commercial purposes

---

## 五、授权定价 | Licensing Pricing

商业授权费用与被授权方业务规模挂钩：

Commercial licensing fees scale with the licensee's business scale:

| 阶段 | 年销售额 | 年费 |
|------|---------|------|
| 🌱 扶持期 / Nurture | < ¥10 万 / $10k | **免费 / Free** |
| 🚀 初创期 / Startup | ¥10–50 万 / $10k–$50k | ¥5,000 / 年 / year |
| 📈 成长期 / Growth | ¥50–150 万 / $50k–$150k | ¥20,000 / 年 / year |
| 🏢 规模期 / Scale | ¥150–500 万 / $150k–$500k | ¥80,000 / 年 / year |
| 🌐 企业级 / Enterprise | > ¥500 万 / $500k | 面议 / Negotiable |

---

## 六、AGPL 用户保护条款 | AGPL User Protection

> **不追溯条款 | Non-Retroactivity Clause**
>
> 本协议变更生效日期（v1.0.8 正式发布日）前，基于 AGPL-3.0 条款使用 Toonflow 的用户，其现有使用行为不受本协议变更的约束，继续按 AGPL-3.0 条款执行。
>
> Users who used Toonflow under AGPL-3.0 prior to the effective date of this change (v1.0.8 official release date) are not affected by this license change. Their existing usage continues under AGPL-3.0.

---

## 七、收入分配承诺 | Revenue Distribution Commitment

HBAI-Ltd 郑重承诺：全部商业授权收入的 **50%** 将直接用于 Toonflow 社区建设与社区基金。

HBAI-Ltd commits that **50% of all commercial licensing revenue** will go directly to Toonflow community development and the community fund.

- 每季度公布授权收入总额与社区基金划拨金额 / Quarterly publication of total licensing revenue and community fund allocations
- 每半年公示基金使用明细 / Semi-annual publication of fund usage details
- 社区理事会对基金用途优先级具有投票权 / The Community Council votes on community fund priorities

---

## 八、我们想听到你的声音 | We Want to Hear From You

此次变更对社区至关重要。我们真诚希望听到你的意见，尤其是：

This change is significant for the community. We genuinely want to hear from you, especially:

- 你认为补充协议的授权触发条件是否合理？/ Do you think the authorization trigger conditions in the supplementary agreement are reasonable?
- 你是否遇到过 AGPL-3.0 带来的实际合规困扰？/ Have you encountered actual compliance difficulties with AGPL-3.0?
- 授权定价是否与你的业务规模匹配？/ Does the licensing pricing match your business scale?
- 你是否有其他我们未考虑到的场景或风险？/ Are there other scenarios or risks we haven't considered?

**请在 GitHub Issue 中留言，或私信 HBAI 团队。**
**Please leave a comment in this GitHub Issue, or DM the HBAI team.**

---

## 九、后续时间线 | Timeline

| 阶段 | 时间 |
|------|------|
| RFC 发布 / RFC Published | 2026-03-24（今天） |
| 社区反馈期 / Community Feedback | 即日起至 v1.0.8 发布当日 |
| 协议正式变更生效 / License Change Effective | v1.0.8 发布当日 |

---

## 十、附件 | Attachments

- [ ] 《Toonflow 社区宣言 / Toonflow Community Manifesto》
- [ ] 《Toonflow 社区治理章程 / Toonflow Community Governance Charter》

---

*本 RFC 由 HBAI-Ltd 发起，基于 2026-03-24 社区理事会第一次会议决议。反馈截止时间为 v1.0.8 发布当日，协议变更同步生效。*
*This RFC is initiated by HBAI-Ltd, based on the resolution of the first Toonflow Community Council meeting on 2026-03-24. Feedback deadline: on the v1.0.8 release date, at which time the license change will take effect.*
