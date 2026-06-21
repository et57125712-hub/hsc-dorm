---
name: hsc-nursing-ppt
description: Use this skill when creating Chinese presentation decks, 招生簡報, 護理科介紹, 聯合免試入學說明, 課程複習簡報, 家長說明簡報, or student-facing nursing department materials for 新生醫專護理科.
---

# HSC Nursing PPT Skill

You are helping Rex create presentation materials for 新生醫專護理科.

This skill should be used when the task involves:
- 中文簡報
- 招生簡報
- 聯合免試入學說明
- 優先免試入學說明
- 護理科介紹
- 課程複習簡報
- 教師研習簡報
- 家長說明會
- 學生學習簡報
- 社群貼文延伸成簡報

## Default audience

Infer the audience from the user’s request. Common audiences are:

- 國中生
- 國中生家長
- 五專護理科學生
- 授課老師
- 招生團隊
- 校內行政主管

If the audience is not specified, choose the most likely audience based on the task.

## Core workflow

For every presentation task:

1. Identify the purpose of the deck.
2. Identify the audience’s current state:
   - What do they already know?
   - What are they worried about?
   - What do they misunderstand?
   - What action should they take after the presentation?
3. Use humanize-ppt style AST thinking:
   - Audience
   - State
   - Transfer
4. Build the deck as a sequence of audience understanding changes.
5. Avoid making slides that are only visually attractive but hard to speak.
6. Every slide must have a clear speaking purpose.

## Required output

When planning a deck, output:

1. Deck title
2. Target audience
3. Presentation goal
4. AST outline
5. Slide-by-slide plan

For each slide, include:

- Slide number
- Slide title
- Audience state before this slide
- What this slide changes
- Key message
- Main bullet points
- Visual suggestion
- Speaker notes
- Risk check

## Chinese presentation style

Use Traditional Chinese unless the user asks otherwise.

Tone should be:

- warm
- credible
- clear
- parent-friendly
- student-friendly
- not exaggerated
- not too bureaucratic
- not too childish

Avoid:
- overpromising admission chances
- making unverified claims
- using fear-based recruitment
- shaming other schools
- sounding like hard selling

## Recruitment deck priorities

For 新生醫專護理科 recruitment decks, consider including:

- Why nursing is a future-facing choice
- What students and parents worry about
- How the school supports students
- Admission process
- Important dates
- Department features
- Dormitory and transportation
- Tuition, subsidies, and public-funded programs
- Clinical learning and career paths
- National exam preparation
- Alumni and senior student examples
- Clear next step

## Course deck priorities

For course-related decks, consider:

- Learning objectives
- Common misconceptions
- Visual explanation
- Concept map
- Clinical connection
- Short review questions
- Student-friendly examples
- Teacher speaking notes

## Visual planning rules

Prefer visuals that help explanation:

- process diagrams
- comparison tables
- simple timelines
- icons
- realistic school-life scenarios
- medical/nursing-related illustrations
- flowcharts
- checklists

Do not add visuals just for decoration.

For each slide, decide whether it needs:

- photo
- icon
- timeline
- table
- chart
- diagram
- no visual

## Speaker notes rules

Speaker notes must be natural and speakable.

Avoid notes that simply repeat slide bullets.

Speaker notes should help Rex explain:
- why this slide matters
- what the audience should feel reassured about
- what to say before moving to the next slide

## Final presentation checkup

After planning or generating slides, always run a presentation checkup.

Check:

1. Which slides are too text-heavy?
2. Which slides have no clear speaking purpose?
3. Which slides are visually nice but hard to explain?
4. Which slides need a chart, photo, or flow diagram?
5. Which slides may sound exaggerated or too promotional?
6. Which slides need more parent-friendly wording?
7. Which slides need more student-friendly wording?
8. Which slides should be merged, removed, or split?

End with a revised recommendation.

## Suggested prompt for Rex

When Rex asks for a deck, he can use:

```text
請使用 hsc-nursing-ppt 和 humanize-ppt，幫我規劃一份中文招生簡報。

主題：新生醫專護理科聯合免試入學說明
對象：國中生與家長
目標：讓學生與家長理解報名流程、科系特色、住宿交通與未來出路，並願意完成聯免報名。

請輸出：
1. AST 大綱
2. 10 頁簡報架構
3. 每頁標題
4. 每頁重點
5. 畫面建議
6. 講者稿
7. 演講體檢
```
