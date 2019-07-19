# The Monkees

This Project was undertaken for the Code Institute. This is the First Milestone Project undertaken to demonstrate my HTML5 and CSS capability.

I decided to create a website for the band, The Monkees. The website provides an overview of the band, their catalogue (audio and video), upcoming event details, and a number of mediums for users to reach out to the band, for example, through social media.

## UX

I designed this website with two users in mind: 1) **Fans**, and, 2) **Event Organisers**.

For **Fans**, I wanted the website to provide important information upfront(i.e. on the homepage) to engage them immediately. I also wanted to use this opportunity to prompt them to explore the website further by making use of call to action buttons, contrasting colours, and, the use of various multimedia (e.g. audio, video, images, etc.)

For **Event Organisers**, I wanted the website to showcase the band's work and highlight the active nature of the band. This was achieved byproviding a number of upcoming events, latest single, and, recent news. To expand on this the Music page provides a snapshot of the band's catalogue, showcasing their variety. Finally, I created a Booking page which enables Event Organisers to reach out to the band with propositions, capturing only the relevant details (e.g. name, venue size, contact details, etc.) and providing an additional information textbox to enable any adhoc/event specific detail of note.

## Features

### Features implemented

1. Collapsable navigation bar on smaller devices with a popdown menu
2. Embedding audio and video files using HTML5
3. Mobile first design

### Features to be implemented

1. **Implementation of the Booking Form**: submission of the booking form should result in the data inputs being transferred to a back-end system which either, stores it in a database, and/or, sends out a structured email with the data included.

## Technologies Used

- HTML
- CSS
- Bootstrap (v4.3.1)
- Bootstrap JS (v4.3.1)
- JQuery (v3.3.1)
- Font Awesome (v5.8.1)

## Testing

**Browser and Device Testing**: The website was tested on the following devices using a variety of browsers, and screen sizes, to ensure the mobile first design rendered as expected:

- Apple iPhone (Safari)
- Samsung Galaxy (Chrome)
- Windows Laptop (Edge)
- Macbook Pro (Chrome)

**Links**: All links to _external_ websites open in a new window to ensure user is not directed away from this website.

**Booking Form**: Invalid data (e.g. no-entry for required fields, invalid email address format for email, etc.) was entered to ensure the checks were functional. Invalid entries received relevant error messages.

**Multimedia**: Videos and Audio files were all tested to ensure they were working, including the YouTube embedded videos.

**Notable Findings**: Due to the varying amount of content for each page, some pages did not have enough to ensure the footer sat flush with the bottom of the browser window (taking account of the varying screen sizes). To address this I used the CSS Calc function to calculate a minimum height based on viewport size - see the styling for **main** attribute in the CSS style sheet.

## Deployment

Using GitHub Pages I deployed the website from the Master branch. You can see the deployed website [here](https://jyoung90ie.github.io/The-Monkees/).

Using the Master branch means that all updates will be reflected on the deployed website.

If you wish to run this project locally, you will need to download and install Git to your computer - see [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Once you have installed Git, you can copy and paste the following code into your terminal:

```terminal
git clone https://github.com/jyoung90ie/The-Monkees.git
```

When this has completed, you can access the website locally by opening the _index.html_ file.

Please note: all links and multimedia files use relative file referencing, so long as you maintain the same folder structure as downloaded by Git, you can store the folder any where on your computer and it will continue to function.

## Credits

### Content

Content for news articles came from the sources listed below:

- [Interview With Micky Dolenz](https://www.undertheradar.co.nz/news/15891/Interview-Micky-Dolenz-of-The-Monkees.utr)
- [The Monkees To Release Christmas Party, Their First Ever Holiday Album](https://www.monkees.com/article/the-monkees-to-release-christmas-party-their-first-ever-holiday-album)

Band member background information extracted from [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)

### Media

- Audio and Video files were obtained from the [Code Institute repository](https://github.com/Code-Institute-Org/project-assets) and YouTube
- Homepage Upcoming Events logos were obtained from:
  - [Electric Picnic](http://www.oxygen.ie/electric-picnic-2015-line-up-announced/)
  - [V-Festival](https://www.designweek.co.uk/issues/6-12-march-2017/v-festival-unveils-youthful-rebrand-clearer-reference-to-virgin/)
  - [Glastonbury Festival](hhttps://www.glastonburyfestivals.co.uk/)
- All other images used in this site were obtained from the [Code Institute repository](https://github.com/Code-Institute-Org/project-assets) and Google Images

### Acknowledgements

Inspiration for this project came from the Code Institute.

My Code Institute Mentor provided me with valuable feedback at various stages of the development process. This enabled me to enhance, refine, and finalise the project.
