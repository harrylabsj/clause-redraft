---
name: clause-redraft
description: Redraft unclear or risky contract clauses into clearer, more balanced language
version: 1.0.0
tags: legal, contract, document-automation, drafting, review
---

# Clause Redraft

Redraft unclear or risky contract clauses into clearer, more balanced language. Use when the user asks about 条款改写、改合同、条款优化、合同措辞、改写这句话、条款润色, or wants to improve specific contract language. This skill provides drafting assistance only and does not constitute legal advice.

## Usage Scenarios

### Scenario 1: Basic Clause Rewriting
**User input:** "帮我改写这个条款：'Payment due upon completion'"
**Expected output:** The skill receives the clause text, identifies issues (ambiguous timing of "completion"), generates 2-3 alternatives with different approaches: Balanced version ("Payment due within 30 days of invoice date or within 10 days of acceptance of deliverables, whichever is earlier"), Protective version, and Simple version. Explains what was changed and why. Recommends attorney review for important clauses.

### Scenario 2: Rebalancing a One-Sided Clause
**User input:** "这个条款太偏向甲方了，改平衡一点：'Company is not responsible for anything'"
**Expected output:** The skill identifies the clause as unbalanced. Generates a balanced alternative ("Company's total liability shall not exceed the total amount paid by Client under this agreement in the 12 months preceding the claim") with explanation of how it preserves both parties' reasonable protections. Also provides a simpler plain-language version if needed.

### Scenario 3: Simplifying Complex Legal Jargon
**User input:** "用简单的话重说一遍这个保密条款" (followed by a complex confidentiality clause)
**Expected output:** The skill analyzes the clause for core meaning, generates a plain-language version that removes unnecessary legalese while preserving legal intent, also provides a more standard legal version as backup. Explains what was simplified and why, and notes any nuance that was lost in simplification.
### Scenario 4: 租房合同退租条款太苛刻
**User input:** "中介给的租房合同有个条款说'提前退租押金不退还要再付一个月租金'，这个条款合理吗？能不能改？"
**Expected output:** 分析条款的法律效力：根据《民法典》第585条和《最高人民法院关于审理城镇房屋租赁合同纠纷案件具体应用法律若干问题的解释》，该条款可能构成惩罚性违约金，尤其是同时约定'不退押金+再付一个月'存在被认定过高的风险。给出修改建议：将违约后果改为'提前30天通知，押金扣一半'或'违约金不超过一个月租金'。提供完整的修改条款文本供参考。

## Overview

This skill helps users rewrite unclear, ambiguous, or potentially risky contract clauses into clearer, more balanced language. It provides alternative wording while preserving the intended meaning.

**⚠️ Important Disclaimer**: This tool provides drafting assistance only. It does not constitute legal advice, nor does it replace professional legal counsel. Always consult a qualified attorney before finalizing contract language.

## When to Use This Skill

- A clause seems unclear or ambiguous
- Language feels one-sided or unbalanced
- You want more professional contract wording
- Translating informal agreements into formal contract language
- Simplifying overly complex legal jargon

## Limitations

- Only provides **suggested alternatives**, not definitive language
- Cannot assess enforceability under specific jurisdictions
- May not capture all nuances of the original intent
- Not a substitute for professional legal drafting

## Workflow

1. **Receive clause text** — User provides the clause to be redrafted
2. **Identify issues** — Analyze for ambiguity, imbalance, or unclear language
3. **Generate alternatives** — Provide 2-3 alternative versions with different approaches
4. **Explain changes** — Describe what was changed and why
5. **Suggest review** — Recommend attorney review for important clauses

## Redraft Approaches

### Approach 1: Balanced (Recommended)
- Fair to both parties
- Clear obligations for each side
- Reasonable protections

### Approach 2: Protective (Favorable to you)
- Stronger protections for your interests
- Still reasonable and enforceable
- May require negotiation

### Approach 3: Simple (Plain language)
- Removes unnecessary legalese
- Easier to understand
- May sacrifice some precision

## Common Redraft Scenarios

### Payment Terms
**Before**: "Payment due upon completion"
**After**: "Payment due within 30 days of invoice date or within 10 days of acceptance of deliverables, whichever is earlier."

### Termination
**Before**: "Either party may terminate this agreement at any time."
**After**: "Either party may terminate this agreement with 30 days written notice. Upon termination, Client shall pay for all work completed through the termination date."

### Confidentiality
**Before**: "All information is confidential forever."
**After**: "Confidential Information shall be held in confidence for a period of 3 years from disclosure, except for trade secrets which shall be protected indefinitely."

### Liability
**Before**: "Company is not responsible for anything."
**After**: "Company's total liability shall not exceed the total amount paid by Client under this agreement in the 12 months preceding the claim."

## Usage

### Basic Redraft
```
"帮我改写这个条款"
"这句话怎么写更清楚"
"优化一下这个条款"
```

### With Context
```
"我是乙方，帮我改一下这个条款"
"这个条款太偏向甲方了，改平衡一点"
"用简单的话重说一遍"
```

## Output Format

For each redraft request:
- **Original**: The clause as provided
- **Issues Identified**: What's problematic about the original
- **Alternative 1 - Balanced**: Fair version
- **Alternative 2 - Protective**: Version favoring your interests
- **Alternative 3 - Simple**: Plain language version
- **Recommendation**: Which version to consider and why

## References

For redrafting templates and patterns, see:
- [references/redraft-templates.md](references/redraft-templates.md) — Clause redrafting template library

## Privacy Note

Clause content is processed for redrafting only. No content is stored or transmitted to third parties.
