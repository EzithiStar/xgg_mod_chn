# xgg_mod_chn
# Pathfinder 1e (PF1) 核心系统及模组中文汉化包

![Foundry Core Compatible Version](https://img.shields.io/badge/Foundry%20VTT-v13-orange) ![System](https://img.shields.io/badge/System-PF1e-blue) ![Language](https://img.shields.io/badge/Language-zh--cn-red)

本项目致力于为 Foundry VTT 平台的 **Pathfinder 1e (PF1)** 系统及其常用模组提供简体中文本地化支持。

本项目旨在整合分散的汉化资源，并补全 PF1e 系统更新带来的新文本空缺。

## 📦 汉化进度概览

### ✅ 完整汉化 (Fully Translated)
以下模组已完成绝大部分 UI 界面及设置项的汉化：

*   **CKL Roll Bonuses** (`fvtt-ckl-roll-bonuses`)
*   **CKL Advanced Templates** (`ckl-advanced-templates-pf1`)
*   **Aura Share** (`AuraShare`)
*   **Koboldworks – Health over Time** (`HealthOverTime`)
*   **Koboldworks – Item Hints** (`ItemHints`)
*   **Koboldworks – Companion Link** (`actor-link`)
*   **PF1 Spellbook Generator** (`SpellBookGenerator`)
*   **Spellcaster Utility PF1** (`spellcaster-utility-pf1`)
*   **PF1 Loot Sheet NPC** (`lootsheet-simple`)

### ⚠️ 部分汉化 (Partially Translated)
以下模组由于**原作者未开放完整的本地化接口 (Hardcoded Text)**，导致部分设置菜单或提示信息无法通过语言包进行翻译，需等待原模组更新支持：

*   **Koboldworks – Little Helper**
*   **PF1 Improved Conditions**

---

### 📜 PF1 核心系统汉化说明 (PF1 System Core)

本汉化包包含针对 **Pathfinder 1e 系统核心 (v11.x - v13.x)** 的汉化更新。

*   **基础来源**：继承了社区原有的汉化成果。
*   **增补内容**：针对系统版本迭代产生的大量新增文本进行了补全。
*   **⚠️ 免责声明**：
    由于 PF1 系统文本量极为庞大（数百万字），个人维护精力有限，新增部分的翻译使用了 **AI 辅助翻译**。因此，部分专有名词（如特定的法术名、专长名或规则术语）可能与国内通用的译名标准（如纯美苹果园/PFS 常用译名）存在出入。
    
    如果您在使用过程中发现术语不准确或歧义，**非常欢迎您提交 Issue 或 Pull Request 进行指正**，我会尽快进行修订和统一。

---

## 📥 安装方法 (Installation)

1.  打开 Foundry VTT 的 **Add-on Modules** 标签页。
2.  点击 **Install Module**。
3.  在底部的 **Manifest URL** 框中输入以下链接：
    ```
    https://github.com/EzithiStar/xgg_mod_chn/releases/latest/download/module.json
    ```
    *(请将上面的链接替换为您实际发布的 Manifest 链接)*
4.  点击 **Install** 并启用模组。

## 🤝 贡献与反馈 (Contribution)

这是一个开源项目，欢迎任何形式的贡献！

*   **反馈问题**：如果您发现翻译错误、漏译或术语不统一，请在 [Issues](../../issues) 中提出。
*   **提交代码**：欢迎提交 Pull Request 来改进翻译质量。

## 📄 许可证 (License)

本项目遵循 [MIT License](LICENSE)。
