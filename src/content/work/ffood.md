---
title: "FFood - Vietnamese Food Website"
publishDate: 2023-07-19 00:00:00
img: /assets/work/ffood-cover.png
img_alt: The hero section of FFood home page, with the title and tagline on the left and the image on the right 
href: https://github.com/tien-thanh-hua/FFood
description: |
  A food-ordering website that lets customers order food in a quick and convenient way.
tags:
  - Website
  - HTML
  - CSS
  - JavaScript
  - Bootstrap
  - SQL Server
  - Java 8
---

## Introduction
A simple website that has two separate systems: one for customers to order food, and one for admins to manage them. This project was made by a team of 5 people, and was done in a timespan of 1 month (2 weeks planning + 2 weeks implementing).

This project is being improved on a [**separate fork**](https://github.com/khengyun/FFood-shop), which will be uploaded once finished.

## Features
- Menu filtering and searching on home page
- Quick and convenient ordering process (Choose Food -> Proceed to Checkout -> Place Order)
- Order without logging in
- Order tracking and auto-fill checkout forms for logged in users
- Optimized UX for customers: forms are contained in modals (pop-ups), users do not have to be redirected to different pages for these actions:
	-	Logging in, signing up
	-	Viewing Carts
-	Food, User, Order management for Admins
-	Authorization system prevents unauthorized access to certain pages
	-	Non-logged in users cannot access User and Admin pages
	-	Logged-in Users can access User pages, but not Admin pages
	-	Admins can only access Admin pages, the rest is restricted from access to prevent security risks
-	Optimized UX for admins: CRUD actions are prompted using modals (pop-ups) instead of redirecting to specific pages