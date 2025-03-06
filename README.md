> [!NOTE]  
> This project is not affiliated with or endorsed by Vipps MobilePay. The Vipps MobilePay brand is property of Vipps MobilePay AS.

# Vipps MobilePay Donation Kit

<div>
![Vipps pill button example](buttons/svg/english/vipps_pill_en.svg)
![MobilePay rectangle example](buttons/svg/english/mobilepay_rect_en.svg)
</div>
<div>
![MobilePay pill button example](buttons/svg/english/mobilepay_pill_en.svg)
![Vipps rectangle button example](buttons/svg/english/vipps_rect_en.svg)
</div>

There are a lot of ways to receive donations as an independent free software contributor, such as Patreon, PayPal, Ko-fi, Buy Me a Coffee and Liberapay. This repository facilitates receiving donations the Nordic way: through Vipps and MobilePay.

## Who can do this?

To use Vipps or MobilePay for sending and receiving donations, you need a citizenship in one of the Nordic countries (Norway, Sweden, Denmark, or Finland. Sorry, Icleand, not you!), a phone, a bank account, and to be at least 15 years of age.

## About Vipps and MobilePay

[Vipps](https://vipps.no/) is a Norwegian payment solution. It's developed domestically and co-owned by many Norwegian banks. With a user count of more than 4 million in a country with merely 5.6 million people, it's an ubiquitous part of Norwegian everyday life.

[MobilePay](https://mobilepay.dk/) is the Danish equivalent of Vipps. In 2022, Vipps and MobilePay merged, and the two solutions are now interoperable with each other. The unified [Vipps MobilePay](https://vippsmobilepay.com/no) solution has a total of 12 million users and more than 1 billion yearly transactions in the Nordic countries (Norway, Sweden, Denmark, and Finland. Sorry, Iceland!)

Considering how widespread Vipps and MobilePay are, I think it's perfectly reasonable to spend some time setting yourself up for receiving donations through them if you're able to.

## Advantages

By setting up donations with Vipps and MobilePay, you can:

- Reduce friction for the 12 million possible donors who use Vipps or MobilePay, increasing their chance of donating
- Utilize domestic solutions with Nordic ownership, which isn't that bad of an idea considering current global affairs
- Earn some money! Who doesn't like that?

## Getting started

1. Set up a Vipps or MobilePay account for yourself if you haven't already. Choose the solution that's the most widespread in your country — Vipps in Norway and Sweden, and MobilePay in Denmark and Finland.
2. In the Vipps or MobilePay app on your phone, create a new box ("kasse" in Norwegian, "lipas" in Finnish), and give it a suitable name (e.g. "Brages tipsglass" — Brage's tip jar). A box is, well, like a box, where people can put money. You can transfer the money in this box to your own account whenever you'd like to. A 19 NOK fee is collected from the box for every 1000 NOK that's put in it, but in exchange you get nice convenience features such as being able to see how much has been donated, and a shareable link.
3. Link to the box anywhere you'd like: in your FUNDING.yml file, on your website, or in the README files of your projects.

> [!TIP]
> A link to a Vipps box can be turned into a fully working equivalent MobilePay link by replacing `qr.vipps.no` with `qr.mobilepay.dk`, and vice versa. By including links to both solutions, you make it clear that they are both supported.

## Buttons

Vipps and MobilePay have created a nice set of buttons that can be used to highlight that a payment can be made with either service. Unfortunately, these buttons are web components powered by JavaScript, and not suited for use in README files. An [official SVG kit](https://developer.vippsmobilepay.com/downloads/vipps-mobilepay-design-toolkit.zip) is provided, but it lacks buttons with "Donate" wording, even though the web component buttons have that as an option.

It's safe to say that my inner perfectionist could not live with this. To enable usage of Vipps and MobilePay buttons in README files, this repository contains pure SVG versions of them in all supported languages, constructed using official assets and values.

Grab the ones you'd like to use and use them as they are, just make sure to follow the relevant [design guidelines](https://developer.vippsmobilepay.com/docs/knowledge-base/design-guidelines/buttons/#design-guidelines). Oh, and if Vipps MobilePay ever adds a donate button to the official SVG kit, please use that instead.