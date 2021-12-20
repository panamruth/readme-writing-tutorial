<h1 align="center"><img src="https://emoji.slack-edge.com/T0351JZQ0/ga/bc337c95a83930af.png" width="24" height="24"> How to Write a GA SEI Project README <img src="https://emoji.slack-edge.com/T0351JZQ0/ga/bc337c95a83930af.png" width="24" height="24"></h1>
<!-- ###### <h6 align="center">by</h6> -->
<h6 align="center">
   <a href="https://www.linkedin.com/in/amarpan/">Amar Pan
      </a> + <a href="https://www.linkedin.com/in/neilitalia">Neil Italia</a>      <br>
   
      
   <a href="https://www.linkedin.com/in/amarpan/" target="_blank">
      <img src="https://img.shields.io/badge/-linkedin.com/in/amarpan-blue?style=flat&logo=Linkedin&logoColor=white">
 </a>
   <a href="https://www.linkedin.com/in/neilitalia/" target="_blank">
      <img src="https://img.shields.io/badge/-linkedin.com/in/neilitalia-blue?style=flat&logo=Linkedin&logoColor=white">
 </a>    
</h6>
<div align="center">
 
  <!-- <a href="mailto:amar.panjwani@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/-amar.panjwani@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white">
 </a>
 
 <a href="https://www.github.com/amarpan/" target="_blank">
      <img src="https://img.shields.io/badge/-github.com/amarpan-orange?style=flat&logo=GitHub&logoColor=white">
 </a> 

  <a href="https://amarpan.github.io" target="_blank">
    <img src="https://img.shields.io/badge/-Portfolio:_amarpan.github.io-gold?style=flat&logo="
 </a>
   
   <a href="https://www.linkedin.com/in/amarpan/" target="_blank">
      <img src="https://img.shields.io/badge/-linkedin.com/in/amarpan-blue?style=flat&logo=Linkedin&logoColor=white">
 </a>    
  
 <a href="https://medium.com/@amarpan">
    <img src="https://img.shields.io/badge/-medium.com/@amarpan-darkgreen?style=flat&logo=medium">
 </a> -->
    
  ![](https://visitor-badge.glitch.me/badge?page_id=amarpan.readme-writing-tutorial)

</div>

<h4>
The README is often the most overlooked and underestimated aspect of a General Assembly SEI project, frequently left until the very last minute.
And yet, it is what employers directly look at when assessing one's technical competency as a developer.
</h4>

<h4>
Thus, in today's tutorial, we'll take a look at how to write and design a GA SEI README that would make any employer blush.
</h4>

This tutorial assumes you already have some semblance of a README. If you're starting from scratch, however, download my blank skeleton template [here](https://github.com/amarpan/blank-README-template/blob/main/README.md).      

For a quick review on how to use Markdown, go [here](https://www.markdowntutorial.com/). For GitHub-flavored Markdown documentation, go [here](https://github.github.com/gfm/).


<h2  align="center">Header & Description</h2>

<div align="center"> 
  <img src="./images/GOOD-DESCRIPTION-SOLO.png" width="800">
</div>

```html
<div align="center">
   <h1>:school_satchel: :school: MEET YOUR CLASSMATES :school: :school_satchel: </h1>
   <h3>https://meetyourclassmates.herokuapp.com/</h3>
   <h5>Teammate Name | Your Name | Teammate Name </h5>`                             
   <a href="https://yourportfoliolink.com" target="_blank">
      <img src="https://img.shields.io/badge/-Portfolio:_user.github.io-darkgreen?style=flat&logo=medium"/>
   </a>
   <a href="https://www.linkedin.com/in/user/" target="_blank">
      <img src="https://img.shields.io/badge/-linkedin.com/in/user-blue?style=flat&``logo=Linkedin&logoColor=white">
   </a> 
   <a href="mailto:user@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/-user@gmail.com-c14438?style=flat&logo=Gmail&``logoColor=white">
   </a>
   <a href="https://medium.com/@user">
      <img src="https://img.shields.io/badge/-medium.com/@user-black?style=flat&logo=medium">
   </a>
</div>

<h1>:pencil: Description</h1>
<p>Meet Your Classmates is an Instagram-clone and hub where students can get to know and relate to their peers via completion of short 3-question mini-surveys. By learning about others' backgrounds, previous experiences, and interests, an atmosphere of community is created that is conducive to higher levels of learning and success.</p>
```

|            | Instructions |
|------------|--------------|
| Note:      | Each `#` stands for a header of that number in HTML. | 
|            | Ex. `#` is equivalent to `<h1>` |
|            | Ex. `######` is equivalent to `<h6>`|
| Note:      | Integrate styling with `<h1 align="center">` to center text. |
| Note:      | Add your deployed link directly to the top here - many users won't scroll all the way down to find it.
| Note:      | Use emojis by typing in `:emojiname:` Ex. `:school:` ---> :school:
|         | While emojis automatically show on GitHub, to see them on VS Code one needs to install an extension like [this](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji).
|            | A full list of available emojis can be found [here](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

<hr>

<h2  align="center">Screenshots</h2>
<div align="center"> 
   <img src="./images/GOOD-SCREENSHOTS-SOLO.png">   
</div>

```html
<details>
<summary> :bar_chart: ERD</summary>
| Description | Screenshot |
|------------ | ------------|
| <h3 align="center">ERD</h3> | <img src="https://``github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ERD.MYC.png" width="700"> |
</details>

<details>
<summary> :art: Wireframes</summary>
| Description | Screenshot |
|------------ | ------------|
| <h3 align="center">Home Page</h3> | <img src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/Homepage.Wireframe.MYC.png" width="700"/>
| <h3 align="center">Profile Page</h3> | <img src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ProfilePage.Wireframe.MYC.png" width="700"> |
</details>

<details open>
<summary> :gear: Functionality</summary>
| Description | Screenshot |
|------------ | ------------|
| <h3 align="center">Feed Page</h3> | <img src="https://github.com/amarpan/meet-your-classmates/blob/main/public/Screenshots/FeedPage.png?raw=true" width="700"/> |
| <h3 align="center">Profile Page</h3> | <img src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ProfilePage.png" width="700"/> |
</details>
```   

|            | Instructions |
|------------|--------------|
| Note:      | To set up a  table, use: |
|            | `\| Description \| Screenshot\|` |
|            |`\|-------------\|-----------\|`|
|            |`\|   caption   \|   image   \|`|
| Note:      | Whatever is placed in between `<details></details>` will be hidden beneath a closed drop-down menu, until its arrow is clicked on. The title for this should be placed in between `<summary></summary>`. 
| Note:      | To have a drop-down menu display by default without the user having to click it, add the word 'open' to the details tag.
|            |Ex. `<details>`  -->  `<details open>` 
| Note:      |Image dimensions can also be resized by specifying width and height.| 
|            |Ex. `<img src="" width="300" height="400">`| 

<hr>

<h2  align="center">Technologies Used</h2>  

<div align="center"> 
   <img src="./images/GOOD-TECHNOLOGIES-USED-SINGLE.png">
</div>

```markdown
## :computer: Technologies Used

![MongoDB Atlas](https://img.shields.io/badge/-MongoDB-333?style=flat&logo=mongodb)

![Express](https://img.shields.io/badge/-Express-333?style=flat&logo=express)

![React](https://img.shields.io/badge/-React-333?style=flat&logo=react)

![Node](https://img.shields.io/badge/-Node.js-333?style=flat&logo=node.js)

![SemanticUIReact](https://img.shields.io/badge/-Semantic%20UI%20React-333?style=flat&logo=semanticuireact)

![AWS S3](https://img.shields.io/badge/-AWS_S3-333?style=flat&logo=amazons3)

![JWT](https://img.shields.io/badge/-JSON_Web_Tokens-333?style=flat&logo=jsonwebtokens)

![Mongoose ODM](https://img.shields.io/badge/-Mongoose_ODM-333?style=flat&logo=mongodb)

![JavaScript](https://img.shields.io/badge/-JavaScript-333?style=flat&logo=javascript)

![HTML5](https://img.shields.io/badge/-HTML5-333?style=flat&logo=html5)

![CSS3](https://img.shields.io/badge/-CSS-333?style=flat&logo=css3)

![Trello](https://img.shields.io/badge/-Trello-333?style=flat&logo=trello)

![Heroku](https://img.shields.io/badge/-Heroku-333?style=flat&logo=heroku)

![Canva](https://img.shields.io/badge/-Canva-333?style=flat&logo=canva)
```
   
<!-- 
|            | Instructions |
|------------|--------------|
| Note:      | 
 -->

<hr>

<h2  align="center">Getting Started</h2>

<div align="center"> 
   <img src="./images/GOOD-GETTING-STARTED-SINGLE.png">
</div>

```html
<h2> :atom_symbol: Getting Started </h2>

<h3> :calling: Instructions </h3>
<details open>
<summary>How to Create a Post</summary>
<ol>
<li>Type in your answers to each of the 3 randomly-generated mini-survey questions.</li>
<li>Click on "Add Survey" to post your responses so others may see them.</li>
<li>Click on the "X" in the bottom-right corner to delete a post.</li>
</ol>
</details>

<details>
<summary>How to Interact With Others' Posts</summary>
<ol>
<li>Posts may be "liked" or "disliked" by clicking on the thumbs up or down button on their card.</li>
<li>To reveal the author of a post, hover over the "Who could it possibly be?" button.</li>
<li>To see more posts by the same user, click on the revealed username and profile picture.</li>
</ol>
</details>

<details>
<h3> :link: Links </h3>
<summary>Trello Board</summary>   
<a href="https://trello.com/b/x4ViComX/meet-your-classmates-project-4">https://trello.com/b/x4ViComX/meet-your-classmates-project-4</a>   
</details>

<details open>   
<summary>Deployed Link (Heroku)</summary>
<a href="https://meetyourclassmates.herokuapp.com/">https://meetyourclassmates.herokuapp.com/</a>
</details>
```

|            | Instructions |
|------------|--------------|
| Note:      | Use numbered lists as opposed to lengthy paragraphs to make sure this section is easily readable.
| Note:      | Put your links in more drop-down menus using `<details open>` and `<summary>`.
| Note:      | Try to choose something simple and memorable when choosing your Heroku URL / link name.

<hr>

<h2  align="center">Next Steps</h2>

<div align="center"> 
   <img src="./images/GOOD-NEXT-STEPS-SINGLE.png"> 
</div>

```markdown
## :fast_forward: Next Steps   

### Upcoming Features

- [X] Add gifs to animated sliding buttons   

- [ ] Add comment functionality on posts to encourage discussion   

- [ ] Add edit and update functionality for a user's profile  

- [ ] ~~Add Tinder API Integration~~
```

|            | Instructions |
|------------|--------------|
| Note:      | Try to avoid using the word "icebox", as most non-technical users probably won't know what this means.
| Note:      | Use bullet points rather than paragraphs to make it immediately clear what each new feature would be.

<hr>

<h2 align="center">The Final Product</h2>


<div align="center">
 <img align="center" src="./images/GOOD-FULL-README.png">  
</div>

<!-- <h4>Today we learned how to convert an average README into one that instantly catches the eyes of employers.</h4>
<h4>Despite not being able to use proper CSS to change colors and styles, we can actually add a lot of customization and fine-tuning with the right Markdown shortcuts.</h4> -->

<hr>

<h1 align="center">Optional Additions</h1>
<h6 align="center">by <br> Neil Italia GA SEI Oct '21 Dallas, TX
<h2 align="center">Header Banner</h2>

<div align="center"> 
   <img src="./images/OPTIONAL-PROJECT-BANNER.png"> 
</div>

```html
<div align="center">
   <img src="https://i.imgur.com/y2SPx4E.jpg" width="800" height="400" />
   <h1 align="center">plantrade</h1>
</div>
```

|       | Instructions |
|-------|--------------|
| Note: | Royalty-free stock photos can be found on [Pexels](https://www.pexels.com/), [Pixabay](https://pixabay.com/), or [Unsplash](https://unsplash.com/). |
| Note: | Free photo editing tools like [Photopea](https://www.photopea.com/) can streamline the editing process with their ability to import images from URLs and export images directly into [imgur](https://imgur.com/). |

<hr>

<h2 align="center">Emoji Commits</h2>

<div align="center"> 
   <img src="./images/OPTIONAL-COMMITS.png" width="800" /> 
</div>

```console
git commit -m ":pencil2: fix typo on cart page"
```

|       | Instructions |
|-------|--------------|
| Note: | GitHub-friendly commit emojis can be found on [gitmoji](https://gitmoji.dev/). |

<hr>

<h2 align="center">Horizontal Image Scroll (Carousel) Hack</h2>

<div align="center"> 
   <img src="./images/OPTIONAL-CAROUSEL.png" width="800" /> 
</div>

```html
<pre>
  <img src="https://i.imgur.com/NdzHyyX.png" width="700" height="500" />
  <img src="https://i.imgur.com/XIxBAcO.png" width="700" height="500" />
  <img src="https://i.imgur.com/tYVxWvF.png" width="700" height="500" />
  <img src="https://i.imgur.com/vRjshke.png" width="700" height="500" />
  <img src="https://i.imgur.com/qap5IXS.png" width="700" height="500" />
</pre>
```

|       | Instructions |
|-------|--------------|
| Note: | This works best with images of similar heights. |

## Full README Examples

</details>
 </h5>
 <details open>
<summary>   
Amar 'Pan' Panjwani - GA SEI Nov '21 - Apple Valley, CA (Los Angeles)   
</summary>
<h4> 

https://github.com/amarpan/meet-your-classmates

</h4>
</details>


<details open>
<summary>   
Neil Italia - GA SEI Oct '21 - Dallas / Fort Worth, TX   
</summary>
<h4> 

https://github.com/neilitalia/ilovehue 

https://github.com/neilitalia/plantrade

https://github.com/neilitalia/spacex-flights


</h4>


 
 ## Future Updates

- [x] Add contributions
- [x] Add examples from other GA students
- [x] Add code samples
- [x] Add horizontally-scrolling images how-to
 
## Contributions
<details>
<summary>Neil Italia - GA SEI Oct '21 - Dallas / Fort Worth, TX </summary>
<h4> UX/ UI, Code Samples, Header Banner, Emoji Commits, Carousel Horizontally Scrolling Images Slider</h4>
</details>

<details>
<summary>Olivia Emery - GA SEI Oct '15 - San Francisco, CA (Mountain View) - Technical Writer @ Google</summary>
<h4> Editing, Suggestions for Clarity of Writing</h4>
</details>


<details>
<summary>Isaac Ferrero - GA SEI Nov '21 - Seattle, WA (Bremerton)   </summary>
<h4> Proofreading, Editing, and Quality Assurance </h4>
</details>

<details>
<summary>Miguel Urena - GA SEI Nov '21 - Los Angeles, CA (Anaheim, CA)   </summary>
<h4> Graphic Design, Social Media Rich Preview Banner, Quality Assurance </h4>
</details>
   
<details>
   <summary>
      Amar (Pan) Panjwani - GA SEI Nov '21 - Los Angeles, CA (Apple Valley, CA) - IT Manager at Summit Medical
   </summary>
      <h4>
      Literally everything else + making/conceptualizing this in the first place because my classmates' READMEs sucked
   </h4>
   </details>



