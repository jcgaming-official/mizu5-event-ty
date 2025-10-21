
# Appreciation Letter for PJSK/EnSekai Events

A simple webpage and responsive design of the appreciation letter for Project Sekai / Hatsune Miku: Colorful Stage! Events using Mizu5 theme



## Features

- Mizu5 theme
- Hosted Online using Vercel
- Create unlimited letters
- Mobile and Desktop friendly


## Screenshots
### Desktop Mode
![pop-up](https://i.ibb.co/Kx6BwK7F/1d.png)

![main](https://i.ibb.co/Jwpy6jvy/2d.png)
### Mobile Mode
## Usage/Examples
Change the event banner and your name:
```html
div class="container">
    <div class="header">
      <img src="./your_pathfile_name.png" alt="Event banner" />
      <h1>Appreciation Message</h1>
      <h2>by your name</h2>
    </div>
```

Change/Add/Remove your letter(s):
```html
{
        id: 1,
        discord_name: "Target Name",
        sample_text: "username/short message preview",
        extended_text: "Your letter here",
        profile_image: "./your_pathfile_name.png"
      },
```

Change pop-up message:
```html
 <div id="popup-overlay">
    <div id="popup-message">
      <p>
        write anything here<br>
        Are you sure you want to continue?
      </p>
      <button class="popup-btn" id="cancel-btn">Cancel</button>
      <button class="popup-btn" id="view-btn">View</button>
    </div>
```


## Deployment

To deploy this project, fork this [repository](https://github.com/jcgaming-official/mizu5-event-ty/fork), go to [Vercel](https://vercel.com/), log in with your GitHub account, click Add New → Project, select this repository, keep the default settings, and click Deploy to launch your static website and you are now ready to share the link



## Support the Project ⭐

If you like this project, consider supporting it by giving it a star on GitHub and forking it.
