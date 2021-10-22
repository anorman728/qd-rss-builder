# Quick & Dirty RSS Builder.

Takes in STDIN and outputs an RSS file.

Format for STDIN is like follows:

    !meta
    How to Stop Worrying and Start Living
    https://fake-dale-carnegie-site.com
    https://fake-dale-carnegie-site.com/feed.xml
    Blog posts from friends of Dale Carnegie (not real-- just for demo purposes).

    !newentry
    Six Major Troubles Hit Me All At Once
    How C.I. Blackwood handled them.
    Sat, 26 Jan 2019 00:00:00 CST
    https://fake-dale-carnegie-site.com/blog/six-major-troubles-hit-me-all-at-once
    Now this is a story all about how my life got twist-turned upside down.
    I'd like to take a minute, just sit right there.  I'll tell all about
    the story how I became prince of a town called Bel-air.

    !newentry
    I Can Turn Myself into a Shouting Optimist Within an Hour
    How Roger W. Babson spent all his money on sucrets.
    Wed, 23 Jan 2019 00:00:00 CST
    https://fake-dale-carnegie-site.com/blog/i-can-turn-myself-into-a-shouting-optimist-within-an-hour
    In West Philadelphia, born and raised, on the playground is where I
    spent most of my days.  Chillin' out maxin', relaxin' all cool, I was
    shootin' some b-ball outside of the school.

    !newentry
    How I Got Rid of an Inferiority Complex
    Elmer Thomas is now an arrogant jerk.
    Tuesday, 22 Jan 2019 00:00:00 CST
    https://fake-dale-carnegie-site.com/blog/how-i-got-rid-of-an-inferiority-complex
    When a couple of guys who were up to no good started makin' trouble in
    my neighborhood.  I got in one little fight and my mom got scared.  She
    said "You're moving with your auntie and uncle in Bel-Air."

This does *not* parse the date!  It'll need to be in the appropriate format first.
