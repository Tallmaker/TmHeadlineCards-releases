---
title: Property panel
order: 20
---
# Property panel

## Data

- **Category** (dimension): one card per value.
- **Time** (dimension): the order of the trend. The chart sorts it newest first to read the latest values, and draws the trend oldest to newest.
- **Value** (measure): the headline and the trend.
- **Comparison** (measure, optional): the change shown under the headline.
- **More measures** (up to four in all): each one after Value has a **Role**: **Comparison**, **Headline** (shown in place of the latest Value, for example `Sum(TOTAL <Category> Sales)` for a period total) or **Comparison 2** (a second change row). The role stays with the measure when you reorder them.
- **Card colour** (expression on Value, optional): a colour for each card, such as `if(Sum(Sales) >= Sum(Target), '#167447', '#a52a2a')`. It replaces the good or bad colour on the status targets. A result that is not a colour is ignored.

## Appearance

- **Layout**: the most columns; **Stacked**, **Compact** or **Side by side** cards; **Fit the object** or **Fixed, then scroll** with a card width and height; the text alignment; and the card order: data order, by value, or by change.
- **Labels**: show the category name at the top or the bottom, and the measure name under the headline.
- **Headline**: **Responsive** fits the largest size that fits; **Fixed** keeps the Styling font size. **Abbreviate** uses the app's number abbreviation when the number does not fit, or always. **Mute a headline from an earlier period** greys a card whose latest value is older than the others and names its period.
- **Comparison**: show the change as a **Difference**, a **Percent change** or **Both**. Choose the percent decimals, which direction is good (**Higher is better**, **Lower is better** or **Neutral**), the **Triangle ▲▼** or **Arrow ↑↓** indicator, a neutral band in percent of the Comparison, and the change label. An empty label shows "vs" and the Comparison name. When the Comparison is zero, the percent shows a dash.
- **Comparison 2**: the same options for the second change row.
- **Trend**: **Line**, **Area**, **Columns**, **Win and loss** or **None**. Areas and columns start at zero; win and loss marks each period against the Comparison by the good direction. Markers for the latest point, the latest with the highest and lowest, or every point. A scale per card or shared by all cards, a start at zero, a **Comparison** or **Average** reference line, missing periods as a gap, connected or as zero, and the number of latest periods shown.
- **Link**: a sheet that each card's **Open sheet ›** link opens, and the link text. The link is hidden in edit mode.
- **Tooltip**: tooltips on trend points (month, value, comparison, change) and on abbreviated headlines.
- **Status colour**: the change always takes the good or bad colour. Also colour the headline, the card accent bar, the trend, or the card background as a light tint; text on a tinted card stays readable.

## Styling

The native Styling panel. **General** sets the title, subtitle, footnote, background and border of the object. **Chart** sets:

- **Cards**: **Plain** (the default), **Outlined** or **Filled**, the border colour and width, the corner radius, the padding, and an accent bar on the left or top with its colour.
- **Headline**: the font size, colour and weight.
- **Category name**: the font size and colour.
- **Change**: the font size, the **Green and red** or **Blue and orange** colours, and your own good, bad and neutral colours.
- **Trend**: the colour, the line width, the area opacity and the marker size.

A colour you leave unset follows the app theme.
