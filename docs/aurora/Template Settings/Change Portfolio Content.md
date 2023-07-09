
---
sidebar_position: 2
---

# Change Portfolio Card Content
This page will tell you how to change Portfolio content.

1. Login to your ACP and go to Configuration > General Settings
2. - In the dropdown "Homepage type" set Custom Content

## Custom Portfolio Card Content
1. Logon to your FTP client (ex, FileZilla)
2. Go to folder > custom > templates > Aurora
3. Open the file index.tpl
4. At line 95 Modify the content inside `Portfolio Card 1` and set it according to you
  ```html
           <div class="eight wide column">
              <div class="ui segment" style="height:100%;">
                <div class="ui header">My Project <a href="#" target="_blank" class="ui mini blue button right floated">Website</a></div>
                  <div class="ui slide masked reveal image">
                    <img src="SET IMAGE URL HERE" class="visible content" style="border-radius:2%;">
                    <img src="SET IMAGE URL HERE (HIDEN)" class="hidden content"  style="border-radius:2%;">
                  </div> 
               </div>
           </div>
```
You can create multiple cards like this. Set "SET IMAGE URL HERE" from example shown to any url you want. It must have .png or .jpeg at the end!

### Community Support
Feel free to join our [discord](https://discord.gg/creativmap) server for template support.