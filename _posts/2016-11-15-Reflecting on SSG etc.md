---
layout: post
title:  "Reflecting on SSG etc"
date:   2016-11-15
categories: assignment questions
comments: true
---

<h3>What do you think of pre-compiling your CSS?
        Compare to regular CSS
        Which techniques did you use?
        Pros and cons?</h3>
Jag tycker att det mestadels bara finns fördelar, speciellt när man använder sig av variabler för att konfigurerar vissa classer. 
Sass kan vara det mysigaste som har hänt programmering då man kan få en bättre struktur på sin CSS, speciellt håller man sig DRY. 
Den enda egentliga nackdelen jag kan se att kompilera all css är att om man har en specifik del av sin webbplats som ska ha en annan  
struktur, kommer den CSS filen alltid att laddas in, även om man inte befinner sig på den specifika sidan på webbplatsen. Men den mängden  
data borde inte kunna påverka användarens upplevelser kring webbplatsen.

<h3>What do you think of static site generators?
        What type of projects are they suitable for?</h3>
Jag föredrar starkt att förkompilera min webbplats genom Jekyll. Framförallt så slipper jag att göra en template för alla sidor, och sen 
när jag väljer att ändra strukturen eller lägga till ett nytt element när mig projekt är färdigt, måste jag gå in på varje sida och lägga 
till mitt nya element. Däremot så känns det som om att sidan kan ta lite längre att ladda än en traditionellt hårdkodad webbplats. Så jag 
tänker att mindre webbplatser som inte har särskilt mycket innehåll är SSG ett bra verktyg att använda sig av.

<h3>What is robots.txt and how have you configure it for your site?</h3>
Man lägger till en robots.txt i root foldern och bestämmer vilka typer av robotar som får komma åt min webbplats. Man kan blockera "snälla" robotar,
men de "dumma" robotarna kan man inte göra så mycket åt. Jag har valt att blockera allt förutom Google's robot.

<h3>What is humans.txt and how have you configure it for your site?</h3>
Precis som robots.txt lägger man till humans.txt i root foldern. Jag har valt att skriva mina kontaktuppgifter, eftersom jag inte är den del av ett team
gjorde jag min text ganska nerskalad.

<h3>How did you implements comments to blog posts</h3>

<h3>What is Open Graph and how do you make use of it?</h3>
