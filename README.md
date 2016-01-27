##FEATURES:##
1. table-based, modular HTML email (will ultimately have only inline styles)
2. no media queries; width of 600px
3. placeholders for logos, social icons, and other images
4. use of rems and ems so that each module can be resized independently
5. thoroughly-documented, validated code
6. CSS fix for superscript HTML entities (&reg;) -- line-height distortion is anticipated, eliminated


##DIFFERENCES BETWEEN BUILD AND PSD:##
1. exact design ratios not possible:
  * Chrome does not support media queries, so compromises to layout had to be made
  * The original PSDs do not adhere to the convention of not exceeding a width of [approx.] 600px
2. button size increased in order to increase usability in small viewports
3. added underlined phone numbers that trigger the phone application, for increased usability
4. when the content of the "quad section" (the area with the gray background) exceeds a certain word-count, the 4 black squares no longer adhere to the desired design ratio.
5. A different font has been used for the HTML build since only a limited number of fonts are suggested for HTML email


##QUESTIONS, POSSIBLE ISSUES:##
1. URL to hosted images? (social icons, etc)    { perhaps this is not our responsibility }
2. Late in the testing phase, Gmail started to give me this message: "This message has been modified to fit your screen. Tap here to show original." I'm not sure what would cause this to start happening. When this occurs, the email is not displayed properly.


##REQUIRED ACTIONS:##
1. update all links
2. generate necessary [content] placeholders (e.g. [Customer Name])
3. replace all image placeholders (logo, social icons, other images)
