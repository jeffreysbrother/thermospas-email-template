##FEATURES:##
1. table-based, modular HTML email (will ultimately have only inline styles)
2. no media queries; width of 600px
3. use of rems and ems so that each module can be resized independently
4. thoroughly-documented, validated code
5. CSS fix for superscript HTML entities (&reg;) -- line-height distortion is anticipated, eliminated
6. Absolute paths to hosted images (social icons, etc)
7. Thoroughly-tested on desktop (Gmail and Thunderbird in Chrome, Edge, FireFox, Internet Explorer 11) and mobile (Gmail app, iOS Mail app)


##DIFFERENCES BETWEEN BUILD AND PSD:##
1. exact design ratios not possible:
  * Chrome does not support media queries, so compromises to layout had to be made
  * The original PSDs do not adhere to the convention of not exceeding a width of [approx.] 600px
2. button size increased in order to increase usability in small viewports
3. added underlined phone numbers that trigger the phone application, for increased usability
4. when the content of the "quad section" (the area with the gray background) exceeds a certain word-count, the 4 black squares no longer adhere to the desired design ratio.
5. A different font has been used for the HTML build since only a limited number of fonts are suggested for HTML email


##POSSIBLE FUTURE ISSUES:##
1. Late in the testing phase, Gmail started to give me this message: "This message has been modified to fit your screen. Tap here to show original." When this occurs, the email is not displayed properly. I've included a fix for this issue&mdash;a snippet just before the closing body tag&mdash;which should not be removed.
2. The email template will break in Gmail if the HTML dash entity is used.
3. I initially sized the social icons in the footer with a height and width property (in ems), but ultimately eliminated the height property and switched to pixels...this resolved an inconsistency in how the iOS Mail app was displaying these images.


##REQUIRED ACTIONS:##
1. put all CSS inline, test again after updating any content, images, or links
