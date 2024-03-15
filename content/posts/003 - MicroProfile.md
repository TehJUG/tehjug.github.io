---
date: "1397-08-09"
title: "معرفی میکروپروفایل"
keywords: "جاوا، میکروپروفایل"
draft: false
tags: ["MicroProfile"]
subtitle: "میکروپروفایل"
description: "خلاصه ای از کلیدواژه های ارائه مجید با موضوع Jakarta EE و MicroProfile
"
author: "حسام غیاثی"
readmore: true
---

**خلاصه ای از کلیدواژه های ارائه مجید با موضوع Jakarta EE و MicroProfile**


جاوا از ابتدا با پشتیبانی از موارد زیر شروع به کار کرد: cross platform, connectivity, enterprise software

Infinispan vs Redis: Redis is single-thread and single-core but Infinispan has better support for clustering. It is an example of good connectivity support in Java.


RI = Reference Implementation 
پیاده سازی مرجع هر استاندارد در Java EE


پس از خرید سان مایکروسیستم توسط اوراکل، شرکت اوراکل بسیاری از پیاده سازی های مرجع را کنار گذاشت که موجب افت Java EE شد.


‌و MicroProfile تلاشی است برای پر کردن خلاء ناشی از کند بودن پیشرفت Java EE بود و در سال ۲۰۱۸ استارت خورد. شرکتهای مختلفی در فرایند تهیه specification های آن دخیل هستند و به نوعی industry-accepted است.


TCK = Technology Compatibility Suit


SmallRye = A collection of implementations of MicroProfile specifications.

 
Redhat Weld = RI for CDI (Jakarta EE)


Quarkus and Helidon are both implementations of MicroProfile


There is an IntelliJ plugin that support replacement of Javax with Jakarta in any project.


Different profiles of Jakarta EE:
Web: example implementation is Tomcat
Full: example implementation is jboss
Core


Helidon is very new and low on educational resources
Quarkus is very efficient for running on containerized environments.



همزمان با توسعه MicroProfile، با اهدای Java EE به بنیاد Eclipse، سرعت رشد Jakarta EE هم بیشتر شده است و ورژن های جدید EJB و تغییرات آن مؤید این موضوع است.


به صورت خلاصه، در این ارائه ما با جایگاه و اهمیت MicroProfile، پیاده سازی های آن، پیشرفت های Jakarta EE و فرصتهایی که برای ما برنامه نویسان جاوا در آینده فراهم می آورند آشنا شدیم.