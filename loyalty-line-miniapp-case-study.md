# Ruby & Co. Loyalty Program — LINE Mini App

**Role:** Product Owner — scoping, spec, and business logic
**Deployed with:** engineering support from Nuttapon Pattanavijit (production deployment only)
**Platform:** LINE Mini App

---

## Background

Ruby & Co. is a new brand with one hero product. Getting a first sale is one thing — getting a customer to buy again, without paid ads doing all the work, is the harder problem. A loyalty mechanism was the answer, but it needed to fit a pre-launch brand: low-cost to run, easy for customers to use, and buildable without a dedicated engineering team.

## Problem

Most loyalty program tooling is built for brands that already have volume — POS integrations, app downloads, CRM systems. None of that fits a solo-founder brand at pre-launch stage. The program needed to live somewhere customers already were, with minimal friction to join and minimal backend complexity to run.

## Why LINE Mini App

LINE is the dominant messaging platform for Thai consumers, and Ruby & Co.'s customer base is Thai. A LINE Mini App meant:
- No separate app download — customers interact within an app they already have open daily
- Lower build complexity than a standalone app or web portal with login
- Direct tie-in to how the brand already plans to communicate with customers (LINE OA)

## What I Owned

- **Program mechanics:** how customers earn and redeem loyalty value, structured to work for a single-SKU brand rather than a multi-product catalog
- **User flow:** the end-to-end path from first purchase → loyalty enrollment → repeat purchase, designed to add as little friction as possible for a customer who just wants to reorder a floor cleaner
- **Business rules and requirements:** the spec that defined what the system needed to do, handed off as the build requirements
- **Product decisions throughout:** every call on how the loyalty system should behave within the broader Ruby & Co. customer journey — this wasn't a hand-off-and-forget spec, I stayed the decision-maker through build and deployment

## Collaboration Boundary

I want to be precise about this, since it matters for how the work should be read: an engineering partner, Nuttapon Pattanavijit, handled getting the finished product deployed to production. He did not scope the program, define the logic, or make product decisions — that ownership sat with me end-to-end as PO. His role was infrastructure, not product.

## Status

Scoped, spec'd, and deployed to production as part of the Ruby & Co. launch plan — ready to activate alongside the brand's official launch.

## What This Shows

This is a self-contained example of PM/PO work in its purest form: identifying a business problem (retention without ad spend), choosing the right-sized solution for the company's actual stage (not over-building), writing the spec, and owning the product through to production — all without needing to write the implementation code myself.
