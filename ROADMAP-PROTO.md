# Vuetube Roadmap

_a Vue infused Youtube project_

## Feature Concepts

- Video URL Input
- Playlists List
- Individual Playlist
- Video Display Grid
- Video Item Display

## Development Stories

### **As a User:**

> Playlists
* [ ] I want to be able to see a list of my created playlists. [feature] [visual]
  * [ ] I want see my vuetube stats on each playlist. [visual]
    * [ ] I want to see what date each playlist was created. [visual]
    * [ ] I want to see how many videos are in the playlist. [visual]
    * [ ] I want to see how many videos ive marked as 'watched' in each playlist. [visual]

> Playlist
* [ ] I want to create a playlist of Youtube videos I like. [feature]
  * [ ]  I want to be able to add video URLs to a list that I can access. [action]
    * [ ] I want to see a preview of the video URL so I know its the correct video. [visual]
    * [ ] I want to be able to mark whether I've watched it yet or not. [action] [visual]
    * [ ] I want to be able to remove videos from the playlist. [action]
  * [ ] I want to be able to give this playlist a custom name. [feature] [action] [visual]
    * [ ] I want to be able to edit the playlist name. [action]
  * [ ] I want to be able to delete the playlist, after confirmation. [action] [visual]

> Video Grid
* [ ] I want to see a grid of my added videos [feature] [visual]
  * [ ] Each video grid item should display the video thumbnail, title, channel and "favorite" icon [feature] [visual]
    * [ ] I want each video grid item to display the video thumbnail [visual]
    * [ ] I want each video grid item to show the title of the video [visual]
    * [ ] I want each video grid item to show the name of the channel [visual]
    * [ ] I want each video grid item to have the "Favorite" icon [visual]
      * [ ] I want to be able to toggle the "Favorite" status of the video [feature] [action]
  * [ ] I want the grid to be able to display videos from a selected playlist only [visual]

> Video Item
* [ ] I want to watch the video in-app. [feature]
  * [ ] I want to see a title bar for the video
    * [ ] I want to see how many views the video has [visual]
    * [ ] I want to see how many likes the video has [visual]
    * [ ] I want to be able to open the video in youtube [action]


### 0.1 > PROTOTYPE
* [x] Init Vue.js Project [app]
  * [x] Basic layout design [app]
    * [ ] Add Video [cmp]
      * [ ] Video URL Input [cmp]
      * [ ] Vuetube Playlist Dropdown [cmp]
        * [ ] Add to Existing Playlist [cmp]
          * [ ] Video Info Preview [cmp]
        * [ ] Add to New Playlist [cmp]
          * [ ] New Playlist Title [cmp]
          * [ ] New Playlist Description [cmp]
    * [ ] Manage Playlists [cmp]
    * [ ] Playlist [cmp]
    * [ ] Video Grid [cmp]
      * [ ] Grid Item [reusable_cmp]
    * [ ] Video View [cmp]
      * [ ] Video Thumbnail / Start Screen [cmp]
        * [ ] Toggleable Favorite Icon [slot/cmp]
      * [ ] Video Title Bar [cmp]
        * [ ] Title [reusable_cmp]
        * [ ] Views [reusable_cmp]
        * [ ] Likes [reusable_cmp]
        * [ ] Youtube Link [reusable_cmp]
      * [ ] Channel Info Bar [cmp]
        * [ ] Mystery Component
      * [ ] Video Description [cmp]
    * [ ] Markdown Notes Editor [cmp]
      * [ ] Read/Write Toggle Switch [cmp]
      * [ ] Read Panel [slot/cmp]
      * [ ] Write Panel[slot/cmp]


  * [ ] RW Flexbox Util Lib
  * [ ] Youtube API
    * [ ] Checking for Lib
    * [ ] Might use Vanilla [no wrapper pkg]
