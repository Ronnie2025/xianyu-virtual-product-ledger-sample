# Xianyu Virtual Product Ledger Field Guide

This guide explains the minimum fields used in the free Excel and CSV sample. It is written for small digital product sellers who need a lightweight order, cost, margin, delivery, and after-sales review table.

中文说明：这份字段说明面向闲鱼虚拟资料卖家，用来记录订单、成本、毛利、交付、售后和每周复盘。

## Minimum Fields

| Field | 中文字段 | What It Means | Why It Matters |
| --- | --- | --- |
| Date | 日期 | Order or inquiry date | Enables daily and weekly review |
| Platform | 平台 | Xianyu, Xiaohongshu, WeChat, shop, etc. | Separates channel performance |
| Product | 商品名 | Digital pack, tutorial, template, or SKU name | Tracks sales and support by SKU |
| Price | 成交价 | Actual buyer price | Calculates gross sales |
| Quantity | 数量 | Number of units sold | Usually 1 for low-ticket digital products |
| Platform fee | 平台费 | Marketplace or payment fee | Prevents overestimating profit |
| Product cost | 资料成本 | Creation, curation, material, and tool cost | Digital products still have hidden cost |
| Other cost | 其他成本 | Traffic, packaging, labor, or extra cost | Shows real net margin |
| Order status | 订单状态 | Paid, inquiry only, cancelled, refunded, etc. | Shows conversion loss |
| Delivery status | 交付状态 | Not delivered, delivered, resent, etc. | Prevents missed fulfillment |
| After-sales question | 售后问题 | What buyers ask or struggle with | Improves listing copy and delivery scripts |
| Refund/cancel reason | 退款关闭原因 | Why the order was refunded or cancelled | Prioritizes product-page fixes |
| Net sales | 到手销售额 | Price x quantity - platform fee | Shows usable revenue |
| Total cost | 总成本 | Product cost + other cost + platform fee | Normalizes cost accounting |
| Estimated gross profit | 预估毛利 | Net sales - product cost - other cost | Decides whether a SKU is worth continuing |
| Gross margin | 毛利率 | Estimated gross profit / sales | Compares prices and SKUs |
| Review action | 复盘动作 | What to change next week | Turns records into action |

## Weekly Review

Review only four things each week:

1. Which product received the most questions?
2. Which product converted the most orders?
3. Which question caused cancellations or refunds?
4. What is the one listing, cover, price, or delivery change to make next week?

For a dedicated weekly review row, see [`weekly-review-template.md`](weekly-review-template.md) and [`../samples/weekly-review-sample.csv`](../samples/weekly-review-sample.csv).

## 5-Minute Test

Before building a full workbook, test the free Excel or CSV sample with three records:

1. One paid order.
2. One inquiry that did not convert.
3. One cancelled, closed, or refunded order.

If these three records already show a missing cost, confusing buyer question, or weak listing promise, the ledger is doing its job. The goal is not perfect accounting; the goal is to turn small selling signals into one concrete improvement action.

中文使用建议：先填 3 条真实记录，再看有没有漏算平台费、资料成本、工具成本和售后解释成本。最后只选一个动作改，不要一次改所有东西。

## Free Sample vs Full Excel Pack

| Item | Free Excel / CSV sample | Full Excel pack |
| --- | --- | --- |
| Core order fields | Yes | Yes |
| Example rows | Yes | Yes |
| Dashboard | Basic preview | Full dashboard |
| Cost and inventory sheet | No | Yes |
| Pricing calculator | No | Yes |
| Weekly review sheet | Manual field only | Dedicated worksheet |
| Listing copy and delivery scripts | No | Yes |

Use the free sample to confirm the workflow. Use the full Excel pack only if you need inventory, pricing, structured review sheets, and reusable selling scripts.

## Boundary

This sample is only for order tracking and review. It does not promise sales, traffic, profit, payback, or any business outcome. Do not use it as automatic money-making software or to bypass marketplace rules.
