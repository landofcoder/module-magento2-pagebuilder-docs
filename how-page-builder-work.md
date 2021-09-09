---
description: >-
  The module are using bootstrap framework (compatible with bootstrap 3,
  bootstrap 4 and comming soon bootstrap 5)
---

# How Page builder work

Our magento 2 page builder extension using core magento 2 widgets to build content of the cms page or block content.

Steps to design content with page builder:

* create page builder profile / element builder profile 
* design grid layout for there screen size \(desktop, tablet, mobile\) with bootstrap grid \(12 or 14 columns\)
* Create layout rows
* In Row, create columns
* In Column create widgets \(supported all magento 2 widgets, base widgets of page builder, 3th party extension widgets\)
* Save profile
* With Page Builder Profile, after save it will been auto create CMS page with identifier same as page builder profile.
* With Element builder profile, after save it will not show on frontend automatic. You should call it in cms page, cms block, create widget instance to show on any position on frontend. Also, can re use Element builder profile in Page Builder profile by call it via widget or load element profile.

