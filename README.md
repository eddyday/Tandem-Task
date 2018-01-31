# Tandem

When designing this, I was torn between going for a design that was unique and based off my own vision, or going for a design that was faithful to the pre-established branding already evident on the site. I thought in the end it would be more prudent to go for the latter, as I wanted to demonstrate that I have an eye for maintaining existing branding.  Sticking to style guides is an area I’m a stickler for!

The design is generally faithful to Tandem’s current branding with the obvious exception of the typography. Lato is a decent font in itself though it is quite different to the default fonts used by Tandem on the current site and it does have an impact on the general aesthetic. I was tempted to grab the fonts Tandem currently uses on their site and incorporate them, but I felt it best to strictly observe the guidelines of the brief.

As requested, the bullet points in the intro and lowdown sections are being pulled from a json file. I originally embedded the json in the HTML file but the code became messy this way and hosting it in a separate file helped to keep the code cleaner and better organised. I’m using AngularJS to pull this data as it’s very well suited for this task.

The CTA toggles between the benefits and lowdown. I thought this was better from a user perspective and it would be more obvious that new data had been loaded without scrolling further down the page. I was tempted to load the lowdown after the benefits when the button was pressed but it wouldn’t have been immediately obvious that it had been loaded unless the user was automatically jumped to the correct section, which felt clunky and inconsistent with how the rest of the site navigates the user. Switching between benefits and lowdown seemed a better call in this instance and the subtle fade helps to inform the user of the change.

The header of the page proved tricky. The included image in the brief, being of a fairly boxy aspect ratio, was not suited to a wide banner image. As a result, I borrowed one of the header images from tandem’s site and cropped it to give the image context relevant to the content of the page. The image included in the brief accompanies the benefit text directly under where it works much better with the intended layout. 

I thought about which colours to use. I’m personally partial to the blue but I thought it would be nice to see all the colour choices. I thought it would be cool to change the colour scheme depending on the device the user was viewing the site on. So I did just that and the colour scheme changes as thus:

Mobile: Mint
Small device: Pink
Medium-sized device: Orange
Desktop: Blue

Thought that was an interesting way of getting the various colours represented in their own way!

That’s all, I believe but I’m more than happy to clarify any other questions you may have!

Ed
