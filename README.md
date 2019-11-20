# Hello! We come in peace.

## About

This is a security research project by 2e.lc ("two elk"), an operating division of Machines Never Sleep, LLC, a cybersecurity research and development company. We're not here to cause harm, sell you a product, or anything else like that. We're just a bunch of curious nerds doing nerd stuff on the internet.

This project is currently online and collecting data. In short, we're testing to see if sites will run (safe) Cross-Site Scripts from a number of unlikely vectors. If we find anything, we'll be contacting the website owners to responsibly notify them and help keep the internet safer.

## Concerned Citizens

If you're here because:
 - you were redirected here, or
 - an unexpected script was run in your browser, or
 - you have seen DNS traffic for 2e.lc, or
 - your console log has told you to go here

Please reach out to us, either via personal contact information [on our site](https://mns.llc) or by opening a GitHub issue. We would be interested to hear what happened and will help to the best of our ability in *personal* (non-professional, you cannot hold us liable, we provide no warranty/guarantee/etc) capacity.

Our goal throughout all of this is to be transparent and trustworthy. This repository contains all of 2e.lc, including server-side scripts to ingest and parse data. If your site did load our script, it beacons a small amount of information back to us for diagnostic assistance. How much data? Hardly any! Certainly much less than the average advertisement. The data we collect is:

 - a random ID (which is ephemeral - it doesn't stick around, and isn't tied to you)
 - the IP you connect to the internet with, and the country that IP appears to be in
 - the time of the event
 - whether or not you connected using HTTPS
 - the URI that you accessed
 - the origin of your request
 - the referrer to your request
 - the user-agent string of your browser

None of this could be reasonably used by us to identify you. Frankly, we're just not that into you - we're much more interested in what site you were on. If you have concerns about any of this, please contact us - we'd love to discuss.

## Technical Details

Sorry, you'll want to check the wiki if you want to learn about our research methodology, system design, etc. This readme is for concerned citizens only while research is running.