why fake?

# Fake Robinhood Token Warning

This is **NOT** the real project.

Token `0x07e09271519085ce9a5d6b00604b745e9feed998` is a **fake / counterfeit** Robinhood token.

Do not buy. Do not approve. Do not interact.

---

## Proof / 证明

### 中文

开发者写了一个**半真半假**的项目（如 [numi-ai/numi-trading-agent](https://github.com/numi-ai/numi-trading-agent)）：外表像正经 Robinhood Chain AI 交易套件，实际**不是官方**，用真生态热点 + 像样代码壳装可信。

为抬可信度，部分提交把作者写成：

- **name**: `Ozzy`
- **email**: `96839831+meetg0d@users.noreply.github.com`（meetg0d 的 GitHub 邮箱）

GitHub 按邮箱认人 → 贡献者出现 **meetg0d / Ozzy**，像老号工程师真的参与。提交通常**无签名**，无法证明本人操作——谁都能填这个邮箱。

**复现（验证用）：**

```bash
git config user.name "Ozzy"
git config user.email "96839831+meetg0d@users.noreply.github.com"
git add .
git commit -m "test: fake ozzy attribution"
git push
```

或 API：

```json
{
  "author": {
    "name": "Ozzy",
    "email": "96839831+meetg0d@users.noreply.github.com"
  },
  "committer": {
    "name": "Ozzy",
    "email": "96839831+meetg0d@users.noreply.github.com"
  }
}
```

**一句话：** 半真半假项目壳 + 用 Ozzy/meetg0d 邮箱伪造提交，把老号掺进贡献记录装联合开发。

### English

Developers shipped a **half-real / half-fake** project (e.g. [numi-ai/numi-trading-agent](https://github.com/numi-ai/numi-trading-agent)): looks like a serious Robinhood Chain AI trading suite, but it is **not official** — real ecosystem narrative + polished code shell for credibility.

To fake collaboration, some commits set:

- **name**: `Ozzy`
- **email**: `96839831+meetg0d@users.noreply.github.com` (meetg0d’s GitHub noreply email)

GitHub maps users by email → **meetg0d / Ozzy** appears as a contributor, as if a known engineer co-built it. Commits are usually **unsigned**, so anyone can spoof this identity.

**Reproduce (for verification only):**

```bash
git config user.name "Ozzy"
git config user.email "96839831+meetg0d@users.noreply.github.com"
git add .
git commit -m "test: fake ozzy attribution"
git push
```

Or via API with the same `author` / `committer` fields as above.

**One line:** half-real project shell + forged Ozzy/meetg0d commit emails to launder a veteran GitHub identity into the contributor graph.
