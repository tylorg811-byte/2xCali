2xCali Premium Artist Website - V3

WHAT CHANGED
- Completely rebuilt layout with clean, readable HTML instead of one-line code.
- Kept the rotating top banner with: Official Videos / Tour Dates / New Releases / Booking Available.
- Added your Elfsight Instagram Feed code into index.html and media.html.
- Changed image paths from assets/images/ to images/.
- Rebuilt the YouTube page using the uploads/videos link you provided.
- Added responsive mobile navigation.

IMAGE FOLDER
Put all artist photos inside the root images folder:

images/hero.jpg
images/portrait.jpg
images/story.jpg
images/release.jpg
images/photo-1.jpg
images/photo-2.jpg
images/photo-3.jpg
images/photo-4.jpg

If your photos have different filenames, either rename them to the names above or update the paths in the HTML/CSS.

YOUTUBE NOTE
The site includes the official videos link:
https://www.youtube.com/@official2xcali1502/videos

The videos page uses this embed:
https://www.youtube.com/embed?listType=user_uploads&list=official2xcali1502

If YouTube blocks it because the channel only has a handle and no legacy username, you will need the channel's Uploads Playlist ID and replace the iframe src with:
https://www.youtube.com/embed/videoseries?list=UPLOADS_PLAYLIST_ID

GITHUB PAGES
Upload these files to the root of the GitHub repo:
index.html
music.html
videos.html
shows.html
media.html
booking.html
css/
js/
images/
