
Slothrust Official Site
=============
A milestone project displaying my HTML and CSS capabilities.
The project is an official site for a band, in this example the rock group Slothrust.
The site covers a number of essential elements an official band site should contain, helping users better engage with the artist's content (muisic, videoes, images) as well as promoting new music the artist and record label would be looking to sell.

UX
---------------
The intended users of the project are as follows:
* users familiar with the band looking to quickly find specific content they wish to engage with
* users who are aware of the band and do not have an extensive knowledge of their work, but wish to learn more about them
* users who want to find the latest music of said band

The project helps to satisfy each user group's request, it does this through a number of ways, explained as follows:

* users familiar with the band looking to quickly find specific content they wish to engage with
    * This user group may wish to listen to a specific song from the artist. The music page is segmented into albums, so that they do not have to sort through every song the artist has produced. The segmented albums are only visible on click from a dropdown, helping to not overload the user with too much content.
    * Similarily, the videos page offers the opportunity for users to sort through the artist's previous work to find the exact video they are looking for. On clicking a video, they appear in a lightbox modal, improving the viewing experience.
    * The videos page promotes the latest video in a separate section, as this is likely to be the most sought after video around its release. As a user familar with their work, options to purchase the latest track are clearly visible under the video - with a number of options available depending on the user's preference.
    * The tour page makes use of a map menu, which when clicked will take a user to the corresponding continent of tour locations. This user group may likely be aware of the fact the artist is touring close to thier location. They may need a quick way of viewing the touring information in their area, rather than looking through all locations. The ticket purchasing information is also prominent for each location, as a user viewing this information would likely be wishing to attend the event.

* users who are aware of the band and do not have an extensive knowledge of their work, but wish to learn more about them
    * The segmented music page doubles as a discography list, providing user's the opportunity to see how many albums the band have, how their music has changed across each album and how they have changed as a band over time.
    * Links to social profiles are displayed in the footer on every page, helping users learn more about the artist and engage with them on social channels easily.
    * While the gallery section is segmented in any particular way, it's grid format (especially for desktop and tablet) helps users visually engage with the band quickly.
    * This user group may not be aware of the locations the band will be touring, how extensive their tours are and what countries and continents will be part of it. The map menu quickly informs the user which continents the band will be visiting and that their tour is worldwide. By only providing a table of venues, it'd be difficult to see the size of their tour. Without studying each table row, it could be assumed the band is visiting only North America or Europe. The map menu gives an indication of the tour extent.

* users who want to find the latest music of said band
    * A large portion of users will be visiting the site to see the band's latest work, the videos page is one example of how this desire is satisfied. The latest video is given a more prominent section, with more information and links if users wish to purchase the song. Instead of sorting through all videoes, the one that will likely be more sought after is more prominent.
    * On every page, the latest album is promoted. This is both to satisfy this users group's likely interest but also helping the record label in their current aim of selling the latest album. All pages (except for home) have a banner at the footer with a link to purchase the album, the footers placement means it does not detract from the site's main function but helps to promote the album to users who will be receptive.
    * Similarly, the homepage features a background image of the album. This functions as a prominent way of promoting the artist's latest work.

* Both mobile and desktop users may be using the site
    * The site is fully responsive so that both user groups may use the project

Wireframes of the desktop pages can be found [here](https://s3.amazonaws.com/assets.mockflow.com/app/wireframepro/company/C75be0e9612b44582a7f957193df83688/projects/Me9b9df2871d6e69c2e9c209484fed0131539713676270/pages/D9583b6cdf03bb8312221ea009a4f7766/image/D9583b6cdf03bb8312221ea009a4f7766.png)

Wireframes of the mobile pages can be found [here](htt)

Features
---------------
### Existing Features ###
* The burger menu allows mobile users to open and close the menu as they wish
* The menu option currently selected is given a different colour, indicating the page the user is currently on (Screen reader text is also changed)
* Footer and menu links change colour on hover and icon changes to pointer, informing users that it is a link
* Under music, embeded Spotify iframes allow users to play music directly on the page. The iFrame also allows users to view the album on Spotify, share the album and also log in to listen as a paid user
* Embeded Spotify iframes are hidden under an accordian, allowing users to select which album they wish to listen to by clicking on the relevant option
* Under Videos, YouTube iFrames allow the user to view a video directly on the page. The iFrame also allows users to select similar videos, play and pause, adjust settings, play full screen and share online.
* Bootstrap modals allows the user to select a video (except featured) and for it to be played as a pop up modal. The user is able to close this modal using the X icon.
* The tour page allows users to select a specific continent and see events in that area. This is done by clicking on the relevant continent on the map, diverting users to the relevant section in the table.
* For desktop users, this continent menu is selected on hover, allowing them to engage with the map menu and find the relevant location. For mobile, as hover isn't possible, all options are visible on load.
* A back to top button allows users to quickly navigate back to the top of the page for all pages (excluding index). This is especially useful for mobile, on long pages such as gallery or tour.

### Features Left to Implement ###
* For the gallery to allow users to select and image, for it to appear in a pop up modal, and for users to navigate next and previous through the images.
* For the tour map menu to be country specific, however the hover effect may need to be rethought as it could be difficult to use. Moreover the mobile version would also need to be adjusted, as selecting countries could be difficult.
* Allow users to play music through different means, other than Spotify. Either other music platforms or as a music file.

Technologies Used
---------------
* Bootstrap library was used to aid development with its grid system, navigation menu, modals, etc.
[Bootstrap 4.1](https://getbootstrap.com/)
* jQuery was used to aid the implementation of Bootstrap (e.g. the burger menu) and to assist in the video modal
* Google Fonts was used for the implementation of the font Shadows Into Light

Testing
---------------
Test  | Test Actions | Successful | Notes
------------- | ------------- | ------------- | -------------
Desktop mobile  | *buttons react on hover 
*buttons take users to respective page
*active page is clear (both visually and screen reader)| Successful | Notes
Test  | Test Actions | Successful | Notes


Happy coding!
The Cloud9 IDE team

Embed video responsiveness: http://embedresponsively.com/
Add favicon
Overlay play icon on videos

Video modal code was Bootstrap modal and additional help provided by https://codepen.io/anon/pen/LgJRjz. Primarily for jQuery to stop video playing after modal closed. jQuery has been updated
as it was targeting a button with class .video-btn but now targets < a> element with class .video-link (as no buttons are used). Modal has also been styled.


