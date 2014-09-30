So far, we've talked mostly about what makes good code, and making and using checklists to filter out common mistakes and help you zoom in on more subtle ones quickly. Here are some more techniques that make for good code reviews, largely from [this study](http://smartbear.com/SmartBear/media/pdfs/WP-CC-11-Best-Practices-of-Peer-Code-Review.pdf)

 - **Limit the scope** No one can sit and read 10000 lines of code at once. Code should be reviewed ideally 100-200 lines of code at a time, and never more than 500. This lets you focus on each line, without it eating up your whole day. Consider requiring that new contributions be of a maximum size to accommodate this, and review just one such contribution per day.
 - **Never review for more than 90 minutes** After a while, staring at the same piece of code becomes futile. A big code review session should be at most 90 minutes, and potentially much less for small contributions.
 - **Insist contributions be annotated** By making contributors explain each bit of their code, not only do you get a walkthrough that helps clarify their intentions, *there will actually be fewer bugs*! By verbalizing and writing out what each piece of code is supposed to do, the author will often catch their own mistakes before even submitting their work.

### Live Reviews
The strategies discussed so far assume no face contact between the person who writes the code, and the person who reviews it. But, if like many researchers you are working in a lab or group setting, some useful opportunities for group discussions of code arise.

[TBD]
