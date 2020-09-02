Hey! These are instructions on how to add new crowdfundign profiles
Inside `<div class="grid">`, add this code and obciosuly modify it:
```html
<div class="grid-item">
          <h3>User Name</h3>
          <h4>How they are associated with VTC</h4>
          <br>
          <img class="pfp" src="pfp/doge.png">
          <h4>Newest Project Looking for Funds</h4>
          <b><a href="/users/user-name/new.html">Learn More</a></b>
          <b><a class="old-projects" href="/users/user-name/old.html">Previous Projects</a></b>
          <h4>XXX VTC/XXX VTC Raised</h4>
        </div>
```
Now, make sure the `href`'s "user-name" with the real username of whoever your adding.
Next, add a folder to the `users` folder. the folder name should be the username earlier. add the `new.html` and `old.html` and `vtc logo.png` files that you see in the example `users/user-name` folder. Modify the `new.html` and `old.html` to fit your needs.