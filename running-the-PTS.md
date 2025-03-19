# Running the Perl Toolchain Summit

These are my notes on how I think we do and should run the toolchain
summit. I'd like to have a clearly and openly documented model for the
event and how we run it. Why? (a) to ensure it's the best/right event
for the toolchain community, (b) transparency on who gets to attend and
why, and (c) as a play book to help people who might be (considering)
running future summit, (d) so potential sponsors can see the details of
what they're paying for, if they want to know more than the prospectus
tells them.

## What is the PTS?

An annual summit where we assemble as many of the key developers for the
"perl toolchain" as we can, for 4 days working together.

Some issues need multiple people to work together, and gnarly issues
take time to work through. Given most of this is volunteer effort,
giving people 4 days together gives an opportunity to push through
things that might not otherwise happen, or would perhaps take a long
time ("a face-to-face conversation is worth 1000 emails", or as nine put
it "high-speed discussions got us to a point that would have taken us a
year via email"). 4 days of concentrated time with the right neighbours.

Having people together means it's also an opportunity to have
face-to-face discussions to plan things that might be done after
the summit.

The goal is to set things up to maximise the value we get out of the
event, as individuals, for the community, and for the sponsors. If we do
it right, those things are all aligned.

## Principles

* The scope is the tools that people use with Perl in Production. More
  on the scope below.
* The people who attend are those who have been working on those tools
  for the last year or so.
* They are generally all volunteers, so the only way we can afford to
  run this is with sponsorship.
* Sponsors generally support the summit because they have Perl in
  Production, and they can see the summit is a key driving force behind
  the maintenance and evolution of the toolchain.
* Attendees are generally all working in proximity, so you need to get
  on with others. Regardless of your contributions, if you're a jerk you
  won't get invited, and if we discover you're a jerk at a summit,
  you're not likely to get invited back. If you harass people, the end
  result could be we eject you (never happened).

## Organising the Summit

These are all the things you need to get to the summit itself:

* Establish the organising team
* Pick the location
* Decide who's coming
* Select the venue
* Pick the dates
* Raise sponsorship
* Web site

### Organising team

There are four key roles. We now think these are best done by
separate people:

* The host: they live locally, organise venue (important to build a
  relationship), group meal etc. Speak the lingo, know local
  restaurants, etc
* Attendee wrangler (establishing the attendee list and ensuring
  they come).
* Sponsorship (prospectus, finding sponsors, delivering benefits)
* Money (invoicing, getting money from sponsors, reimbursing
  attendees, etc)

If you're one of these people, accept that you'll get less hacking
  done at the summit. Hofstadter's law applies to this.

One person is the chief organiser. Good if it is the host, but it
  doesn't have to be.

### Picking the location

* So far it's always been in Europe, as 60-70% of the attendees are
  from Europe.
* Pick a city/town that's relatively easy to get to from Europe, USA,
  Canada, Brazil, and Japan. i.e. in or near a "hub" city with a large
  airport that has many direct international flights
* Easiest if it's the hometown for one of the organisers, as it makes
  life easier if someone can go talk to the venue, look at the rooms,
  etc. Having a real person instead of an email as a contact usually
  makes people more comfortable too.
* Don't pick an "expensive city".

### Deciding who's coming

The goal is to pull "the right people" together, and for them to pull in
more of the right people, so a gravitational thing happens.

* Identify the core team and check if they think the core team should
  change this year. Roughly 10 people.
* The core team nominates people for the next wave, from which we
  identify roughly 10 people.
* Those two groups nominate more people, pulling in roughly another
  10 people.

Who are the core team?

* The lead people working on the core building blocks: PAUSE, CPAN
  clients, ExtUtils::MakeMaker, metadata spec, core test modules
* Lead people working on critical services & tools: CPAN Testers,
  MetaCPAN, Devel::Cover / CPAN Cover

People will come and go. Barbie was previously lead on CPAN Testers, but
now it's Doug Bell. MetaCPAN has now been deemed critical enough for
Olaf Alders to join the core in 2017. The core team for 2017 were:

* Andreas
* Leon T
* Doug Bell
* BinGOs
* Olaf Alders
* Paul Johnson
* Tux
* Miyagawa (was going to attend, but last minute couldn't)
* Chad Granum (was going to attend, but then couldn't)
* David Golden (couldn't attend)
* Rik Signes (couldn't attend)

That's probably the worst attendance record for the core team for a few
years at least. Picking the date sooner might have meant more people
could attend, but for 2 of those people probably not. Real life happens.

Are there other components, tools, or criteria we should use for the
core?

How are attendees nominated? There have been various approaches in
recent years

* Email people & ask on IRC: "who else should come?" See who bubbles up
  and make a list. Iterate.
* For Rugby, we asked people to nominate people, and I kept track in
  a spreadsheet, and sorted that on # votes. One problem was that
  some people nominated a lot of people, and others just nominated a
  few people.
* For Lyon, I asked the core people to nominate up to 5 people each. We
  picked the top ~10 people, and then asked them to nominate.
* Proposal for next year: people get 10 points. You can put all on
  one person ("I really want them to be there"), or spread across
  several people.
* Increasing the bus factor, mentoring new people.
* Let people ask to be considered? "here's what I'd work on". fixed
  number of spots / c.f. send a newbie.
* Resolving potential attendees quickly.

Thoughts:

* Attending the summit is a good way to draw in people who are starting
  to work on tools type stuff. How do we ensure that we're pulling in
  new blood?
* There could also be tools that we'd like people to develop/start
  using, so pulling in those people is good.
* Also Raku: ensuring the right Raku toolchain people are here
* This task is never-ending, right up to the event.
* Reality: there may be people you don't want there. "if he
  comes, I won't"

### Selecting the venue

* The last 2 years we've had the hacking space be the same place where
  we're staying. This minimises travel time each day. I think we can now
  establish this as "how we do it".
* Single rooms for everyone. It means we need to raise more sponsorship,
  but given the intense time spent together, it's good to have your own
  space at night. 2016 was the first year we did this, and got good
  feedback on it. Also now fixed, I think.
* Two meeting rooms. Generally better if everyone can fit into one of
  them, so the other can be used for discussions without disturbing
  everyone else. Larger break-outs have been a bit trickier to handle
  this year.
* Good if there are some kind of breakout spaces. The bar works fine
  most of the time in Lyon, and similarly, the bar worked well at Rugby.
* Decent (enough) selection of restaurants nearby, catering for
  vegetarians & vegans.
* Wifi that can handle 35 people (laptops & phones) (c.f. Berlin:
  separate venue close to the hotel, with solid wifi).
* Airport hotel?
* Too many rooms would fracture the group.

### Picking the dates

* Generally we try to land it from mid-March to mid-May (doesn't clash
  with Perl conference season & avoids the long school holidays). Here
  are the dates for all events:
  * Oslo 2008: Sat April 5th to Mon April 7th
  * Birmingham 2009: 28th to 30th March
  * Vienna 2010: April 10th to April 12th
  * Amsterdam 2011: April 16th through 18th
  * Paris 2012: March 30th through April 1st
  * Lancaster 2013: April 12th through 14th
  * Lyon 2014: March 13th through 16th
  * Berlin 2015: April 16th through 19th
  * Rugby 2016: April 21st through 24th
  * Lyon 2017: May 11th through 14th
  * Oslo 2018: April 19th through 22nd
  * Marlow 2019: April 25th through 28th
  * Lyon 2023: April 27th through 30th
  * Lisbon 2024: April 25th through April 28th
  * Leipzig 2025: May 1st through May 4th
* Once the core team are picked, find out which weekends in the above
  range they definitely can't do
* Pick the weekend or weekends that maximise core attendance. For the
  past 2 years this immediately identified a best weekend.
* Obviously need to pick a weekend when the venue is also available.
  Check whether venue costs change significantly in certain weeks (only
  an issue if there's a massive price hike during a school holiday,
  which does happen in Europe).
* Avoid week-end close to some bank holiday, for instance May 1st in
  France: a lot of things are closed, and it is a demonstration day.
* I think everyone's happy with the 4-day weekend. Longer would be
  hard to justify (to employers & families). I think we can consider
  this fixed.

### Raising sponsorship

* Create a sponsorship prospectus with clear sponsorship levels &
  benefits. Also needs to concisely present what it is (and isn't), and
  the benefits (of the event).
* We have an established pool of sponsors, a different subset of which
  chooses to sponsor each year
* Need to keep working on adding fresh sponsor potential every year
* Sponsors (seem to) like the branded blog post.
* Sponsors (seem to) like invoices.
* Get people to bring t-shirts with their employer's logo on, to get it
  in pictures for tweets. Sponsors like tweets thanking them, and like
  to get their names / logos in photos as well. These are so cheap, so
  we should be doing more of them, before, during, and after the summit.
* The mentions in attendees' blog posts are appreciated too.
* Hofstadter’s Law applies to this.

## Running the Summit

* Have a stand-up every day at the same time. Would people prefer
  something like 10am rather than 9am? (my goal with 9am was to get it
  done before everyone starts). Have them be concise: 30 people speaking
  for 1 minute eats up half an hour.
* Have a fixed time when discussions will happen. Doing this around
  mid-day will let people bring lunch. Get people to pre-announce. Have
  slots, fill on board.
* If the budget allows, have a sponsored meal on the Thursday.
* Have a Wendy: healthy food available nearby, so people can graze &
  lunch without breaking away
* People record on the wiki what they do/achieve as they go along.
* Need a list of sponsors, which you work through, tweeting to thank,
  mention etc
* Need printed checklist of attendees
* Having an attendee who can both hack and take photos has been very
  helpful (at least to the organisers).
* Create a markdown file that lists the sponsors, to make it easy for
  people to acknowledge them in blog posts
* Organisers solicit feedback
* Have a retrospective at the end, every time?
  * What was a pain?
  * What was missing?
  * Who else should have been here?
  * How can we make this better?
* Have a knowledge-sharing mechanism?
  * pick one day for this or last 1 hour of every day

## After the Summit

* Attendees blog soon after. Remember to thank sponsors. Have a snippet
  to copy/paste with all sponsors and links.
* Organisers do an official blog posts with pictures. Mention all
  attendees, and some flavour of what they did.
* Follow up with every sponsor, thanking them for support and asking how
  it was for them.
* Ensure everyone gets reimbursed
* Work out how much money is left over to roll-over to next
  year's summit

## The money role

* "Keep track" is the keyword
* When a sponsor commits to supporting the summit, the sponsorship
  organiser passes a contact to the money person.
* Money person contacts them to:
  * ask if they want an invoice, and their info for the invoice
    (contact, address, currency)
  * Tell them the ways we can receive funds, and ask what their
    preference is.
  * Ask them what logo and text we can add to the sponsor page
* Organise the funds transfer.
* Keep track of all sponsors, e.g., in Google docs, with a status
  against each one (at least committed/invoiced/paid/denied).
* Periodically tickle sponsors who haven't yet paid.
* Once they've paid, confirm back to them and thank them.
* When the venue and hotel are choosen, ask for an quotation, 
  if a deposit is required, how to proceed with payment.
* Update budget spreadsheet (in google docs)
* Reimburse organizers if they paid for food, venue...
  Ask them to keep invoices, tickets... (depending on the
  regulation of the supporting organization)
* Reimburse attendees
  Keep track of who must be reimbursed for travel / hotel / both / none

## Schedule

* Establish organiser and location
* Late September / early October: clarify core team and email them to
  establish viable weekends
* Pick a tentative weekend. Ensure it doesn't clash with other events
* Mid-Late October: identify the second wave of attendees & invite them
* Talk to potential venue(s) and see if potential weekends work
* End October: fix the weekend
* November: fix the venue, decide target number of attendees, and
  estimate required funds
* November: identify & invite the third wave of attendees
* November: update sponsorship prospectus and start contacting
  established sponsors
* December: announce
* Iterate over sponsors & attendees

## Ideas / Questions / Thoughts

* Have a "sponsor board" which has names and logos of all sponsors? This
  could be strategically positioned behind people, and if we have
  someone like Lee, we can ask them to take pictures of individuals
  against it too. Additional sponsor benefit and visibility for
  sponsors. [suggestion from Sawyer]
* Wifi is an issue every year. Would it be workable to bring our own
  wifi hub each year, and hook it into the local network. That way at
  least we'd all stay connected, even if someone does occasionally need
  to get the internet sorted. [suggestion from Olaf]
* We should have an explicit code of conduct. For Lyon 2014, the code of
  conduct was: "Be excellent to each other. If anything is less than
  excellent, talk to the organisers."
* Have a single travel agent organising flights, to get a
  discount? [Leo]
* emailing list

