---
title: Getting started
order: 10
---
# Getting started

Add Tm Headline Cards to a sheet and give it data. These steps use the Qlik Cloud edit mode.

1. Open the sheet and choose **Edit sheet**.
2. Open the Custom objects panel and drag **Tm Headline Cards** onto the sheet.
3. Add the **Category** dimension. Each value gets one card. Skip it to get one card, or one card for each Value measure.
4. Add the **Time** dimension, such as a month or a date. It orders the trend.
5. Add the **Value** measure. The card headline is its latest value.
6. Optionally add the **Comparison** measure, such as a plan or last year's value. The card then shows the change.
7. Optionally open **Appearance** for the layout, the change and the trend, and **Styling** for the look of the cards.
8. Choose **Done editing**.

## Limits

The chart shows up to 24 categories. With more, it shows a notice instead of a partial set of cards; filter the sheet to 24 or fewer. Each trend shows the latest 60 periods, and a notice says when older periods are hidden. All cards share the same periods, so a period a category lacks shows as a gap.
